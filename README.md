### ![header](https://capsule-render.vercel.app/api?type=waving&color=7F7FD5&text=%20Jaesung&nbsp;Park%20%20&height=200&fontSize=90&fontColor=ffffff)


<h1 align="center">STACKS</h1>


<p align="center">
  <img src="https://img.shields.io/badge/Java-007396?logo=java&logoColor=white&style=flat-square" alt="Java" /> 
  <img src="https://img.shields.io/badge/Spring-6DB33F?logo=spring&logoColor=white&style=flat-square" alt="Spring" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?logo=spring-boot&logoColor=white&style=flat-square" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/JPA-004D40?logo=hibernate&logoColor=white&style=flat-square" alt="JPA" />
  <img src="https://img.shields.io/badge/Thymeleaf-005F73?logo=thymeleaf&logoColor=white&style=flat-square" alt="Thymeleaf" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/JavaScript-323330?logo=javascript&logoColor=F7DF1E&style=flat-square" alt="JavaScript" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white&style=flat-square" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white&style=flat-square" alt="CSS3" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white&style=flat-square" alt="MySQL" />
  <img src="https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white&style=flat-square" alt="Redis" />
  <img src="https://img.shields.io/badge/JWT-000000?logo=jsonwebtokens&logoColor=white&style=flat-square" alt="JWT" />
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white&style=flat-square" alt="Docker" />
  <img src="https://img.shields.io/badge/RabbitMQ-FF6600?logo=rabbitmq&logoColor=white&style=flat-square" alt="RabbitMQ" />
</p>

## 주요 프로젝트

### 1. [Book-Dream-Portfolio](https://github.com/yoki06161/Book-Dream-Portfolio)
> **중고 서적 거래 & 실시간 채팅(WebSocket) 기능 구현**

- **주요 기술 스택**: Spring Boot, Spring Data JPA, MySQL, Thymeleaf, JavaScript, WebSocket(SockJS + STOMP), Jsoup  
- **주요 기능**  
  - **중고책 등록** 시 알라딘 도서 정보(제목/이미지 등) 자동 크롤링  
  - **실시간 채팅(WebSocket)**: 1대1 메시지 전송, 이미지 전송, 안 읽은 메시지 수 표시  
  - **판매 상태(예약중/거래완료 등) 관리** 로직  
- **특이사항**  
  - Jsoup 사용한 **크롤링** 구현  
  - WebSocket 환경 설정 & 메시지 송수신 프로세스(Controller/Service/Entity) 설계  

---

### 2. [Food-Delivery](https://github.com/yoki06161/Food-Delivery)
> **Spring Boot + JPA + Redis + JWT + WebSocket + OAuth2(구글) 로그인** 등 다양한 기능 통합 구현

- **주요 기술 스택**: Spring Boot, Spring Security, JWT, OAuth2(Client), JPA, Redis, WebSocket(STOMP), MySQL  
- **주요 기능**  
  - **회원 권한**(CUSTOMER, OWNER, RIDER, ADMIN)별로 다른 비즈니스 로직 적용  
  - **주문-결제-배달 전체 플로우** 간단 시뮬레이션  
  - **Redis 캐싱** & WebSocket 을 통한 실시간 위치(라이더) 업데이트  
  - **Google OAuth2** 로그인 후 JWT 발급  
- **특이사항**  
  - 배달 상태 변경을 실시간으로 확인할 수 있는 **WebSocket** 브로드캐스팅  
  - **SpringDoc(Swagger)** 사용으로 API 문서화

---
### 3. [E-Commerce](https://github.com/yoki06161/E-Commerce)
> **간단한 전자상거래 시스템**

- **주요 기술 스택**: Spring Boot, Spring Data JPA, MySQL, RabbitMQ, Docker Compose
- **주요 기능**  
  - **회원(User)・상품(Product)・주문(Order)** 도메인 설계  
  - **주문 생성 시 재고 차감** 및 **RabbitMQ** 이벤트 발행  
  - Docker Compose를 이용해 **MySQL & RabbitMQ**를 로컬 환경에서 간단 실행  
- **특이사항**  
  - 주문 성공 시 **재고 감소** + **이벤트 발행** → Consumer가 이벤트 처리 (확장 시, 배송/알림 등)  
  - 향후 JWT 인증, 결제 로직, CI/CD 등 기능 확장 가능
---
### 4. [Movie-Booking](https://github.com/yoki06161/Movie-Booking)
> **간단한 영화 예매 시스템**

- **주요 기술 스택**: Spring Boot, Spring Data JPA, MySQL, Redis, Docker, JWT  
- **주요 기능**  
  - **영화 정보** & **상영 스케줄** 조회, 좌석 예매  
  - 예매 시 **동시성 제어(비관적 락)** 적용으로 좌석 중복 예약 방지  
  - **Docker & docker-compose** 를 이용해 MySQL, Redis, Spring Boot 컨테이너 실행  
- **특이사항**  
  - **Redis**로 인기 영화 목록 캐싱 → DB 부하 감소  
  - **Swagger(OpenAPI)** 로 주요 Endpoint 확인 및 테스트

