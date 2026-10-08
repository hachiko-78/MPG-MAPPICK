# MPG-MAPPICK
# 🗺️ Mappick (매픽)
> **"지도에서 고르고, 일정으로 연결하는 나만의 여행 계획"**

Android 기반의 위치·동선 연동 및 사용자 맞춤형 여행 플랫폼 **Mappick**입니다.

---

### 📌 주요 핵심 기능

#### 1. 📅 일정 뷰 - 지도 뷰 실시간 양방향 연동
* 일자별 방문 장소, 시간, 예상 체류 시간, 예산 카드를 작성하고 Google Maps 상의 번호 마커 및 동선(Polyline)으로 한눈에 확인
* 일정 순서나 장소를 변경하면 지도 상의 마커 번호와 동선 연결선이 즉시 리프레시

#### 2. 🔀 [차별화] 유연한 대안 일정 (Plan A / Plan B 마인드맵)
* 웨이팅이나 휴무일 위험이 있는 장소 하위에 대안 선택지(Plan B)를 마인드맵 형태로 연결 등록
* 여행 중 현장 상황에 맞춰 원클릭으로 Plan A ↔ Plan B 즉시 교체 및 지도 동선 반영

#### 3. 🎨 [커스텀] DIY 에셋 제작 (여행 가이드북 & 추억 기록장)
* 동일한 커스텀 캔버스 엔진(배경지, 템플릿 서식, 스티커 요소, 폰트)을 탑재
* **여행 전:** 나만의 일정 가이드북을 꾸미고 디지털/PDF로 출력 소장
* **여행 후:** 실제 다녀온 사진과 방명록 후기를 담은 나만의 여행 다이어리/기록장 완성

#### 4. 💰 트래블 포켓 (가계부)
* 현지 통화 지출 입력 및 수동 환율 적용을 통한 원화 환산 자동 계산
* 계획용 '예상 비용'과 포켓의 '실제 지출'을 독립 관리하여 중복 집계 방지

#### 5. 📋 준비물 체크리스트 & 개인 메모장
* 필수 서류, 전자기기 등 카테고리별 준비물 점검 및 진행률 표시 (공동 준비물 담당자 지정 가능)
* 작성자만 열람할 수 있는 개인 메모장 제공

#### 6. 👥 Firebase 기반 실시간 공동 계획
* 초대 코드를 통해 동행인을 초대하고, Cloud Firestore를 통해 공동 일정 및 지출 내역을 실시간 동기화

---

### 🛠️ Tech Stack & Architecture
* **Language/IDE:** Java / Kotlin, Android Studio
* **UI/UX:** Fragment, Custom ListView & Adapter, Custom Canvas View, DatePicker/TimePicker
* **Database:** SQLite (Local Storage), Firebase Cloud Firestore (Cloud Sync)
* **API & SDK:** Google Maps Android SDK, Firebase Authentication

---

### 👥 Team Members & Roles
* **윤서현 (팀장):** 백엔드 & DB (SQLite Schema, DB Helper, Firebase Auth/Firestore)
* **오수린:** 지도 & QA (Google Maps SDK, Polyline, 외부 지도 연동, 디자인 가이드라인)
* **정예원:** 가계부 & QA (트래블 포켓, 체크리스트, 개인 메모, 테스트 시나리오)
* **홍세희:** 프론트엔드 & UI (일정/Plan A/B UI, 실시간 연동, DIY 커스텀 에셋 캔버스 엔진)
