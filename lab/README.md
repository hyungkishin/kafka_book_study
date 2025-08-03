## Kafka 실습 환경 구성 디렉토리
- docker-compose.yml: Kafka + Zookeeper 구동 설정
- README.md: lab 사용 방법 (예: bash scripts/produce.sh)
- scripts: Kafka CLI 자동 실행 스크립트
  - 예: 토픽 생성, 메시지 생산/소비
- config: server.properties: 브로커 설정값
- topic-config.sh: 토픽 설정 자동화 스크립트