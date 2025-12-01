<div align="center">
  <h1>🎭 OMIJOY</h1>
  <strong>공연과 공연장을 한 번에 탐색하고, 저장하고, 공유하는 공연 플랫폼</strong>
</div>

<br />

## 📋 프로젝트 개요
- **프로젝트명**: 오미조이 (OMIJOY)
- **팀명**: OMIJA
- **개발 기간**: 2025년 ~ (진행형, 세부 기간 추후 보완)
- **프로젝트 타입**: Full-stack Web Application (React + Spring Boot)

## 🎯 개발 배경

코로나 이후 공연·문화 산업은 다시 활성화되었지만, 여전히 **공연 문화에 익숙하지 않은 사용자들은 정보 접근성이 낮고** 적절한 공연 정보를 얻기 어렵습니다. 지역별·장르별로 흩어진 정보를 찾고, 예매 사이트를 일일이 옮겨 다니며 확인하는 과정은 번거롭고 비효율적입니다.  

OMIJOY는 **KOPIS 공공 데이터와 Kakao 지도, 소셜 로그인, 즐겨찾기/플래그 기능**을 결합하여,

- 공연 정보(지역별/장르별)를 한 곳에서 모아보고,
- 공연장 위치와 편의시설, 진행 중인 공연을 지도에서 확인하며,
- 마음에 드는 공연·공연장을 저장하고,  
- 좋아요(즐겨찾기)한 공연 목록을 **링크로 공유**할 수 있는

**공연·공연장 통합 플랫폼**을 목표로 제작되었습니다. :contentReference[oaicite:0]{index=0}

---

## ✨ 주요 기능

**공연 탐색**부터 **위치 기반 공연장 정보**, **즐겨찾기/플래그 관리**, **관리자 대시보드**까지 통합 제공됩니다.

### 🎫 공연 탐색 및 상세 보기

- **홈 화면**
  - 박스오피스 Top10, 할인/키즈/수상작/예정 공연 섹션
  - 각 공연을 클릭 시 상세 모달로 주요 정보 제공
- **공연 목록 페이지**
  - 장르, 기간 등 다양한 조건으로 **검색 / 필터 / 정렬**
  - 카드형 리스트로 공연 탐색
- **공연 상세 페이지**
  - 기간, 장소, 포스터, 상세 설명
  - 예매 사이트 및 제작사 정보로 이동 가능

### 🗺️ 공연장 지도 및 위치 기반 서비스

- Kakao 지도 기반 **공연장 지도 페이지**
- 현재 위치 또는 선택한 지역(시·군·구) 주변 공연장 조회
- 공연장 마커 클릭 시
  - 공연장 상세 정보 (주소, 편의시설 등)
  - 해당 공연장에서 진행 중인 공연 목록 모달로 제공

### 💖 개인화 & 공유

- **마이페이지**
  - 내가 저장한 공연 **즐겨찾기(Favorite) 리스트**
  - 공연장 **플래그(Flag) 리스트** – 자주 가는 공연장 북마크
- **공연 공유 기능**
  - 좋아요한 공연 목록을 **링크 형태로 다른 사용자에게 공유** 가능

### 👤 인증 & 관리자 기능

- **인증**
  - 이메일/비밀번호 로그인
  - Google / Naver / Kakao **소셜 로그인(OAuth2)**
  - CapsLock 감지, 로그인 실패 시 스낵바 알림
  - 회원가입 시 이메일/비밀번호 형식 검증, 비밀번호 일치 확인
- **관리자 대시보드**
  - 월별 일간 신규 가입자 라인 차트
  - 최근 7일 방문 수 바 차트
  - 즐겨찾기 Top10 공연 테이블
  - 사이드바 기반 관리자 전용 메뉴

---

## 🛠️ 기술 스택

### Frontend
<p>
  <img src="https://img.shields.io/badge/React-18.2.0-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-5.0.2-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Vite-4.4.5-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
  <img src="https://img.shields.io/badge/Axios-1.13.1-5A29E4?style=for-the-badge&logo=axios&logoColor=white" />
  <img src="https://img.shields.io/badge/Zustand-5.0.8-764ABC?style=for-the-badge&logo=react&logoColor=white" />
  <img src="https://img.shields.io/badge/TanStack_Query-5.90.7-FF4154?style=for-the-badge&logo=react-query&logoColor=white" />
  <img src="https://img.shields.io/badge/React_Router_Dom-7.9.5-CA4245?style=for-the-badge&logo=react-router&logoColor=white" />
</p>

