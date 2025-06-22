# 🌈 Welcome to MoonoZ

> 🐙 무너와 함께하는
> ✨ *MZ세대를 위한 스마트한 LG U+ 혜택 큐레이션 서비스* ✨


## 프로젝트 개요

- **프로젝트명**: MoonoZ
- **팀명**: 4EVER0
- **주제**: LG U+ 요금제 추천 AI 챗봇 서비스
- **동기**: 경기 불황 속에서 합리적 소비를 추구하는 구독 친화적 MZ세대에게 성향 기반 LG U+ 상품 추천으로 스마트한 소비 지원
- **타겟층**: 합리적 소비를 추구하는 MZ세대
- **개발 기간**: 2025.06.04 ~ 2025.06.26 (약 3주)

## 팀원 소개

| [이영주](https://github.com/abyss-s) | [박교녕](https://github.com/kny0ng125) | [박지회](https://github.com/jihoi0615) | [이은채](https://github.com/eunchrri) | [홍민주](https://github.com/illustermin) |
| :---: | :---: | :---: | :---: | :---: |
| <img src="https://avatars.githubusercontent.com/u/77565980?v=4" width="100" /> | <img src="https://avatars.githubusercontent.com/u/80964083?v=4" width="100" /> | <img src="https://avatars.githubusercontent.com/u/197379577?v=4" width="100" /> | <img src="https://avatars.githubusercontent.com/u/171488704?v=4" width="100" /> | <img src="https://avatars.githubusercontent.com/u/134802163?v=4" width="100" /> |
| **조장**, 프로젝트 총괄<br/>AI 챗봇 설계<br/>요금제 및 구독 API 개발<br/>네이버 API 연동 | OAuth 소셜로그인<br/>회원 관리<br/>핫플레이스 페이지<br/>인프라 관리 | 플로우 차트 설계<br/>좋아요 기능<br/>BEST 혜택 3 API 개발<br/>UBTI 페이지 구현 | 프로토타입 설계<br/>출석체크 및 미션<br/>페이지 구현 | 유플투플 쿠폰 관리<br/>API 개발<br/>홈 화면 및<br/>마이페이지 구현 |

## 프로젝트 목적

- **시장 배경**
    - 최근 경기 불황과 구독료 인상으로 **MZ세대의 합리적 소비 지향**이 뚜렷해짐
    - 최근 LG유플러스의 '유독픽' 과 같은 구독 통합 상품이 **20·30대 가입자 비중 71%** 달성
    - **개인 라이프스타일 최적화된 통합 서비스**에 대한 수요 급증
- **개발 목표**
    - **AI 챗봇 기반 성향 분석**을 통한 맞춤형 요금제 및 서비스 추천
    - **MZ세대의 스마트한 통신 라이프스타일** 지원

## 주요 기능

### **1. AI 기반 추천 & 멀티턴 챗봇 시스템**
- LangChain + OpenAI GPT를 활용한 자연어 기반 요금제 및 구독 서비스 추천
- 사용자 응답 기반 UBTI 성향 분석 → 유형별 맞춤형 상품 추천
- Redis 기반 세션 관리로 연속적인 대화 흐름 유지 및 실시간 스트리밍 응답

### **2. 위치 기반 혜택 & 개인화 추천 서비스**
- Naver Geolocation 및 Maps API 연동하여 내 위치 반경 내 라이프스타일 팝업 탐색
- 사용자가 선호한 서비스 데이터를 기반으로 유사 구독 서비스 추천
- 좋아요 클릭 시 응답 기다리지 않고 UI 선반영하는 낙관적 업데이트

### **3. 소셜 로그인 & 크로스플랫폼**
- Spring Security + OAuth2 클라이언트를 통한 카카오/네이버/구글 인증
- 반응형 UI로 웹과 모바일 환경 모두 최적화된 사용자 경험 제공
- JWT 기반 보안 토큰 관리 및 Zustand로 사용자 세션 유지

## 기술 스택

| 분야 | 기술 스택 |
|------|-----------|
| **Frontend** | ![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white) ![Zustand](https://img.shields.io/badge/Zustand-FF6B35?style=flat&logo=zustand&logoColor=white) ![React Query](https://img.shields.io/badge/React_Query-FF4154?style=flat&logo=reactquery&logoColor=white) ![Axios](https://img.shields.io/badge/Axios-5A29E4?style=flat&logo=axios&logoColor=white) |
| **Backend** | ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=spring-boot&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?style=flat&logo=JSON%20web%20tokens&logoColor=white) ![OAuth2](https://img.shields.io/badge/OAuth2-4285F4?style=flat&logo=oauth&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white) ![JPA](https://img.shields.io/badge/JPA-59666C?style=flat&logo=hibernate&logoColor=white) ![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat&logo=swagger&logoColor=black) |
| **AI Server** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white) ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white) ![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat&logo=sqlalchemy&logoColor=white) |
| **Infrastructure** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=flat&logo=amazon-ec2&logoColor=white) ![AWS RDS](https://img.shields.io/badge/AWS_RDS-527FFF?style=flat&logo=amazon-rds&logoColor=white) ![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=flat&logo=amazon-s3&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white) |
| **Development Tools** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white) ![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat&logo=jira&logoColor=white) ![Notion](https://img.shields.io/badge/Notion-000000?style=flat&logo=notion&logoColor=white) ![Confluence](https://img.shields.io/badge/Confluence-172B4D?style=flat&logo=confluence&logoColor=white) ![Discord](https://img.shields.io/badge/Discord-5865F2?style=flat&logo=discord&logoColor=white) ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white) |
| **UI/UX & Testing** | ![Shadcn/ui](https://img.shields.io/badge/Shadcn%2Fui-000000?style=flat&logo=shadcnui&logoColor=white) ![Storybook](https://img.shields.io/badge/Storybook-FF4785?style=flat&logo=storybook&logoColor=white) ![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=flat&logo=eslint&logoColor=white) ![Prettier](https://img.shields.io/badge/Prettier-F7B93E?style=flat&logo=prettier&logoColor=black) ![Husky](https://img.shields.io/badge/Husky-42B883?style=flat&logo=husky&logoColor=white) |

## 시스템 아키텍처
![system-architecture](https://github.com/user-attachments/assets/23b5d5b9-4266-42d5-89d6-c6d473e630b8)


## 프로젝트 관련 문서
- [WBS](https://docs.google.com/spreadsheets/d/1ln5VudFdBKMbaNANwzZyW0CGLYC_R9Xf/edit?usp=sharing&ouid=101077923369398316818&rtpof=true&sd=true)
- [플로우 차트](https://www.figma.com/proto/C1HjN8qg3Vptm2j7k2cT8N/%ED%94%8C%EB%A1%9C%EC%9A%B0%EC%B0%A8%ED%8A%B8?node-id=1-4&t=OH4mgwF8RPp4bDv8-1&scaling=scale-down-width&content-scaling=fixed&page-id=0%3A1)
- [API 명세서](https://hollow-cello-87b.notion.site/1fb3347f51ee81269bceeaad7f3c76f1?v=1fb3347f51ee81719ba1000c67dfe978)
- [ERD](https://dbdiagram.io/d/DB_4ever0-684e577c3cc77757c8eaba7c)
- [Storybook](https://6835efb2a0dda6635d6b2c1d-nazyzhfott.chromatic.com)

---
**Team 4EVER0** | LG U+ URECA 프론트엔드 개발자 과정 2기 종합프로젝트 4조
