# 🚀 WriteFlow - AI Writing Assistant 2.0 SaaS Landing Page

**WriteFlow**는 사용자가 아이디어를 단 몇 초 만에 완성된 콘텐츠로 변환할 수 있도록 돕는 지능형 **AI 글쓰기 어시스턴트(AI Writing Assistant 2.0)** 서비스의 현대적이고 세련된 SaaS 랜딩 페이지 프로젝트입니다. 

Next.js (App Router), React 19, 그리고 최신 Tailwind CSS v4를 활용하여 뛰어난 성능, 유려한 애니메이션, 그리고 완벽한 반응형 레이아웃을 구현했습니다.

---

## 🎨 주요 특징 (Key Features)

* **✨ AI 글쓰기 어시스턴트**: 원클릭 초안 작성 및 콘텐츠 확장 기능.
* **✍️ 완벽한 문법 검사**: 실시간 문장 매끄럽게 다듬기 및 교정 기능.
* **🎯 브랜드 맞춤형**: 사용자 고유의 브랜드 목소리와 톤앤매너에 맞게 개인화.
* **🌐 다국어 지원**: 30개 이상의 국가 언어를 자연스럽게 지원 및 번역.
* **📁 템플릿 라이브러리**: 100개 이상의 기제작된 전문 템플릿 제공.
* **👥 실시간 협업**: 팀원들과 동시 편집 및 피드백 공유 기능.
* **💳 요금제 토글 (Pricing Toggle)**: 월간/연간(20% 할인) 구독 요금제를 반응형 UI로 시각화.

---

## 🛠 기술 스택 (Tech Stack)

| 기술 분류 | 사용된 기술 / 라이브러리 | 버전 | 설명 |
| :--- | :--- | :--- | :--- |
| **Core** | **Next.js** (App Router) | `16.2.6` | 현대적인 웹 애플리케이션 프레임워크 |
| **Library** | **React** | `19.2.4` | 컴포넌트 기반 사용자 인터페이스 라이브러리 |
| **Styling** | **Tailwind CSS** | `v4.0` | 유틸리티 퍼스트 CSS 프레임워크 (v4 성능 및 포스트CSS 최적화 적용) |
| **Icons** | **Lucide React** | `^1.14.0` | 깔끔하고 정교한 벡터 아이콘 라이브러리 |
| **Language**| **TypeScript** | `^5.0` | 안전한 타입 검사를 위한 JavaScript 상위 집합 |
| **Linting** | **ESLint** | `^9.0` | 코드 스타일 분석 및 품질 유지 도구 |

---

## 📂 프로젝트 구조 (Project Structure)

```markdown
saas-landing-page/
├── 📁 app/                    # Next.js App Router 디렉토리
│   ├── 📁 components/         # 프리미엄 섹션별 컴포넌트 목록
│   │   ├── CTA.tsx            # 마지막 행동 유도(Call To Action) 섹션
│   │   ├── FAQ.tsx            # 아코디언 방식의 자주 묻는 질문 섹션
│   │   ├── Features.tsx       # 6가지 핵심 기능 그리드 카드 섹션
│   │   ├── Footer.tsx         # 하단 법적 고지 및 소셜 링크 네비게이션
│   │   ├── Hero.tsx           # 그라디언트 배경과 메인 타이틀 및 데모 보기 섹션
│   │   ├── Navbar.tsx         # 상단 헤더 로고 및 퀵 네비게이션 바
│   │   └── Pricing.tsx        # 연간/월간 상태 관리 기반 요금제 테이블 섹션
│   ├── globals.css            # 글로벌 Tailwind CSS v4 스타일링 설정
│   ├── layout.tsx             # 루트 레이아웃 (Geist 폰트 자동 최적화 설정)
│   └── page.tsx               # 모든 메인 컴포넌트들이 조립되는 홈 페이지
├── 📁 design/                 # 디자인 프리뷰 이미지 폴더
│   └── screen.png             # 랜딩 페이지 대표 스크린샷 이미지
├── 📁 public/                 # 이미지, 파비콘 등 정적 자원 디렉토리
├── postcss.config.mjs         # PostCSS 설정 파일 (Tailwind v4 연동)
├── tailwind.config.js         # Tailwind 구성 파일 (v4 사양에 맞춘 모듈)
├── tsconfig.json              # TypeScript 컴파일러 구성 파일
└── package.json               # 의존성 패키지 및 개발 스크립트 정의
```

---

## 💻 시작 가이드 (Getting Started)

로컬 개발 환경에서 프로젝트를 실행하려면 아래 단계를 따르세요.

### 1. 패키지 설치
먼저 프로젝트 루트 디렉토리에서 필요한 의존성 패키지를 설치합니다.
```bash
npm install
```

### 2. 개발 서버 실행
설치가 완료되면 개발 모드로 서버를 켭니다.
```bash
npm run dev
```

### 3. 브라우저 확인
개발 서버가 시작되면 브라우저에서 아래 링크를 열어 결과를 확인하세요.
* Local URL: [http://localhost:3000](http://localhost:3000)

---

## 🏗 주요 컴포넌트 디자인 특징

### 1. Hero.tsx (히어로 섹션)
* 상단 보라색 계열(`#E6E6FF` ➡️ `#F3E8FF` ➡️ `#FFFFFF`)의 미려한 배경 그라디언트 레이아웃.
* `AI Writing Assistant 2.0` 안내를 위한 유선형 배지 컴포넌트 적용.
* 한글 타이포그래피 강조 효과 및 무료 체험 시작과 데모 시청 버튼 배치.

### 2. Features.tsx (기능 카드 섹션)
* 회색 톤(`#FAFAFA`)의 부드러운 배경 디자인.
* Lucide React 아이콘들을 연보라색 사각 라운드 박스 처리하여 세련된 분위기 연출.
* Hover 마우스 오버 시 미세하게 섀도우가 상승(`hover:shadow-md transition-shadow`)하는 인터랙티브 디자인 적용.

### 3. Pricing.tsx (구독 요금제 섹션)
* React `useState`를 통해 구현한 실시간 **월간 vs 연간** 연동 슬라이더 UI (연간 선택 시 20% 자동 할인 가격 노출).
* Free, Pro, Enterprise 세 단계의 명확한 요금 체계 설계.
* 사용자의 시선을 집중시키기 위해 Pro 요금제 카드를 세로로 길게 강조(`transform md:-translate-y-4`)하고 배지를 추가한 특수 레이아웃.

### 4. FAQ.tsx (아코디언 섹션)
* 질문 클릭 시 상태 값 변동에 따라 설명란이 자연스럽게 여닫히는 Accordion 동작 구현.
* Plus, Minus 아이콘이 토글 상태에 맞춰 스마트하게 전환됨.

---

## 📄 라이선스 (License)

본 프로젝트는 개인 포트폴리오 및 SaaS 서비스 개발 목적의 프로젝트입니다.

---
💡 **참고**: 이 프로젝트는 `Next.js 16` 및 `Tailwind CSS 4.0` 환경에서 빌드되었습니다. 최신 버전에 따른 종속성 관리를 위해 수정 시 `package.json` 파일의 플러그인 사양을 반드시 준수해 주세요.
