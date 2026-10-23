# ✈️ WhereTo AI (어디가나 AI)

> **Google Gemini 3.8 Flash** 기반 맞춤형 여행 가이드 및 스마트 동선 지도 웹 애플리케이션입니다.

![WhereTo AI License](https://img.shields.io/badge/license-MIT-blue.svg)
![Gemini AI](https://img.shields.io/badge/AI-Gemini%203.8%20Flash-black)
![Leaflet Map](https://img.shields.io/badge/Map-Leaflet.js-green)

---

## 🌟 주요 기능 (Key Features)

- 📅 **맞춤형 여행 조건 입력**: 여행 날짜, 목적지, 선호 활동/명소, 미식 취향 및 기타 요청사항 반영
- 🤖 **Gemini 3.8 Flash AI 분석**:
  - 해외/국내 여행 자동 판별 및 해당 국가의 예측 날씨, 환율, 언어, 긴급 연락처 제공
  - 현지 문화 에티켓 및 팁 안내
  - 일자별 상세 가이드 및 장소 카테고리(관광, 식당, 카페, 숙소) 자동 분류
- 🗺️ **일자별 컬러 동선 지도 (Interactive Leaflet Map)**:
  - 날짜별로 명확하게 구분되는 비비드 컬러 패스(Polyline) 및 스팟 핀 표시
  - 일정 카드를 클릭하면 지도 상의 해당 위치로 포커싱(Fly-to)되는 상호작용
  - API Key 제한이나 403 차단 없는 오픈 지도 레이어(Esri Canvas) 적용
- 💡 **추가 추천 카드**:
  - 일정표 외에 AI가 추가로 제안하는 추천 맛집, 액티비티/체험, 명소/갈 곳 카드 제공
- 📦 **여행 플랜 보관함 (Local Storage)**:
  - 생성된 일정이 `Plan #1`, `Plan #2` 형식으로 자동 저장
  - 지난 플랜 클릭 시 즉시 불러오기 및 개별 삭제 지원
- 🖥️ **스마트 UI & 레이아웃 관리**:
  - 깔끔하고 세련된 모노크롬 다크 모드 디자인
  - 여행 설정 입력창 및 플랜 보관함 접기/펴기(확대/축소) 토글 기능
  - 날짜 선택창 클릭 시 즉시 달력(Datepicker) 표시
  - PDF 저장 및 인쇄 전용 뷰 지원

---

## 🛠️ 기술 스택 (Tech Stack)

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Tailwind CSS (CDN)
- **AI Model**: Google Gemini API (`gemini-3.8-flash`)
- **Map & GIS**: Leaflet.js, Esri World Dark Canvas Tiles
- **Icons**: Lucide Icons

---

## 🚀 시작하기 (Getting Started)

별도의 백엔드 서버나 빌드 과정 없이 `index.html` 파일을 브라우저에서 실행하여 바로 사용할 수 있습니다.

### 1. 저장소 클론 (Clone)
```bash
git clone [https://github.com/YOUR_USERNAME/WhereTo-AI.git](https://github.com/YOUR_USERNAME/WhereTo-AI.git)
cd WhereTo-AI
