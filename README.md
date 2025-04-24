# 👵📱 AR 길안내 – 실외 AR 내비게이션 앱 for Seniors

> 지도를 보기 어려운 어르신도 쉽게 사용할 수 있는  
> **실시간 AR 기반 길안내 앱**입니다.

---

## 🔍 프로젝트 소개

**AR 길안내 앱**은 스마트폰 카메라 위에 현실 길을 그대로 비추면서,  
그 위에 실시간으로 **화살표와 거리 정보**를 오버레이하여  
노년층 사용자도 직관적으로 따라갈 수 있게 돕는 AR 네비게이션 앱입니다.

- "병원 좀 가야 하는데 어떻게 가더라..."
- "지도는 잘 모르겠고… 그냥 보여줬으면 좋겠네"

> 이 앱은 그런 사용자들을 위해 만들어졌습니다.

---

## 🎯 주요 대상 사용자

- 지도를 보는 것이 어려운 **노년층**
- 방향 감각이 약한 분들
- **직관적인 안내**를 선호하는 모든 사용자

---

## ✅ 핵심 기능 (MVP 기준)

- 📍 **AR 화살표 안내** – 거리 위에 실시간 경로 표시
- 🗣 **음성 검색** – 자연어로 장소 검색 ("병원 가고 싶어")
- 🔊 **음성 안내** – "왼쪽으로 가세요", "도착했습니다" 등
- 🔎 **텍스트 검색** – 직접 목적지 입력 가능
- 🧭 **최단 거리 계산** – Google Maps API 사용
- 🧓 **초간단 UI** – 큰 버튼과 글씨로 쉽고 간편
- 🚨 **비상 호출 기능** – 현재 위치 + 화면 캡처 전송

---

## 🛠 기술 스택

| 기능 | 사용 기술 |
|------|-----------|
| AR 렌더링 | Unity + AR Foundation / WebAR (Three.js) |
| 위치 추적 | GPS + ARCore Geospatial API |
| 음성 명령 인식 | 초경량 LLM (BitNet 수준) |
| 음성 안내 | Google TTS / CLOVA Voice |
| 경로 탐색 | Google Maps Directions API |
| 백엔드 | Firebase / Supabase / AWS Lambda |
| 프론트엔드 | Unity UI / Flutter / React Native |

---

## 🧪 사용 예시 시나리오

> “맨날 가던 병원으로 가줘 주사 좀 맞으러 갔다 오려고”  
> → “저번에 가셨던 서울힘내과 의원으로 안내해드릴까요?”  
> → “그랴그랴”  
> → “지금부터 안내를 시작하겠습니다.”  
> → 📷 AR 화면에서 화살표가 길을 알려줌

---

## 📦 실행 방법 (준비 중)

🚧 개발 중입니다. 추후 설치 및 실행 가이드를 추가할 예정입니다.

---

## 🙌 기여 및 문의

이 프로젝트는 **노인 친화적 기술을 위한 오픈소스 실험**입니다.  
기여 또는 아이디어 제안은 언제든 환영합니다!

- 프로젝트 관리자: [loveiscomplicated]
- 문의: loveiscomplicated@yonsei.ac.kr

# 👵📱 AR Path Guide – Outdoor AR Navigation App for Seniors

> A real-time **AR navigation app** designed to help elderly users  
> easily follow directions without reading maps.

---

## 🔍 Project Overview

**AR Path Guide** is a mobile navigation app that overlays **real-time arrows and distance markers** on top of the real-world street view through the smartphone camera.  
This allows users—especially seniors—to reach their destination **without needing to interpret 2D maps**.

- “I just want to go to the clinic I always go to...”
- “Maps are confusing, I just want it to show me the way.”

> This app was made for people who feel that way.

---

## 🎯 Target Users

- Seniors who struggle to use map apps  
- Users with poor directional sense  
- Anyone who prefers **visual, intuitive guidance**

---

## ✅ Key Features (MVP)

- 📍 **AR Arrow Navigation** – Arrows overlaid on streets in real time
- 🗣 **Voice Search** – Natural speech input ("Take me to the clinic")
- 🔊 **Voice Directions** – Spoken guidance ("Turn left in 100m")
- 🔎 **Text Search** – Type in destination manually
- 🧭 **Shortest Path Algorithm** – Google Maps API powered routing
- 🧓 **Simplified UI** – Large buttons, minimal text
- 🚨 **Emergency Button** – Sends current location + screen snapshot

---

## 🛠 Tech Stack

| Feature | Technology |
|--------|------------|
| AR Rendering | Unity + AR Foundation / WebAR (Three.js) |
| Location Tracking | GPS + ARCore Geospatial API |
| Voice Understanding | Lightweight LLM (e.g., BitNet scale) |
| Voice Output | Google TTS / CLOVA Voice |
| Route Calculation | Google Maps Directions API |
| Backend | Firebase / Supabase / AWS Lambda |
| Frontend | Unity UI / Flutter / React Native |

---

## 🧪 Usage Scenario

> “Take me to the clinic I went to last time.”  
> → “Do you mean Seoul Health Clinic?”  
> → “Yes, that one.”  
> → “Okay, guiding you now.”  
> → 📷 AR view displays arrows on the actual street

---

## 📦 How to Run (Coming Soon)

🚧 This app is currently under development.  
Setup and build instructions will be added soon.

---

## 🙌 Contributions & Contact

This project is an open-source initiative to improve **senior-friendly technology**.  
Ideas, issues, and contributions are always welcome!

- Maintainer: [loveiscomplicated]  
- Contact: loveiscomplicated@yonsei.ac.kr


