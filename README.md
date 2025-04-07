# OTel

문제점	→ OpenTelemetry + Tempo가 어떻게 해결함?
요청 흐름 추적 안 됨	→ trace-id 따라가며 요청 흐름 시각화 가능 (A → B → C)
로그가 서비스마다 따로 있음	→ trace-id 기준으로 연관 로그 연결 가능
어디서 느려졌는지 모름	→ Tempo에서 병목 서비스가 시각화됨 (span time으로 확인)
서비스 많아질수록 디버깅 지옥	→ 모든 서비스에 OTel 적용만 하면 자동 추적됨
