# 🛍️ NOVER - Style Commerce Web

온라인 패션 스토어 '무신사(Musinsa)'를 모델로 제작한 이커머스 웹사이트입니다. 반응형 디자인과 동적 데이터 렌더링을 통해 사용자 중심의 쇼핑 경험을 제공합니다.

## 라이브 데모

<div align="center">

### **[배포된 웹사이트 보기](https://nover-feedback.vercel.app/)**

[![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://nover-feedback.vercel.app/)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white)](https://nover-feedback.vercel.app/)

**별도 설치 없이 바로 체험 가능**

</div>

## 프로젝트 개요

이 프로젝트는 패션 커머스 플랫폼의 핵심 기능을 클론 코딩 방식으로 구현한 프론트엔드 포트폴리오입니다. 상품 관리, 동적 필터링, 사용자 인증, 검색 등 실제 이커머스 환경에 필요한 기능들을 중심으로 개발되었습니다.

### 주요 특징

  - **동적 상품 시스템**: JSON 데이터를 기반으로 상품 목록과 상세 정보를 동적으로 렌더링합니다.
  - **실시간 검색 및 필터링**: 사용자가 입력하는 키워드에 따라 실시간으로 상품을 검색하고, 카테고리 및 정렬 기준에 따라 필터링합니다.
  - **사용자 인증**: `localStorage`와 `sessionStorage`를 활용한 회원가입 및 로그인/로그아웃 시스템을 구현했습니다.
  - **컴포넌트 기반 구조**: `header`, `footer` 등 공통 UI를 분리하여 JavaScript로 동적으로 삽입해 재사용성과 유지보수성을 높였습니다.
  - **반응형 디자인**: 모바일, 태블릿, 데스크톱 등 모든 디바이스에서 최적화된 화면을 제공합니다.

## 기술 스택

### Frontend

  - **HTML5**: 시맨틱 마크업을 활용하여 웹 접근성을 준수합니다.
  - **CSS3**: Flexbox, Grid 레이아웃 및 미디어 쿼리를 사용한 반응형 디자인을 구현합니다.
  - **JavaScript (ES6+)**: DOM 조작, 이벤트 처리 및 비동기 데이터 통신을 담당합니다.
  - **jQuery 3.7.1**: AJAX 통신 및 DOM 조작을 간소화하기 위해 사용되었습니다.

### 데이터 & 스토리지

  - **JSON**: 상품, 배너, 콘텐츠 등 정적 데이터를 구조화하여 관리합니다.
  - **LocalStorage**: 회원가입 정보를 영구적으로 저장합니다.
  - **SessionStorage**: 사용자의 로그인 세션을 유지합니다.

### Deployment

  - **Vercel**: 프로젝트를 배포하고 관리합니다.

## 프로젝트 구조

```
style-commerce-web/
│
├── 📄 index.html                  # 메인 홈페이지
│
├── 🎨 css/                         # 페이지별 스타일시트
│   ├── index.css                 # 메인 페이지 스타일
│   ├── product-list.css          # 상품 목록 페이지 스타일
│   ├── product-detail.css        # 상품 상세 페이지 스타일
│   ├── login.css                 # 로그인/회원가입 페이지 스타일
│   └── global.css                # 공통 스타일 및 모달
│
├── 🖼️ image/                       # 로고, 아이콘, 상품 이미지 등 리소스
│
├── ⚙️ js/                          # JavaScript 파일
│   ├── script.js                 # Header/Footer 동적 삽입 및 경로 관리
│   ├── index.js                  # 메인 페이지 동적 콘텐츠 로딩 및 캐러셀
│   ├── product-list.js           # 상품 목록 필터링 및 렌더링
│   ├── product-detail.js         # 상품 상세 정보 렌더링
│   ├── login.js                  # 로그인 시스템
│   ├── signup.js                 # 회원가입 시스템 및 유효성 검사
│   └── header.js                 # 헤더 메뉴 상호작용 및 로그인 상태 관리
│
├── 📦 json/                        # JSON 데이터 파일
│   ├── products.json             # 상품 정보
│   ├── banner.json               # 메인 배너 정보
│   └── contents.json             # 콘텐츠 정보
│
└── 📃 pages/                       # 서브 페이지
    ├── product-list.html         # 상품 목록 페이지
    ├── product-detail.html       # 상품 상세 페이지
    └── account/
        ├── login.html            # 로그인 페이지
        └── signup.html           # 회원가입 페이지
```

## 실행 방법

### 온라인에서 바로 체험

**가장 쉬운 방법** - 별도 설치 없이 바로 사용 가능합니다.

👉 **[https://nover-feedback.vercel.app/](https://nover-feedback.vercel.app/)**

### 로컬 환경에서 실행

#### 요구 사항

  - 웹 브라우저 (Chrome, Firefox 등 최신 브라우저)
  - 코드 에디터 (예: VS Code)
  - 로컬 웹 서버 (VS Code의 **Live Server** 확장 프로그램 권장)

#### 설치 및 실행

1.  **저장소 클론**

    ```bash
    git clone https://github.com/yeonhee-cho/style-commerce-web-feedback.git
    cd style-commerce-web-feedback
    ```

2.  **VS Code Live Server 실행**

      - VS Code에서 프로젝트 폴더를 엽니다.
      - `Live Server` 확장 프로그램이 설치되어 있는지 확인합니다.
      - `index.html` 파일을 우클릭한 후 \*\*"Open with Live Server"\*\*를 선택합니다.

3.  **브라우저에서 접속**

      - Live Server가 실행되면 자동으로 브라우저에 `http://127.0.0.1:5500` (또는 다른 포트) 주소로 페이지가 열립니다.

## 핵심 기능 구현

### 1\. 동적 컴포넌트 로딩 (`script.js`)

`data-include-path` 속성을 이용하여 공통 UI(header, footer)를 비동기적으로 로드하고, 현재 페이지 경로에 따라 내부 링크와 이미지 경로를 동적으로 재설정합니다. 이를 통해 코드 중복을 방지하고 유지보수성을 향상시켰습니다.

```javascript
// data-include-path 속성을 가진 모든 요소를 찾아 HTML 콘텐츠를 삽입
window.addEventListener("load", async () => {
  const allElements = document.querySelectorAll("[data-include-path]");
  
  for (const el of allElements) {
    const includePath = el.dataset.includePath;
    const response = await fetch(includePath);
    if (response.ok) {
      const html = await response.text();
      // ... 경로 수정 로직 ...
      el.outerHTML = tempDiv.innerHTML;
    }
  }
});
```

### 2\. 사용자 인증 시스템 (`login.js`, `signup.js`)

`localStorage`에 사용자 데이터베이스를, `sessionStorage`에 현재 로그인된 사용자 세션을 저장하여 인증 시스템을 구현했습니다. 이를 통해 브라우저를 닫기 전까지 로그인 상태가 유지됩니다.

```javascript
// login.js - 로그인 기능
function loginFn() {
  const usersJSON = localStorage.getItem("userList"); // localStorage에서 사용자 목록 로드
  const users = JSON.parse(usersJSON);
  
  const foundUser = users.find((u) => u.userId === userId);
  
  if (foundUser && foundUser.password === password) {
    alert("로그인 성공!");
    // sessionStorage에 로그인된 사용자 정보 저장
    sessionStorage.setItem("loggedInUser", JSON.stringify(foundUser));
    window.location.href = "/";
  }
}
```

### 3\. 데이터 기반 상품 렌더링 (`product-list.js`)

`products.json` 파일에서 상품 데이터를 비동기적으로 가져와 화면에 렌더링합니다. URL 쿼리 파라미터(`?filter=...`)를 분석하여 카테고리별, 정렬 기준별 필터링 기능을 구현했습니다.

```javascript
// product-list.js - 상품 데이터 로드 및 렌더링
function addProducts() {
  $.get("../json/products.json").done(function (data) {
    $("#pdResult").html(
      data.map((item) => `
        <div class="product-item">
          <a href="product-detail.html" data-product='${JSON.stringify(item)}'>
            <img src="${item.image_urls[0]}" />
            <p>${item.product_name}</p>
            <p>${item.sale_price.toLocaleString()}원</p>
          </a>
        </div>
      `).join("")
    );
    // ...
  });
}
```

### 4\. 페이지 간 데이터 전달 (`product-list.js` → `product-detail.js`)

상품 목록에서 특정 상품을 클릭하면 해당 상품의 전체 데이터를 `JSON.stringify`를 통해 문자열로 변환한 후 `localStorage`에 저장합니다. 상품 상세 페이지에서는 이 데이터를 다시 불러와 동적으로 페이지를 구성합니다.

```javascript
// product-list.js - 상품 클릭 시 localStorage에 데이터 저장
document.querySelectorAll(".product-item a").forEach((link) => {
  link.addEventListener("click", function (e) {
    e.preventDefault();
    const productDataString = this.dataset.product;
    localStorage.setItem("selectedProduct", productDataString); // 클릭한 상품 정보 저장
    window.location.href = this.getAttribute("href");
  });
});

// product-detail.js - localStorage에서 데이터 로드하여 페이지 구성
const productDataString = localStorage.getItem("selectedProduct");
if (productDataString) {
  const productData = JSON.parse(productDataString);
  // 이 데이터를 사용하여 상세 페이지의 각 요소(이미지, 이름, 가격 등)를 채움
}
```

## 테스트 방법

### 회원가입 및 로그인

1.  **회원가입**: 상단 메뉴의 '로그인 / 회원가입' \> '회원가입' 버튼을 통해 새로운 계정을 생성합니다. 모든 정보는 브라우저의 `localStorage`에 저장됩니다.
2.  **로그인**: 생성한 계정 정보로 로그인합니다. 로그인 성공 시 `sessionStorage`에 세션이 저장되며, '로그아웃' 버튼이 활성화됩니다.
3.  **마이페이지**: 로그인 후 마이페이지에서 가입된 정보를 확인할 수 있습니다.

### 상품 필터링 및 검색

  - **필터링**: 상단 헤더의 카테고리(WOMAN, MAN 등) 또는 세그먼트 메뉴(추천, 랭킹)를 클릭하여 상품 목록이 정상적으로 필터링되는지 확인합니다.
  - **검색**: 검색 페이지에서 상품명, 브랜드명 등을 입력하여 실시간으로 결과가 표시되는지 확인합니다.

## 브라우저 호환성

### 지원 브라우저
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+

### 핵심 기능 호환성
- ✅ CSS Flexbox & Grid
- ✅ ES6+ JavaScript
- ✅ jQuery 3.7.1
- ✅ LocalStorage & SessionStorage

🔗 [웹사이트 방문하기](https://nover-feedback.vercel.app/)


