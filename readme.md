# 🥩 아웃백 스테이크하우스 웹사이트

한국 아웃백 스테이크하우스 공식 웹사이트의 클론 프로젝트입니다. 반응형 디자인과 동적 메뉴 시스템을 구현하여 실제 웹사이트와 유사한 사용자 경험을 제공합니다.

## 🌐 라이브 데모

<div align="center">

### 🚀 **[배포된 웹사이트 보기](https://steakhouse-website-eight.vercel.app/)**

[![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://steakhouse-website-eight.vercel.app/)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white)](https://steakhouse-website-eight.vercel.app/)

**✨ 별도 설치 없이 바로 체험 가능! ✨**

</div>

## 🎯 프로젝트 개요

이 프로젝트는 아웃백 스테이크하우스의 공식 웹사이트를 모티브로 한 정적 웹사이트입니다. 실제 메뉴 데이터와 브랜드 정보를 활용하여 완전한 웹사이트 경험을 제공합니다.

### 📈 주요 특징

- **반응형 웹 디자인**: 데스크톱, 태블릿, 모바일 최적화
- **동적 메뉴 시스템**: JSON 데이터 기반 실시간 메뉴 렌더링
- **인터랙티브 UI**: 슬라이더, 모달, 호버 효과
- **실제 데이터**: 진짜 메뉴와 가격 정보 활용

## ⚡ 주요 기능

### 🏠 홈페이지
- **자동 이미지 슬라이더**: 4개의 프로모션 배너 자동 전환
- **메뉴 프리뷰 슬라이더**: 인기 메뉴 소개
- **네비게이션 시스템**: 직관적인 메뉴 구조

### 🍽️ 메뉴 시스템
- **동적 카테고리**: 10개 카테고리별 메뉴 분류
- **실시간 가격**: JSON 기반 메뉴 데이터
- **검색 및 필터**: URL 파라미터 기반 직접 접근
- **반응형 레이아웃**: 디바이스별 최적화된 메뉴 표시

### 🎨 브랜드 페이지
- **스토리텔링**: OUTBACK STORY, BEEF STORY, STEAK ACADEMY
- **멀티미디어**: 이미지 갤러리 및 YouTube 동영상 임베드
- **동적 콘텐츠**: JSON 기반 콘텐츠 관리

### 💳 혜택 페이지
- **카드사별 할인**: 삼성, 신한, BC 카드 혜택 정보
- **탭 시스템**: 카드사별 정보 동적 전환
- **외부 링크**: 카드사 공식 사이트 연동

### 🎧 고객 서비스
- **문의 시스템**: 회원/비회원 문의 폼
- **동적 폼**: JavaScript 기반 폼 생성
- **카테고리별 문의**: 11개 문의 유형 지원

## 🛠️ 기술 스택

### Frontend
- **HTML5**: 시맨틱 마크업
- **CSS3**: Flexbox, Grid, 애니메이션
- **JavaScript (ES6+)**: 모던 JavaScript
- **jQuery 3.7.1**: DOM 조작 및 AJAX

### 배포 & 호스팅
- **Vercel**: 정적 사이트 배포
- **GitHub**: 소스 코드 관리
- **HTTPS**: 보안 연결
- **글로벌 CDN**: 빠른 콘텐츠 전송

### 디자인 & UI/UX
- **반응형 웹 디자인**: Mobile-First 접근법
- **CSS 미디어 쿼리**: 3단계 브레이크포인트 (480px, 768px, 1024px)
- **그라데이션 & 그림자**: 모던 UI 디자인
- **호버 효과**: 인터랙티브 요소

### 데이터 관리
- **JSON**: 구조화된 데이터 저장
- **AJAX**: 비동기 데이터 로딩
- **동적 렌더링**: JavaScript 기반 DOM 생성

## 📁 프로젝트 구조

```
steakhouse-website/
│
├── 📄 index.html                 # 메인 홈페이지
├── 📝 readme.md                  # 프로젝트 문서
│
├── 🎨 css/                       # 스타일시트
│   ├── styles.css               # 전역 스타일 & 헤더/푸터
│   ├── index.css                # 홈페이지 전용
│   ├── menu.css                 # 메뉴 페이지 전용
│   ├── brand.css                # 브랜드 페이지 전용
│   ├── benefit.css              # 혜택 페이지 전용
│   ├── customer-service.css     # 고객서비스 페이지 전용
│   ├── login.css                # 로그인 모달 전용
│   ├── register.css             # 회원가입 모달 전용
│   ├── sitemap.css              # 사이트맵 페이지 전용
│   └── etc.css                  # 기타 페이지 전용
│
├── 🖼️ images/                    # 이미지 리소스
│   ├── banners/                 # 배너 이미지
│   │   ├── brand10.png
│   │   ├── brand11.png
│   │   └── brand2.png
│   └── icones/                  # 아이콘 이미지
│       ├── brandCompany.png
│       ├── delivery.png
│       ├── reserve.png
│       └── savepoint.png
│
├── ⚙️ js/                        # JavaScript 파일
│   ├── index.js                 # 홈페이지 슬라이더 & 인터랙션
│   ├── menu.js                  # 메뉴 페이지 네비게이션
│   ├── brand.js                 # 브랜드 페이지 동적 콘텐츠
│   ├── benefit.js               # 혜택 페이지 카드 시스템
│   ├── customer-service.js      # 고객서비스 문의 폼
│   ├── login.js                 # 로그인 모달
│   ├── register.js              # 회원가입 모달
│   └── sitemap.js               # 사이트맵 네비게이션
│
├── 📊 json/                      # 데이터 파일
│   ├── brand.json               # 브랜드 이미지/동영상 데이터
│   └── index.json               # 홈페이지 슬라이더 데이터
│
└── 📃 pages/                     # 서브 페이지
    ├── menu.html                # 정적 메뉴 페이지
    ├── menus.html               # 동적 메뉴 페이지
    ├── brand.html               # 브랜드 스토리
    ├── benefit.html             # 카드 혜택 정보
    ├── customer-service.html    # 고객 서비스
    ├── login.html               # 로그인 모달
    ├── register.html            # 회원가입 모달
    ├── sitemap.html             # 사이트맵
    ├── etc.html                 # 정책 페이지
    ├── steak.json               # 전체 메뉴 데이터 (1,700줄)
    └── js/
        └── menus.js             # 동적 메뉴 시스템 (핵심 기능)
```

## 🚀 실행 방법

### 🌐 온라인에서 바로 체험
**가장 쉬운 방법!** 별도 설치 없이 바로 사용 가능합니다.

👉 **[https://steakhouse-website-eight.vercel.app/](https://steakhouse-website-eight.vercel.app/)**

### 💻 로컬 환경에서 실행

#### 요구 사항
- 웹 브라우저 (Chrome, Firefox, Safari, Edge)
- 로컬 웹 서버 (개발 환경용)

#### 설치 및 실행 방법

1. **저장소 클론**
```bash
git clone https://github.com/your-username/steakhouse-website.git
cd steakhouse-website
```

2. **로컬 서버 실행**
**VS Code Live Server 사용:**
- VS Code에서 프로젝트 열기
- Live Server 확장 프로그램 설치
- `index.html` 우클릭 → "Open with Live Server"

3. **브라우저에서 접속**
```
http://localhost:5500
```

### 📱 모바일에서 테스트
라이브 데모는 모든 디바이스에서 접근 가능하며, 반응형 디자인을 완벽하게 체험할 수 있습니다.

## 📱 페이지별 기능

### 🏠 index.html - 홈페이지
**주요 기능:**
- 4개 프로모션 배너 자동 슬라이더 (13초 간격)
- 메뉴 프리뷰 섹션 (좌우 이미지 + 중앙 텍스트)
- 베네핏 섹션
- 부메랑 멤버십 홍보

**기술적 특징:**
- jQuery 기반 슬라이더
- JSON 데이터 기반 동적 콘텐츠
- 반응형 이미지 레이아웃

### 🍽️ pages/menu.html & menus.html - 메뉴 시스템

**정적 메뉴 (menu.html):**
- BLACK LABEL CHEF EDITION 고정 페이지
- 세트 메뉴 정보 (커플세트: 137,000원, 패밀리세트: 189,000원)

**동적 메뉴 (menus.html + menus.js):**
- 10개 카테고리 동적 렌더링
- URL 파라미터 기반 직접 접근
- 카테고리별 맞춤 레이아웃
- 가격 포맷팅 시스템

**메뉴 카테고리:**
1. BEVERAGES & ALCOHOL
2. APPETIZERS & SALADS  
3. BLACK LABEL CHEF EDITION
4. SPECIAL STEAKS & BACK RIBS
5. SIDES & ADD ON MATES
6. PASTA & RICE
7. DESSERTS
8. WINES
9. LUNCH SET
10. DELIVERY

### 🎨 pages/brand.html - 브랜드 스토리
**콘텐츠 섹션:**
- **OUTBACK STORY**: 브랜드 역사
- **BEEF STORY**: 소고기 이야기  
- **STEAK ACADEMY**: 스테이크 아카데미 (YouTube 동영상 포함)

**기술적 특징:**
- JSON 기반 동적 이미지 로딩
- YouTube iframe 임베드
- 서브메뉴 기반 콘텐츠 전환

### 💳 pages/benefit.html - 카드 혜택
**카드사별 혜택:**
- **삼성카드**: 아메리칸 익스프레스 리저브/그린 카드
- **신한카드**: 다양한 제휴 카드
- **BC카드**: BC 제휴 혜택
- **기타카드**: 추가 제휴 혜택
- **매장별카드**: 지역별 특별 혜택

**기능:**
- 탭 시스템으로 카드사별 정보 전환
- 외부 카드사 링크 연동
- 할인 서비스 안내

### 🎧 pages/customer-service.html - 고객 서비스
**문의 시스템:**
- 회원 로그인 문의
- 비회원 문의 (동적 폼 생성)
- 11개 문의 유형 지원

**문의 유형:**
- 매장 서비스, 딜리버리 서비스, 부메랑 클럽
- 홈페이지 및 APP, 이벤트, 제휴 서비스
- 지류상품권, 기프트카드/모바일상품권
- 아카데미, 채용문의, 기타

### 🔐 로그인 & 회원가입 시스템
**로그인 (pages/login.html):**
- 통합 회원 로그인 모달
- 아이디 저장 기능
- 아이디/비밀번호 찾기 링크

**회원가입 (pages/register.html):**
- 통합 회원 가입 안내
- 본인 인증 시스템 연동

### 🗺️ pages/sitemap.html - 사이트맵
**전체 사이트 구조:**
- 계층적 메뉴 구조 표시
- 클릭 가능한 네비게이션 링크
- 각 섹션별 서브메뉴 표시

## 📱 반응형 디자인

### 브레이크포인트
- **데스크톱**: 1024px 이상
- **태블릿**: 768px ~ 1024px  
- **모바일**: 480px ~ 768px
- **소형 모바일**: 480px 이하

### 주요 반응형 기능

**네비게이션:**
- 데스크톱: 수평 메뉴바
- 모바일: 카드형 드롭다운 메뉴

**이미지 슬라이더:**
- 데스크톱: 좌우 버튼 제어
- 모바일: 터치 스와이프 (자동 재생만)

**메뉴 레이아웃:**
- 데스크톱: 3단 그리드
- 태블릿: 2단 그리드  
- 모바일: 1단 세로 배치

**카드 시스템:**
- 데스크톱: 가로 배치
- 모바일: 세로 스택 배치

## 📊 데이터 구조

### steak.json (1,700줄)
```json
{
  "BEVERAGES & ALCOHOL": {
    "BEVERAGES & ALCOHOL": [...],
    "DRAFT BEERS": [...],
    "HIGHBALL": [...]
  },
  "APPETIZERS & SALADS": [...],
  "BLACK LABEL CHEF EDITION": [...],
  "WINES": {
    "HOUSE WINE": [...],
    "RED WINES": [...],
    "WHITE WINES": [...],
    "CHAMPAGNE": [...]
  }
}
```

### brand.json
```json
{
  "OUTBACK STORY": [
    {"url": "../images/banners/brand10.png"},
    {"url": "../images/banners/brand11.png"}
  ],
  "STEAK ACADEMY": [
    {"url": "..."},
    {"youtube": "https://www.youtube.com/embed/..."}
  ]
}
```

### index.json (홈페이지 슬라이더)
```json
[
  {
    "id": 1,
    "texts": {
      "large": "GARIC\nRIBEYE",
      "medium": "갈릭 립아이",
      "small": "구운 마늘과 마늘칩이 어우러진..."
    },
    "image": "https://www.outback.co.kr/upload/banner/..."
  }
]
```

## 🔧 핵심 기술 구현

### 동적 메뉴 시스템 (menus.js)
```javascript
// JSON 기반 동적 메뉴 생성
$.getJSON("steak.json", function (menuData) {
  const categories = Object.keys(menuData);
  
  // 카테고리별 버튼 동적 생성
  const menuButtons = categories.map((category) => {
    return $("<button></button>")
      .text(category)
      .on("click", function () {
        displayMenu(menuData, category);
      });
  });
});
```

### 슬라이더 시스템 (index.js)
```javascript
// 자동 슬라이더 (13초 간격)
function resetFirstAutoSlide() {
  clearTimeout(firstAutoSlideTimeout);
  firstAutoSlideTimeout = setTimeout(() => {
    현재페이지 = (현재페이지 + 1) % 이미지총갯수;
    moveSlide(현재페이지);
    resetFirstAutoSlide();
  }, 13000);
}
```

### 반응형 네비게이션
```css
@media (max-width: 768px) {
  .midBar {
    flex-direction: column;
    border-radius: 12px;
    box-shadow: 0 4px 16px rgba(0, 0, 0, 0.08);
  }
  
  .midBar > .submenu {
    width: 280px;
    text-align: center;
    background-image: url("data:image/svg+xml...");
  }
}
```

## 🌟 주요 기능 하이라이트

### 1. 스마트 가격 포맷팅
- 3자리 수 콤마 자동 삽입
- 세트 메뉴 가격 분할 표시
- 와인 글라스/보틀 가격 구분

### 2. URL 기반 직접 접근
```javascript
// URL 파라미터로 메뉴 직접 접근
const urlParams = new URLSearchParams(window.location.search);
const submenuParam = urlParams.get("submenu");
if (submenuParam && categories.includes(submenuParam)) {
  displayMenu(menuData, submenuParam);
}
```

### 3. 모달 시스템
- 팝업 창 형태의 로그인/회원가입
- 중앙 정렬 및 반응형 크기 조절
- ESC 키 및 배경 클릭으로 닫기

### 4. 외부 서비스 연동
- 네이버 지도 (매장 찾기)
- YouTube 동영상 임베드
- 카드사 공식 사이트 링크

## 🔍 브라우저 호환성

### 지원 브라우저
- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+

### 주요 기능 호환성
- ✅ CSS Grid & Flexbox
- ✅ ES6+ JavaScript
- ✅ jQuery 3.7.1
- ✅ CSS 미디어 쿼리
- ✅ JSON 파싱

## 📄 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다. 자세한 내용은 `LICENSE` 파일을 참조하세요.

---

## 🏆 프로젝트 성과

### 🌐 배포 현황
- ✅ **Vercel 배포 완료**: [steakhouse-website-eight.vercel.app](https://steakhouse-website-eight.vercel.app/)
- ✅ **HTTPS 보안 연결** 
- ✅ **글로벌 CDN** 적용
- ✅ **모바일 최적화** 완료

## 📱 모바일에서 체험하기

모바일 기기에서 다음 URL을 입력하여 반응형 디자인을 직접 체험해보세요:

**🔗 https://steakhouse-website-eight.vercel.app/**

> 💡 **팁**: 크롬 개발자 도구에서 다양한 디바이스 크기로 테스트할 수 있습니다!
