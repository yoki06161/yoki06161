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

### 1. [Solebid](https://github.com/yoki06161/Solebid)
> **스니커즈 경매 기반 이커머스 서비스**

- **주요 기술 스택**
  - **Frontend**: React, TypeScript, Vite, Tailwind CSS, React Router
  - **Backend**: Spring Boot, Spring Security, JPA, MySQL, Redis, AWS S3
- **주요 기능**
  - **실시간 경매**: SSE(Server-Sent Events)를 이용한 실시간 입찰 정보 업데이트
  - **결제 시스템**: PortOne 연동을 통한 포인트 충전 및 결제
  - **상품 등록**: AWS S3 프리사인(pre-signed) URL을 활용한 이미지 업로드
  - **사용자 기능**: 소셜/이메일 로그인, 프로필 관리, 위시리스트, 장바구니, 주문 내역 조회
- **특이사항**
  - React 19, TypeScript 등 최신 프론트엔드 기술 스택 활용
  - SSE를 적용하여 실시간성이 중요한 경매 기능 구현

 ---
 
### 2. [Book-Dream-Portfolio](https://github.com/yoki06161/Book-Dream-Portfolio)
> **중고 서적 거래 & 실시간 채팅(WebSocket) 기능 구현**


- **주요 기술 스택**: Spring Boot, Spring Data JPA, MySQL, Thymeleaf, JavaScript, WebSocket(SockJS + STOMP), Jsoup  
- **주요 기능**  
  - **중고책 등록** 시 알라딘 도서 정보(제목/이미지 등) 자동 크롤링  
  - **실시간 채팅(WebSocket)**: 1대1 메시지 전송, 이미지 전송, 안 읽은 메시지 수 표시  
  - **판매 상태(예약중/거래완료 등) 관리** 로직  
- **특이사항**  
  - Jsoup 사용한 **크롤링** 구현  
  - WebSocket 환경 설정 & 메시지 송수신 프로세스(Controller/Service/Entity) 설계  



