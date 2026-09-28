<p align="right">
  <a href="README.md">English</a> | <strong>한국어</strong>
</p>

# 🍕 Give Me The Pizza - Code Lounge

> **"함께할 준비, 코드 하나면 돼요."**  
> 6자리 입장코드로 번거로운 가입 없이 즉시 공간을 열고 아이디어를 공유하는 미니멀 & 인터랙티브 스티커 보드 플랫폼입니다.

[![Live Demo](https://img.shields.io/badge/Live_Demo-GitHub_Pages-2bb379?style=for-the-badge&logo=github)](https://lolonoa-ralo.github.io/give-me-the-pizza/)
[![Vanilla JS](https://img.shields.io/badge/Vanilla-HTML5%20%2F%20CSS3%20%2F%20JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#-기술-스택)

---

## 🌐 라이브 데모 (Live Demo)
별도의 설치 없이 지금 바로 웹 브라우저에서 체험해보실 수 있습니다:  
👉 **[https://lolonoa-ralo.github.io/give-me-the-pizza/](https://lolonoa-ralo.github.io/give-me-the-pizza/)**

---

## ✨ 주요 특징 (Key Features)

### 🔑 1. 번거로움 없는 6자리 입장코드 시스템
* **회원가입/로그인 불필요**: 복잡한 계정 생성 절차 없이 6자리 랜덤 코드로 공간을 즉시 생성하고 참여합니다.
* **이원화된 권한 체계**: 친구들을 초대할 수 있는 **일반 입장코드**와 방 관리 권한이 부여되는 **관리자 코드**가 함께 생성됩니다.

### 📌 2. 감각적인 인터랙티브 스티커 보드
* **직관적인 메모 카드**: 생각, 아이디어, 할 일, 응원 한마디를 카드 형태로 보드에 자유롭게 부착할 수 있습니다.
* **원클릭 클립보드 복사**: 각 스티커의 텍스트를 버튼 하나로 간편하게 복사할 수 있습니다.
* **실시간 검색**: 보드에 게시물이 많아져도 키워드로 빠르게 원하는 스티커를 찾아낼 수 있습니다.
* **수정 및 삭제**: 남긴 스티커의 내용을 손쉽게 수정하거나 정리할 수 있습니다.

### 👑 3. 강력한 방장(Host) 관리 기능
* **코드 변경(Rotate Code)**: 외부 유출 시 새로운 입장코드로 즉시 갱신할 수 있습니다.
* **방 완전 삭제(Delete Room)**: 안전 문구(`삭제하겠습니다`) 확인 후 공간과 메모를 완벽하게 정리하고 모든 유저를 퇴장시킬 수 있습니다.

### 🎨 4. 섬세한 사용자 경험(UX)과 디자인
* **다크 모드 / 라이트 모드**: 환경과 취향에 맞게 눈이 편안한 테마로 즉시 전환할 수 있습니다.
* **다국어(i18n) 지원**: 한국어(KO) 및 영어(EN) 인터페이스를 기본 내장하여 누구나 편리하게 이용할 수 있습니다.
* **반응형 디자인**: 모바일, 태블릿, 데스크톱 등 모든 화면 크기에서 유연하게 작동합니다.

---

## 🚀 빠른 시작 가이드 (Quick Start)

외부 라이브러리나 복잡한 빌드 과정이 전혀 없는 **순수 웹(Vanilla Web)** 구조입니다.

### 방법 1: 파일 직접 열기
저장소를 다운로드한 후 `index.html` 파일을 더블 클릭하여 웹 브라우저에서 바로 열 수 있습니다.

### 방법 2: 로컬 웹 서버 실행
```bash
# Python 3 내장 서버로 실행
python -m http.server 8000
```
브라우저에서 `http://localhost:8000`으로 접속합니다.

---

## 📖 사용 방법 (How to Use)

1. **공간 만들기 (방장)**
   - 메인 화면에서 "무작위 코드 만들기"를 클릭합니다.
   - 생성된 6자리 코드를 확인하고, 친구들에게 공유할 일반 코드를 복사합니다.
2. **공간 입장하기 (참여자)**
   - "코드 입력하기"를 누르고 6자리 입장코드와 닉네임을 입력합니다.
3. **스티커 작성 및 협업**
   - 상단 툴바의 **`+` (스티커 추가)** 버튼을 눌러 메모를 남기고 다른 유저들과 소통합니다.

---

## 🛠️ 기술 스택 (Tech Stack)

* **Markup**: HTML5 (접근성 및 Semantic 구조 준수)
* **Styling**: Pure Vanilla CSS3 (CSS Variables, Flexbox/Grid, Glassmorphism, Theme Switching)
* **Scripting**: Pure Vanilla JavaScript (ES6+, 0 의존성)
* **Deployment**: GitHub Pages

---

## 📂 파일 구성 (Repository Structure)

```text
give-me-the-pizza-main/
├── favicon.png       # 서비스 파비콘 아이콘
├── index.html        # 통합 프론트엔드 애플리케이션 (UI, 스타일, 로직 내장)
├── README.md         # 영문 설명서 (기본 표시)
└── README_KR.md      # 한글 설명서
```

---

## 🍕 PizzaC2 연계 프로젝트 안내
이 프로젝트의 입장코드 및 스티커 보드 아키텍처는 LOTS(Living Off Trusted Sites) 개념 증명 C2 프레임워크인 **[PizzaC2](https://github.com/lolonoa-ralo/Pizza-C2)**의 중계 채널로도 활용됩니다.
