# Frontend Study

HTML, CSS, JavaScript, React를 단계별로 학습한 실습 저장소입니다.

---

## 기술 스택

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React_18/19-61DAFB?style=flat&logo=react&logoColor=black)
![React Router](https://img.shields.io/badge/React_Router_7-CA4245?style=flat&logo=reactrouter&logoColor=white)
![MUI](https://img.shields.io/badge/MUI-007FFF?style=flat&logo=mui&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=flat&logo=axios&logoColor=white)

---

## 프로젝트 구조

```
frontend/
├── html_css/              # HTML5 & CSS3 기초 실습
│   ├── 1_basic.html       # HTML 기본 구조
│   ├── 2_html_js.html     # HTML + JavaScript 연동
│   ├── 3_chart.html       # 차트 연동
│   ├── 4_jquery.html      # jQuery 기초
│   ├── 5_jqeury_css_selector.html  # jQuery CSS 선택자
│   ├── 6_chart_jquery.html         # 차트 + jQuery
│   └── data/              # 실습용 데이터 (sales.json 등)
│
├── js/                    # JavaScript 기초 실습
│   ├── 1_var.js           # 변수 (var, let, const)
│   ├── 2_string.js        # 문자열
│   ├── 3_operator.js      # 연산자
│   ├── 4_typecasting.js   # 형변환
│   ├── 5_flowcontrol_if.js   # 조건문
│   ├── 6_flowcontrol_loop.js # 반복문
│   ├── 7_function.js      # 함수
│   ├── 8_array.js         # 배열
│   ├── 9_object.js        # 객체
│   ├── 10_class.js        # 클래스
│   ├── 11_unstructure_array.js   # 배열 구조분해
│   ├── 12_unstructure_object.js  # 객체 구조분해
│   ├── 13_spread_oper.js  # 스프레드 연산자
│   ├── 14_async_promise.js  # 비동기 / Promise
│   ├── 15_cal_null_safe.js  # null 안전 연산
│   ├── 16_try_catch.js    # 예외 처리
│   └── data/              # 실습용 데이터
│
└── react/
    ├── basic-cdn/         # CDN 방식 React 기초
    └── app-npm/
        ├── demo/          # React 19 기초 (CRA) — 컴포넌트, LifeCycle, 폼 요소
        ├── hook-test/     # React 18 Hooks — useState, useEffect, useReducer, 커스텀 훅, MUI, Axios
        └── route-app/     # React Router 7 + Vite — SPA 라우팅, 동적 세그먼트
```

---

## 실행 방법

### HTML/CSS 실습

`html_css/` 내 `.html` 파일을 VSCode Live Server로 열기

### JavaScript 실습

```bash
# VSCode Code Runner 확장으로 직접 실행하거나
node js/1_var.js
```

### React — demo (React 19 / CRA)

```bash
cd react/app-npm/demo
npm install
npm start
```

### React — hook-test (React 18 / MUI / Axios)

```bash
cd react/app-npm/hook-test
npm install
npm start
```

### React — route-app (React 18 / React Router 7 / Vite)

```bash
cd react/app-npm/route-app
npm install
npm run dev
```

브라우저에서 `http://localhost:5173` 접속

---

## 학습 내용

| 폴더 | 주요 학습 내용 |
|------|---------------|
| `html_css` | HTML5 구조, CSS3 스타일, jQuery, 차트 |
| `js` | 변수·타입·연산자, 함수, 배열·객체, 클래스, 비동기(Promise) |
| `react/basic-cdn` | CDN으로 React 컴포넌트 맛보기 |
| `react/demo` | 컴포넌트 구조, Props, State, 라이프사이클, 폼 요소 |
| `react/hook-test` | useState·useEffect·useReducer, 커스텀 훅, MUI, Axios API 통신 |
| `react/route-app` | React Router 7, 중첩 라우트, 동적 세그먼트, SPA 구성 |

---

## 개발 환경

- **Node.js** 18 이상
- **VSCode** 권장 확장: ESLint, Prettier, Live Server, Code Runner, Auto Rename Tag
