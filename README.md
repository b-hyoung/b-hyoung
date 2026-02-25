### Next.js 기반 프론트엔드 개발자
### 데이터 기반 구조로 유지 보수 가능한 웹을 설계합니다

**Frontend**: Next.js · TypeScript · TailwindCSS · Zustand · React Query  
**Backend**: Django · Python · MySQL · TCP Socket  
**Infra**: AWS(S3, EC2, CloudFront) · Docker
---

## 🛠 Skills

### 🎨 Front-End (Main)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwind-css&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-000000?style=flat-square)
![React Query](https://img.shields.io/badge/ReactQuery-FF4154?style=flat-square&logo=react-query&logoColor=white)

- Next.js App Router 기반 웹 구조 설계
- 정적 페이지를 데이터 기반 자동 렌더링 구조로 전환
- WebSocket을 활용해 실시간 게임 상태를 UI에 반영
- 상태 관리(Zustand) 및 서버 상태 관리(React Query)
- LCP 기준 초기 로딩 성능 최적화 경험(3s -> 1s)

---

### 🐍 Back-End (Project-level)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

- Django 기반 REST API 구현
- 인증·CRUD 중심 개인 프로젝트 경험
- TCP 소켓 기반 원격 제어 서버와 센서 이벤트 흐름을 설계·총괄
- 센서 트리거 → LLM → STT/TTS 음성 루프를 운영 기준(임계치·쿨다운)으로 설계

※ 백엔드는 서비스 구조 이해 및 프론트엔드 연동 목적의 사용 경험 중심

---

### ☁️ Cloud & Infra (AWS)
![AWS EC2](https://img.shields.io/badge/AWS%20EC2-FF9900?style=flat-square&logo=amazon-ec2&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS%20S3-569A31?style=flat-square&logo=amazon-s3&logoColor=white)
![CloudFront](https://img.shields.io/badge/CloudFront-F47421?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

- S3 + CloudFront 기반 정적 웹 배포
- EC2 + Nginx + Gunicorn 서버 구성
- AWS Budgets를 활용한 비용 감소
---

## 🚀 최근 프로젝트

### 🛸 AI Serbot(AIot) – 재난 현장 원격 관제 시스템
**형태**: 4인 팀 프로젝트  
**역할**: PM · 소켓 서버 설계 및 제어 흐름 총괄

- 재난 현장 선진입 로봇을 원격 제어·모니터링하는 통합 관제 시스템
- TCP 소켓 기반 원격 제어 및 센서·영상 실시간 모니터링

**AI 음성 인터랙션**
- 센서 이벤트 발생 시 상태 요약 → LLM 응답 → TTS 안내로 이어지는 음성 피드백 흐름 설계
- 관제 인력 음성 응답을 STT로 수집해 컨텍스트를 갱신하는 양방향 음성 루프 구성

### [🧠 Core-CBT – 자격시험 CBT 학습 서비스](https://github.com/b-hyoung/Core-CBT)
**형태**: 1인 개발 프로젝트  
**역할**: 서비스 설계 · 구현 · 운영

**실사용 기반 개선**
- 실제 사용자 피드백과 운영 데이터를 바탕으로 기능을 반복 개선하였습니다.

**운영·기능**
- GPT 보조 해설에 캐시 재사용 구조를 적용하여 중복 호출 비용 40% 절감
- 문제 신고 발생 시 디스코드 알림으로 즉시 확인하고 관리자 페이지에서 처리
- 방문/완료/합격률 기반 관리자 대시보드로 사용자 학습 행동 분석

---

| 프로젝트 | 설명 | 링크 | 역할 |
|--------|------|------|------|
| **포트폴리오 & 블로그** | Django기반 웹 | [자기소개 블로그](https://django-myportpolio.onrender.com/) | 1인 개발 |
| **kumamid** | 졸업작품전 웹사이트 |[kumamid](https://kmid.netlify.app) | 2인 개발 |
| **ai-serbot** | 구조현장-ai(AIot_rbot) |[깃허브](https://github.com/b-hyoung/Ai_serbot-project) | 4인 개발 |
| **Core-CBT** | 정처산기·SQLD CBT |[Core-CBT](https://jvbhs.netlify.app) | 1인 개발 · 오픈소스 운영  |


---

<a href="https://www.gitanimals.org/en_US?utm_medium=image&utm_source=b-hyoung&utm_content=farm">
<img
  src="https://render.gitanimals.org/farms/b-hyoung"
  width="400"
  height="150"
/>
</a>
