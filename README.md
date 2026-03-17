**Developer 정재빈**

빠른 적응력과 끈기를 바탕으로 문제를 단계별로 해결해나가는 개발자 정재빈입니다.


### Project

- 포인트 및 정산 시스템
  - 포인트 및 정산 로직, API + 스케줄러 처리, 대용량 데이터 Spring Batch 처리

- 로그인 / 인증 시스템  
  - 세션 기반 인증(Redis), Third-party SSO 연동

- 주문 시스템
  - 장바구니/주문/배달 도메인, 이벤트 기반 구조, Outbox 패턴

- 결제 시스템
  - Kafka, 비동기 처리, 결제 프로세스

- 실시간 예약 시스템
  - WebSocket, 중복 예약 방지

### 장애 및 문제 경험

- Redis
  - 세션 데이터 증가 + 단일 노드 환경에서 장애 발생
  - 만료되지 않은 데이터 확인, 세션 데이터 축소, Sentinel/Cluster 필요성 인지, API 서킷 브레이크/슬로우 스타터 

- 포인트 불일치
  - 포인트 잔액과 히스토리 간 불일치 문제 경험, 동시성 문제 발견
  - race condition, lost update, 낙관적락/비관적락/분산락 학습 및 낙관적 락 적용

- Spring Batch
  - 정산 배치 병렬 처리, 과도한 스레드 사용, DB connection pool 고갈
  - 스레드 수 및 커넥션 관리의 중요성 이해, 적당한 스레드 개수 확인

### Contect
- <a href="mailto:jaebin2586@gmail.com"><img src="https://img.shields.io/badge/Gmail-d14836?style=flat-square&logo=Gmail&logoColor=white&link=jaebin2586@gmail.com"/></a>


