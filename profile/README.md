✈️ YOURTRIP — AI 기반 여행 코스 플래너

**개발 기간**: 2025.09 ~ 2025.12 (2025-2 모바일 프로그래밍 팀 프로젝트)

🗺️ **너의 여행은 (YOURTRIP)**  
AI 추천과 코스 공유 기능으로 여행 계획의 번거로움을 줄여주는 **여행 코스 생성 & 공유 앱**

> 정보 과다, 일정 조율, 목적지 탐색 피로도를 한 번에 줄여주는  
> **“여행 코스 플래너 + 여행 코스 SNS + AI 추천”** 서비스

 - 수정해야됨
<p align="center">
  <img src="이미지_URL_여기에" alt="YOURTRIP 메인 화면" width="900"/>
</p>

---

## 📦 레포지토리

- 🎨 **Android App (FE)**: https://github.com/Kookmin-MoP-Yourtrip/YOURTRIP_FE  
- 🛠 **Spring Boot (BE)**: https://github.com/Kookmin-MoP-Yourtrip/YOURTRIP_BE  

---

## 👥 팀 소개

| 이름      | 역할              | GitHub                                           | 주요 담당 |
|--------  |--------------      |--------------------------------------------------|----------|
| 김태환   | Leader / BE / FE   | [@KimTaeHwan21](https://github.com/KimTaeHwan21) | 서버 구축 및 에러 수정, 기본 회원가입/로그인/비밀번호 변경 , 마이페이지, 인증/인가, 프론트 마이페이지 UI / 프로필 편집 |
| 남지은   | BE /FE             | [@zie-ning](https://github.com/zie-ning)         | 여행 코스 생성 및 일차별 일정 관리(BE), 코스 업로드 및 fork 로직(BE), AI 코스 생성 플로우 UI(FE) |
| 최서구   | BE / FE            | [@choiseogu](https://github.com/choiseogu)       | 여행 피드 CRUD API 개발(BE), 피드에 대한 댓글 CRUD API 개발(BE), 나의 업로드 코스 및 피드 조회 플로우 기능 개발(FE) |
| 이다은   | FE                 | [@dani0910](https://github.com/dani0910)                                                | ?? |
| 조혜원   | FE                 | [@agunggung22](https://github.com/agunggung22)   |UI/UX 설계, **홈/피드** 전체 화면 개발, 공통 View 컴포넌트 개발 및 프론트 구조 설계 |

---
 
## ✨ 프로젝트 소개

YOURTRIP은 사용자가 여행을 계획할 때 겪는

- 📚 **정보 과다**: 블로그, 인스타, 유튜브 등 흩어진 정보
- 🧩 **일정 조율의 어려움**: 친구와 날짜·코스를 맞추기 힘든 문제
- 🔍 **목적지 탐색 피로도**: 어디를 가야 할지 고르기만 하다 시간 보내는 문제

를 해결하기 위해 만들어진 **AI 기반 여행 코스 플래너**입니다.

- AI가 조건에 맞는 **추천 코스**를 생성해주고
- 사용자는 직접 **여행 코스를 만들고 관리**할 수 있으며
- 다른 사람이 만든 코스를 **공유 / 검색 / fork**해서
- 나만의 여행 계획으로 **커스터마이징**할 수 있습니다.
---

## 📌 주요 기능

### 1️⃣ 코스 탐색 & 검색

- 지역, 테마, 기간 등으로 분류된 **여행 코스 리스트**
- 해시태그 / 필터 기반으로 **내 취향에 맞는 코스** 빠르게 찾기
- 인기순 / 최신순 정렬 기능

### 2️⃣ 나의 여행 코스 관리

- 여행 일자/도시/동선 기반으로 **코스 생성 & 편집**
- 하루 단위 Day 별 일정 구성

### 3️⃣ AI 기반 코스 추천

- 여행 기간, 동행 인원, 선호 스타일 등 간단 정보만 입력하면  
  → 조건에 맞는 **AI 추천 코스** 자동 생성  
- 추천된 코스를 기반으로 세부 일정만 수정해서 사용

### 4️⃣ 코스 공유 & Fork

- 마음에 드는 코스를 **fork**해서 내 일정에 맞게 수정
- 여행이 끝난 후, 실제 다녀온 코스를 기반으로 **후기/수정** 가능

### 5️⃣ 피드(Feed) 업로드 & 소셜 기능

- 여행 사진, 위치, 설명을 담은 피드 게시
- 다른 사용자의 피드 보기
- 좋아요 및 댓글 작성 

### 6️⃣ 마이페이지 & 계정 관리

- 프로필 이미지/닉네임/비밀번호 변경
- 내가 만든 코스 / fork한 코스 / 저장한 코스 모아보기
- 회원 탈퇴, 로그아웃 등 계정 관련 기능

---

## 🌟 서비스 포인트

1️⃣ **“검색 지옥”에서 벗어나기**  
- 블로그, 카페, 유튜브를 끝없이 뒤지는 대신  
  → AI가 조건에 맞는 코스를 먼저 제안  
  → 마음에 들면 그대로 사용, 아니면 fork해서 내 스타일로 수정

2️⃣ **여행 코스를 “콘텐츠”로 공유**  
- 코스를 단순 일정이 아닌 **콘텐츠처럼 공유**  
- 잘 만든 코스를 다른 사람이 복사해서 쓰는 구조로  
  → 여행 계획이 쌓일수록 플랫폼 가치 상승

3️⃣ **모바일 환경 최적화**  
- 실제 여행 계획/조율이 가장 많이 일어나는 환경인 **모바일(Android)** 기준으로 UX 설계

---

## 🖥️ 화면 구성(수정해야됨)

| 스플래시 & 로그인 | 코스 탐색 (홈) | 코스 상세 |
|:---------------:|:---------:|:---------:|
| <img src="이미지_URL_로그인" width="240"/> | <img src="이미지_URL_코스탐색" width="240"/> | <img src="이미지_URL_코스상세" width="240"/> |

| 나의 코스  | 코스 편집 | 마이페이지 |
|:---------:|:---------:|:----------:|
| <img src="이미지_URL_나의코스" width="240"/> | <img src="이미지_URL_코스편집" width="240"/> | <img src="이미지_URL_마이페이지" width="240"/> |

---

## 🛠 기술 스택

### 📱 Frontend (Android)

- **Language**: Java, XML
- **Framework**: Android SDK
- **UI 구성**: XML 기반 레이아웃 설계, Fragment 기반 화면 전환 구조, RecyclerView, ViewPager2, FlexboxLayout, ConstraintLayout, LinearLayout 등을 활용한 반응형 UI 구성
- **네비게이션**: BottomNavigationView, FragmentManager를 활용한 화면 전환
- **이미지 처리**: Glide 기반 이미지 로딩 및 캐싱
- **네트워크**: Retrofit2 + OkHttp3, Interceptor를 통한 JWT 인증 헤더 자동 주입
- **상태관리**: SharedPreferences 기반 사용자 세션 관리
- **아키텍처**: Adapter 패턴, Listener 인터페이스 기반 이벤트 처리
- **디자인 시스템**: 공통 UI 컴포넌트(TagBasicView, TripCard, 버튼/태그 스타일 등) 재사용 구조
- **기타**: S3 이미지 업로드 연동, Swagger 기반 API 스펙 맞춤 데이터 처리

### 🔧 Backend (Spring Boot)

- **Language**: Java
- **Framework**: Spring Boot, Spring MVC
- **Security**: Spring Security, JWT 기반 인증/인가
- **DB**: PostgreSQL, Spring Data JPA
- **Infra**: AWS EC2, RDS, S3
- **기타**: Nginx, Docker, Gradle

---

## 📂 프로젝트 구조

### 📱 FE – Android

```bash
YOURTRIP_FE/
├── manifests/
│   └── AndroidManifest.xml                # 앱 권한, 액티비티, Application 등록
├── java/
│   └── com.example.yourtrip/
│       ├── auth/                          # 로그인/회원가입, 토큰 처리
│       ├── commonUtil/                    # 공통 유틸, 커스텀 뷰(TagBasicView 등)
│       ├── feed/                          # 피드(조회/상세/댓글/업로드) 전반 UI + 로직
│       ├── home/                          # 홈 화면(인기코스, 지역별, 검색)
│       ├── model/                         # 서버와 주고받는 데이터 모델(Response, DTO)
│       ├── mypage/                        # 마이페이지(프로필/계정 설정)
│       ├── mytrip/                        # 나의 코스(리스트/상세)
│       ├── network/                       # Retrofit, OkHttp, Interceptor
│       │
│       ├── LauncherActivity.java          # 앱 실행 시 최초 진입 화면
│       ├── MainActivity.java              # BottomNav + 전체 Fragment 관리
│       └── YourTripApplication.java       # 전역 Context, 초기 설정 클래스
├── res/
│   ├── anim/                              # 화면 전환 애니메이션
│   ├── color/                             # 색상 정의
│   ├── drawable/                          # 아이콘, 배경(shape)
│   ├── layout/                            # XML 기반 UI 레이아웃 파일들
│   ├── menu/                              # 메뉴 리소스(BottomNav 등)
│   ├── mipmap/                            # 앱 아이콘
│   └── values/
│       ├── colors.xml                     # 색상값
│       ├── strings.xml                    # 문자열 리소스
│       ├── styles.xml                     # 공통 스타일, 테마
│       └── themes/                        # Material Theme 설정
└── build.gradle                           # 라이브러리 및 Gradle 설정

```

### 🛠 BE – Spring Boot

```bash
YOURTRIP_BE/
├── src/main/java/yourtrip
│   ├── domain/                       # 주요 도메인 계층
│   │    ├── feed/                    # 피드 및 코스 공유 관련 도메인
│   │    ├── mycourse/                # 내가 만든 코스 관리 도메인
│   │    ├── mypage/                  # 마이페이지 (프로필, 계정 설정)
│   │    ├── uploadcourse/            # 업로드된 코스 정보 저장 및 관리
│   │    ├── user/                    # 회원 도메인
│   │
│   ├── global/                       # 공통 컴포넌트 모음
│   │    ├── common/                  # 공통 응답, 유틸
│   │    ├── config/                  # CORS, Swagger, Security 등 설정 파일
│   │    ├── converter/               # Enum/String 변환기
│   │    ├── exception/               # 전역 예외 처리 및 핸들러
│   │    ├── gemini/                  # Gemini API 연동 서비스
│   │    ├── jwt/                     # JWT 발급 및 인증 필터
│   │    ├── kakao/                   # Kakao OAuth 인증 로직
│   │    ├── mail/                    # 이메일 인증(메일 발송)
│   │    ├── s3/                      # AWS S3 파일 업로드 및 다운로드 모듈
│   │    ├── security/                # Security Config
└── build.gradle
```
### ⚙️ BE - application.yml
```yml
spring:
  datasource:
    url: ${DB_URL}
    username: ${DB_USERNAME}
    password: ${DB_PASSWORD}
    driver-class-name: org.postgresql.Driver

  jpa:
    hibernate:
      ddl-auto: ${DB_DDL_AUTO}
    properties:
      hibernate:
        format_sql: true
        dialect: org.hibernate.dialect.PostgreSQLDialect
    show-sql: true

  mail:
    host: smtp.gmail.com
    port: 587
    username: ${MAIL_EMAIL}
    password: ${MAIL_PASSWORD}
    properties:
      mail:
        smtp:
          auth: true
          starttls:
            enable: true

  servlet:
    multipart:
      max-file-size: 10MB
      max-request-size: 10MB

jwt:
  secret: ${JWT_SECRET}

logging:
  level:
    org.hibernate.SQL: debug
    org.springdoc: debug
    org.springframework.web: info
    org.springframework.security: DEBUG

springdoc:
  api-docs:
    enabled: true
  swagger-ui:
    enabled: true
    path: /swagger-ui.html
    operationsSorter: method
    displayRequestDuration: true
    persistAuthorization: true
  override-with-generic-response: false

kakao:
  auth:
    client-id: ${KAKAO_CLIENT_ID}
    client-secret: ${KAKAO_CLIENT_SECRET}
    redirect-uri: http://localhost:8080/api/users/login/kakao/callback
  api-key: ${KAKAO_API_KEY}
  local:
    base-url: "https://dapi.kakao.com"

server:
  forward-headers-strategy: framework
  port: 8080
  address: 0.0.0.0
  ssl:
    enabled: false
    # key-store: ${KEY_STORE}
    # key-store-type: ${KEY_TYPE}
    # key-store-password: ${KEY_PASS}

s3:
  bucket: ${S3_BUCKET}
  region: ap-northeast-2
  allowed-content-types: image/png,image/jpeg,image/webp,image/jpg,video/mp4,video/quicktime,video/webm
  max-size-bytes: 10485760 # 10MB

  access-key: ${AWS_ACCESS_KEY}
  secret-key: ${AWS_SECRET_KEY}

gemini:
  api-key: ${GEMINI_API_KEY}
```

## 🚀 실행 방법

### 📱 FE – Android Studio

```bash
git clone https://github.com/Kookmin-MoP-Yourtrip/YOURTRIP_FE.git
cd YOURTRIP_FE
```
- 추가부탁
- SDK 버전 추가해야함

### 🛠 BE – Spring Boot

```bash
git clone https://github.com/Kookmin-MoP-Yourtrip/YOURTRIP_BE.git
cd YOURTRIP_BE
```
- 환경 변수 설정 후 실행
  ```bash
  ./gradlew bootRun
  ```

## 📎 기타 자료

#### 🎥 시연 영상: 업데이트 예정

#### 📑 발표 자료(PPT): 업데이트 예정

#### 🎥 노션 링크: (https://aquamarine-book-1e6.notion.site/2025-2-_-2-_1-26b77c61398180168bcfd3eee08b8e0c?source=copy_link)

#### 🎥 피그마 링크: (https://www.figma.com/design/YcCdV6Eqf486kKcZOK6mUm)

#### 🎥 피그잼 링크: (https://www.figma.com/board/TjRf47J8qvnVRsg2dXcSy9/)

#### 🎥 Swagger 링크: (https://yourtrip.site/swagger-ui/index.html)

#### 🎥 ERD 링크: (https://www.erdcloud.com/d/FvCG4hazXKR4vL8aq)