<p>
  <img src="https://img.shields.io/badge/MUI-7.3.5-007FFF?style=for-the-badge&logo=mui&logoColor=white" />
  <img src="https://img.shields.io/badge/Emotion-11.x-DB7093?style=for-the-badge&logo=emotion&logoColor=white" />
  <img src="https://img.shields.io/badge/Mantine_Carousel-8.3.8-339AF0?style=for-the-badge&logo=react&logoColor=white" />
  <img src="https://img.shields.io/badge/Recharts-3.4.1-FF6384?style=for-the-badge&logo=chart.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Embla_Carousel-8.6.0-888888?style=for-the-badge&logo=react&logoColor=white" />
</p>

<p>
  <img src="https://img.shields.io/badge/Kakao_Maps_SDK-1.2.0-FFCD00?style=for-the-badge&logo=kakaotalk&logoColor=black" />
  <img src="https://img.shields.io/badge/Firebase-12.5.0-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" />
</p>

### Backend
<p>
  <img src="https://img.shields.io/badge/Spring_Boot-3.2.x-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Framework-6.2.12-6DB33F?style=for-the-badge&logo=spring&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-17+-007396?style=for-the-badge&logo=java&logoColor=white" />
  <img src="https://img.shields.io/badge/JPA%20/%20Hibernate-6DB33F?style=for-the-badge&logo=hibernate&logoColor=white" />
</p>

### Database
<p>
  <img src="https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white" />
</p>

### Security
<p>
  <img src="https://img.shields.io/badge/Spring_Security-6.5.6-6DB33F?style=for-the-badge&logo=spring-security&logoColor=white" />
  <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=json-web-tokens&logoColor=white" />
  <img src="https://img.shields.io/badge/OAuth2-FF7F00?style=for-the-badge&logo=openid&logoColor=white" />
</p>

### 외부 API
<p>
  <img src="https://img.shields.io/badge/KOPIS_API-0B5FFF?style=for-the-badge&logo=data&logoColor=white" />
  <img src="https://img.shields.io/badge/Kakao_Maps_API-FFCD00?style=for-the-badge&logo=kakaotalk&logoColor=black" />
  <img src="https://img.shields.io/badge/Google_OAuth-4285F4?style=for-the-badge&logo=google&logoColor=white" />
  <br/>
  + 기타 소셜 로그인 및 외부 연동 API
</p>

---

## 📂 프로젝트 폴더 구조

### Frontend

```bash
omijoy-frontend
├── .github/
├── .vscode/
├── node_modules/
├── public/
├── src/
│   ├── apis/          # Axios 인스턴스 및 API 래퍼 (performance, performanceplace, favorite 등)
│   ├── components/    # 공용 UI 컴포넌트
│   ├── configs/       # 환경 설정, 상수 등
│   ├── hooks/         # 커스텀 훅 (예: useDeferredFavorite 등)
│   ├── pages/
│   │   ├── AdminDashboard/   # 관리자 대시보드
│   │   ├── Auth/             # Login / SignUp / OAuth2Redirect
│   │   ├── Home/             # 홈 화면
│   │   ├── MyPage/           # 마이페이지 (즐겨찾기/플래그)
│   │   ├── Performance/      # 공연 목록/상세
│   │   └── PerformancePlace/ # 공연장 지도 페이지
│   ├── routes/       # MainRouter, PerformanceRouter 등 라우팅 설정
│   ├── stores/       # Zustand 전역 상태 (principal, favorite 등)
│   ├── types/        # TypeScript 타입 정의
│   └── utils/        # 공통 유틸 함수
├── .env / .env.product
├── index.html
├── nginx.conf
├── package.json / package-lock.json
├── tsconfig.json / tsconfig.node.json
├── vite.config.ts
└── 기타 설정 파일 (Dockerfile, cors.json, README.md 등)
```
### Backend
```bash
코드 복사
omijoy-backend/
└── src/
    └── main/
        ├── java/
        │   └── com/
        │       └── example/
        │           └── omijoy_backend/
        │               ├── controller/   # FlagController, KopisController 등 REST API 컨트롤러
        │               ├── dto/          # 요청/응답 DTO
        │               ├── entity/       # User, PrfList, PrfDetail, PrfPlcList, PrfPlcDetail, Favorite, Flag 등 엔티티
        │               ├── record/       # Kopis...Response, Kopis...Detail 등 KOPIS XML 매핑 레코드
        │               │   └── kopis/
        │               ├── repository/   # JpaRepository 인터페이스 모음
        │               ├── security/     # Spring Security, JWT 필터 및 설정
        │               │   └── filter/
        │               └── service/      # 비즈니스 로직 (PerformanceSyncService, Kopis 연동 서비스 등)
        │                   └── kopis/
        └── resources/
            ├── static/
            └── templates/
```
