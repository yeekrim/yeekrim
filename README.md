![header](https://capsule-render.vercel.app/api?type=waving&color=0:7156b7,100:6fa8dc&height=220&text=Hi,%20I'm%20Kyungrim%20👋&fontColor=ffffff&fontAlignY=40&fontSize=48&desc=AI%20Model%20Design%20×%20Service%20Development&descAlignY=58&descSize=18)

<div align="center">

### AI 모델을 설계하고, 실제 서비스로 만듭니다

<br/>

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/> <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white"/>

<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/> <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white"/> <img src="https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white"/>

<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/> <img src="https://img.shields.io/badge/ChromaDB-FF6B6B?style=for-the-badge&logo=databricks&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>

</div>

<br/>

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🤖 RAG 기반 사내 챗봇
**[company-assistant](https://github.com/yeekrim/company-assistant)** · `진행 중`

회사별 문서를 근거로 답변하는 멀티테넌트 RAG 챗봇

- **NVIDIA NIM** (Llama 3.1 70B) + ChromaDB + FastAPI
- LLM 2회 교체 + 프롬프트 보강으로 한국어 품질 개선
- PDF 표 구조화 추출, 대화 히스토리 유사도 필터링
- pytest 단위 테스트 16개 — **retriever 커버리지 86%**

`FastAPI` `React` `ChromaDB` `PostgreSQL` `Docker`

</td>
<td width="50%" valign="top">

### 🧏 실시간 수어 번역 시스템
`졸업 프로젝트 · 팀 리더` · **Val Acc 0.94**

한국어·영어 수어를 실시간 텍스트로 번역

- MediaPipe 양손 관절 126차원 × 30프레임 시계열
- **LSTM + 교차검증**으로 시간적 관계 학습
- 공개 데이터셋 한계 → **1,000개 단어 자체 구축**
- 실시간 카메라 입력 → 확률 기반 예측 출력

`PyTorch` `LSTM` `MediaPipe` `OpenCV`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎣 피싱 사이트 탐지
`화이트햇 스쿨 2기` · **F1 0.87 → 0.93**

ML+DL 앙상블 기반 피싱 URL 탐지

- URL/WHOIS/콘텐츠 **17개 피처 엔지니어링**
- 정상 15만 + 피싱 14만 URL 수집·정제 담당
- LightGBM + CNN 앙상블 → **Recall 0.79 → 0.89**

`LightGBM` `CNN` `GridSearchCV`

</td>
<td width="50%" valign="top">

### 🚗 위조 번호판 탐지 시스템
**[fake-license-plate-detection](https://github.com/yeekrim/fake-license-plate-detection)**

YOLOv5 + 특징점 매칭 기반 위조 번호판 판별

- SIFT/SURF/ORB 비교 실험 → **ORB + knnMatch** 채택
- 위조 번호판 직접 제작해 데이터셋 구축
- OCR 연계 주차장 게이트 시뮬레이션

`YOLOv5` `OpenCV` `OCR`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🖨️ 3D 프린터 로그 시각화
`개인 프로젝트`

SLA600 공정 로그 파싱 → 장비 내부 거동 재구성

- 축별(빌드 플레이트/리코터/레진 블럭) 시계열 시각화
- 13시간 47분 · 1,059 레이어 실공정 로그 분석
- 신규 부품 성능 검증에 활용

`Python` `Data Visualization` `Log Parsing`

</td>
<td width="50%" valign="top">

</td>
</tr>
</table>

<br/>

## 💼 Experience

**Smart 3D Printing 연구실 소프트웨어팀** (2025.4 ~ 2025.7, 2025.10 ~ 2025.11) + **한국전자기술연구원(KETI) 연계 인턴** (2025.8 ~ 2025.9)

> 연구자용 웹/데스크톱 애플리케이션 개발 및 QA

- 📦 8GB 파일 업로드 HTTP 413 해결 — Chunk 분할 + 병렬 전송 파라미터 튜닝(256MB × 4)으로 **17분 → 13분 (24.5% ↓)**
- 🖼️ 이미지 1,000장 전송 — 반복 API 호출을 ZIP 압축 전송으로 개선, **17분 → 30초 (97% ↓)**
- 🔧 Vue/Flask 웹 플랫폼 유지보수 및 CRUD 기능 구현

<br/>

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:6fa8dc,100:7156b7&height=120&section=footer)
