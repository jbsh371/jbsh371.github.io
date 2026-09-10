# jbsh371.github.io

**다시개발 — 기록하는 개발자** 의 프로필 페이지입니다.

🔗 <https://jbsh371.github.io>

---

## 소개

개발자로 시작해 분석하고 설계하며 프로젝트를 관리해왔고, 지금은 다시 개발로 돌아왔습니다.
기록과 정리를 통해 본질을 파악하고, 그 기록을 기반으로 더 나은 개발을 만들어갑니다.
AI를 공부하며 책을 씁니다.

- GitHub: <https://github.com/jbsh371>
- 블로그: <https://recording-it.tistory.com/>
- 이메일: jbsh371@gmail.com

---

## 페이지 구성

| 파일 | 설명 |
| --- | --- |
| `index.html` | 메인 프로필 페이지 (소개 · 책 소개) |
| `blog_info.html` | 블로그 소개 |
| `contact.html` | 연락처 안내 |
| `privacy.html` | 개인정보처리방침 |

---

## 출간한 전자책

교보문고 · YES24에서 만나보실 수 있습니다.

### 01. LangGraph v1.x로 이해하는 LLM Agent의 흐름과 통제
AI Agent를 처음 이해하기 위한 책. LangGraph를 통해 Agent의 실행 과정을 흐름으로 바라보고, State를 기준으로 동작을 이해하며, LLM과 도구를 구성 요소로 나누어 생각하는 방식을 배웁니다.
[교보문고](https://ebook-product.kyobobook.co.kr/dig/epd/ebook/E000012440835) · [YES24](https://www.yes24.com/product/goods/173925712)

### 02. 나만의 Agent 만들기 — OpenAI(GPT-5) 편
OpenAI API로 원리를 이해하고 SDK로 시스템을 완성하는 흐름을 경험하는 입문서. 사용자 요청 이해, 외부 도구 호출, 대화이력 관리, 웹 검색, 문서 기반 질의응답 등을 직접 구현하며 배웁니다.
[교보문고](https://ebook-product.kyobobook.co.kr/dig/epd/ebook/E000012082137) · [YES24](https://www.yes24.com/product/goods/159581129)

### 03. 따라하며 쉽게 익히는 MCP — 파이썬과 FastMCP로 직접 구축하기
MCP를 실습 중심으로 익히는 책. FastMCP로 서버를 반복 구축하고, Claude Desktop, Cursor, 파이썬 등 다양한 클라이언트로 검증하며, Anthropic, OpenAI, Gemini 등 상용 API와 연동하는 방법을 배웁니다.
[교보문고](https://ebook-product.kyobobook.co.kr/dig/epd/ebook/E000012019862) · [YES24](https://www.yes24.com/product/goods/155061618)

### 04. 생성형 AI와 카카오톡으로 만드는 실전 TODO 앱
생성형 AI 서비스를 처음부터 끝까지 구현하는 실전 가이드. 클라우드 서버 구축, OpenAI API 연동, 파이썬 FastAPI 웹 서비스 개발, 카카오 채널 연동까지 AI 서비스의 전 과정을 경험합니다.
[교보문고](https://ebook-product.kyobobook.co.kr/dig/epd/ebook/E000012019843) · [YES24](https://www.yes24.com/product/goods/155061617)

---

## 기술 스택

- 정적 HTML / CSS / Vanilla JavaScript (빌드 도구 · 프레임워크 없음)
- 다크 모드 지원 (`prefers-color-scheme`)
- 반응형 레이아웃
- 웹폰트: Noto Sans KR, Instrument Serif (Google Fonts)
- 호스팅: GitHub Pages

## 로컬에서 실행하기

별도의 빌드 과정이 없습니다. 저장소를 받은 뒤 `index.html`을 브라우저로 열거나, 간단한 로컬 서버를 띄우면 됩니다.

```bash
git clone https://github.com/jbsh371/jbsh371.github.io.git
cd jbsh371.github.io
python -m http.server 8000
# http://localhost:8000 접속
```

## 배포

`main` 브랜치에 푸시하면 GitHub Pages를 통해 자동으로 배포됩니다.

---

© 다시개발
