<h1>Hi, I'm YuJin 👋</h1>

## 🛠 Tech Stack

**Frontend**

![React](https://img.shields.io/badge/React_19-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Zustand](https://img.shields.io/badge/Zustand-443E38?style=for-the-badge&logo=react&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white)

**Backend**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-DC382D?style=for-the-badge&logo=databricks&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle_DB-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

**Infra & Tools**

![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

<br/>

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=PYJ0915&show_icons=true&theme=default&hide_border=true" height="160"/>
  &nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=PYJ0915&layout=compact&theme=default&hide_border=true" height="160"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=PYJ0915&theme=minimal&hide_border=true&area=true" width="95%"/>
</p>

<br/>

---

## 🗂 Projects

---

### 🎭 OPUS — 예술 통합 문화 플랫폼

> 전시·공연 탐색부터 굿즈 구매, 미술품 경매까지 하나의 플랫폼에서 경험하는 예술 서비스

![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle_DB-F80000?style=flat-square&logo=oracle&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat-square)
![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

팀 프로젝트 종료 후 개인 리팩토링 브랜치를 운영하며 기능 고도화 진행 중

| 구현 포인트 | 내용 |
|---|---|
| 🔨 **실시간 경매** | WebSocket(STOMP) 기반 실시간 입찰, START_DATE 스케줄러로 LIVE 자동 전환 |
| 🔍 **통합 검색** | 헤더 실시간 드롭다운 미리보기 + 전체 검색 결과 페이지 |
| 💳 **결제 플로우** | Toss Payments 연동, 모바일 취소 엣지케이스 및 READY 주문 정리 처리 |
| 🗃 **API 캐시 폴백** | KCISA/KOPIS 장애 시 Oracle `STAGE_CACHE` 테이블로 서비스 유지 |
| 🤖 **AI 추천 패널** | GPT-4o-mini 기반 전시·공연 취향 추천, AI 챗봇과 상태 공유 |
| 🔐 **보안 개선** | JWT 서명키 고정, `memberNo` 클라이언트 전송 → 서버 JWT 추출로 전환 |
| 📱 **반응형** | 4단계 미디어 쿼리(Desktop / Tablet / Mobile L / Mobile S) 전 페이지 적용 |

---

### 🐝 HOBEE — 취미 기반 커뮤니티 플랫폼

> 취미 적성 검사로 나에게 맞는 취미를 발견하고, 같은 관심사를 가진 사람들과 소통하는 커뮤니티

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle_DB-F80000?style=flat-square&logo=oracle&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat-square)

팀 프로젝트 이후 개인 리팩토링 1·2차 완료 및 기능 추가 진행

| 구현 포인트 | 내용 |
|---|---|
| 💬 **실시간 채팅** | WebSocket(STOMP) 기반 1:1·단체 채팅, 타이핑 인디케이터, 읽지 않은 메시지 뱃지 |
| 🤝 **모임 모집** | 카카오맵 장소 검색, 참여 신청·수락·거절, 확정 시 단체 채팅방 자동 생성 |
| 🏆 **챌린지** | 인증(이미지 첨부)·달성률 표시, `@Scheduled` 자동 마감, 달성 시 알림 발송 |
| 🔔 **팔로우 & 알림** | 팔로우·게시글·댓글·모임·챌린지 이벤트 실시간 알림 드롭다운 |
| ♻️ **리팩토링** | 게시판 3개 Controller → `boardCode` 기반 단일 Controller 통합 (코드량 60% 감소) |
| 🖼 **이미지 처리** | Thumbnailator 적용, 프로필 300×300 크롭·게시글 최대 1200px 리사이징 |
| 🔒 **트랜잭션 안전성** | 파일 저장 실패 시 `RuntimeException` throw → DB 불일치 롤백 보장 |

<br/>

---
