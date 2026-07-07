<!-- ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ -->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:4f8cff,100:8b5cf6&height=3&section=header"/>

<br/>

### `KYUNGRIM LEE`

<a href="https://github.com/yeekrim">
<img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&weight=500&size=17&pause=1000&color=4F8CFF&center=true&vCenter=true&width=520&lines=AI+Model+Design+%C3%97+Service+Development;From+model+training+to+production+service" alt="typing"/>
</a>

<br/>

<img src="https://img.shields.io/badge/Python-1f2937?style=flat-square&logo=python&logoColor=4F8CFF"/>
<img src="https://img.shields.io/badge/PyTorch-1f2937?style=flat-square&logo=pytorch&logoColor=4F8CFF"/>
<img src="https://img.shields.io/badge/FastAPI-1f2937?style=flat-square&logo=fastapi&logoColor=4F8CFF"/>
<img src="https://img.shields.io/badge/Flask-1f2937?style=flat-square&logo=flask&logoColor=4F8CFF"/>
<img src="https://img.shields.io/badge/React-1f2937?style=flat-square&logo=react&logoColor=4F8CFF"/>
<img src="https://img.shields.io/badge/TypeScript-1f2937?style=flat-square&logo=typescript&logoColor=4F8CFF"/>
<br/>
<img src="https://img.shields.io/badge/Vue.js-1f2937?style=flat-square&logo=vuedotjs&logoColor=4F8CFF"/>
<img src="https://img.shields.io/badge/Electron-1f2937?style=flat-square&logo=electron&logoColor=4F8CFF"/>
<img src="https://img.shields.io/badge/PostgreSQL-1f2937?style=flat-square&logo=postgresql&logoColor=4F8CFF"/>
<img src="https://img.shields.io/badge/ChromaDB-1f2937?style=flat-square&logo=databricks&logoColor=4F8CFF"/>
<img src="https://img.shields.io/badge/Docker-1f2937?style=flat-square&logo=docker&logoColor=4F8CFF"/>
<img src="https://img.shields.io/badge/Git-1f2937?style=flat-square&logo=git&logoColor=4F8CFF"/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:4f8cff,100:8b5cf6&height=3&section=header"/>

</div>

<br/>

## &nbsp;`01` &nbsp;Featured Projects

<table>
<tr>
<td width="50%" valign="top">

#### 🤖 RAG 기반 사내 챗봇
**[company-assistant ↗](https://github.com/yeekrim/company-assistant)** · `active`

> 회사별 문서를 근거로 답변하는 멀티테넌트 RAG 챗봇

`NVIDIA NIM` `Llama 3.1 70B` `ChromaDB` `FastAPI`

- LLM 2회 교체 + 프롬프트 보강으로 한국어 품질 개선
- PDF 표 구조화 추출, 대화 히스토리 유사도 필터링
- pytest 단위 테스트 16개 — retriever 커버리지 **86%**

</td>
<td width="50%" valign="top">

#### 🧏 실시간 수어 번역 시스템
`졸업 프로젝트 · 팀 리더` · **Val Acc 0.94**

> 한국어·영어 수어를 실시간 텍스트로 번역

`PyTorch` `LSTM` `MediaPipe` `OpenCV`

- 양손 관절 126차원 × 30프레임 시계열 학습
- LSTM + 교차검증으로 시간적 관계 학습
- 공개 데이터셋 한계 → **1,000개 단어 자체 구축**

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🎣 피싱 사이트 탐지
`화이트햇 스쿨 2기` · **F1 0.87 → 0.93**

> ML+DL 앙상블 기반 피싱 URL 탐지

`LightGBM` `CNN` `GridSearchCV`

- URL/WHOIS/콘텐츠 **17개 피처 엔지니어링**
- 정상 15만 + 피싱 14만 URL 수집·정제 담당
- LightGBM + CNN 앙상블 → Recall **0.79 → 0.89**

</td>
<td width="50%" valign="top">

#### 🚗 위조 번호판 탐지 시스템
**[fake-license-plate-detection ↗](https://github.com/yeekrim/fake-license-plate-detection)**

> YOLOv5 + 특징점 매칭 기반 위조 번호판 판별

`YOLOv5` `OpenCV` `OCR`

- SIFT/SURF/ORB 비교 실험 → **ORB + knnMatch** 채택
- 위조 번호판 직접 제작해 데이터셋 구축
- OCR 연계 주차장 게이트 시뮬레이션

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🖨️ 3D 프린터 로그 시각화
`개인 프로젝트`

> SLA600 공정 로그 파싱 → 장비 내부 거동 재구성

`Python` `Data Visualization` `Log Parsing`

- 축별(빌드 플레이트/리코터/레진 블럭) 시계열 시각화
- 13시간 47분 · 1,059 레이어 실공정 로그 분석
- 신규 부품 성능 검증에 활용

</td>
<td width="50%" valign="top">
</td>
</tr>
</table>

<br/>

## &nbsp;`02` &nbsp;Experience

**Smart 3D Printing 연구실 소프트웨어팀** &nbsp;`2025.04–07 · 2025.10–11`<br/>
**한국전자기술연구원 (KETI) 연계 인턴** &nbsp;`2025.08–09`

> 연구자용 웹 / 데스크톱 애플리케이션 개발 및 QA

- **8GB 파일 업로드 HTTP 413 해결** — Chunk 분할 + 병렬 전송 튜닝(256MB × 4) → `17분 → 13분 (24.5% ↓)`
- **이미지 1,000장 전송 최적화** — 반복 API 호출을 ZIP 압축 전송으로 개선 → `17분 → 30초 (97% ↓)`
- Vue / Flask 웹 플랫폼 유지보수 및 CRUD 기능 구현

<br/>

<div align="center">
<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:8b5cf6,100:4f8cff&height=3&section=footer"/>
</div>
