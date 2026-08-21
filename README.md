<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=185&section=header&text=Jonghwa%20Park&fontSize=54&fontColor=ffffff&fontAlignY=36&desc=AI%20%C2%B7%20Robotics%20%C2%B7%20Embedded&descSize=18&descAlignY=58&animation=fadeIn" alt="Jonghwa Park — AI, Robotics, Embedded" />

### On-device AI와 자율 로봇을, 실제 동작하는 서비스로 연결합니다.

`Robot Software` · `On-device AI` · `Product Engineering`

</div>

## 🙋‍♂️ About Me

재난 현장에서 움직이는 로봇부터 AI 기반 행정 서비스까지, **하드웨어와 소프트웨어의 경계를 넘어 사용자에게 닿는 시스템**을 만드는 데 관심이 있습니다.

- 🤖 `ROS 2` 기반 자율 탐사, 임무 제어, 안전 체인과 실시간 관제 연동을 구현합니다.
- 🧠 온디바이스 비전 모델의 정확도뿐 아니라 지연 시간, 처리량과 실제 장치 제약을 함께 검증합니다.
- 🚀 `TypeScript`와 `FastAPI`를 활용해 아이디어를 빠르게 제품 형태로 구현합니다.
- 💬 돌아가는 코드에서 멈추지 않고, 의사결정과 한계까지 설명되는 코드를 지향합니다.

<div align="center">

<img src="https://img.shields.io/badge/VQA_Challenge-1st_%2F_193-2C5364?style=for-the-badge&logo=pytorch&logoColor=white" alt="VQA Challenge first place out of 193 teams" />
<img src="https://img.shields.io/badge/AI_Hackathon-Final_6_%2F_103-203A43?style=for-the-badge&logo=kakaotalk&logoColor=white" alt="AI Hackathon finalist, 6 out of 103 teams" />
<img src="https://img.shields.io/badge/Sentinel_CI-941_Tests-36BCF7?style=for-the-badge&logo=gitlab&logoColor=white" alt="Sentinel UGV CI with 941 tests" />

</div>

## 🚀 Featured Projects

### 🤖 [Sentinel-UGV](https://github.com/Common-AIOT/Sentinel-UGV) · 재난 현장 자율 탐사 로봇

실제 차량에서 자율 탐사부터 사람 접근, 영상 스트리밍과 관제 명령까지 연결한 온디바이스 AI 관제 시스템입니다.

> **Role** · Robot SW / ROS 2 — 자율 탐사, 임무 제어, 안전 체인, 녹화·스트리밍, 관제 연동<br/>
> **System validation** · 프로젝트 종료 시 GitLab CI 자동 시험 941개 · Detect 약 15FPS · 90° 회전에서 EKF yaw 89.02°<br/>
> **Stack** · `ROS 2` `Python` `C++` `Jetson` `MQTT` `Spring Boot`

<div align="center">
<a href="https://www.youtube.com/watch?v=guyA2-h8ZME"><img width="72%" src="https://img.youtube.com/vi/guyA2-h8ZME/maxresdefault.jpg" alt="Sentinel UGV 전체 시연 영상" /></a>
<br/>
<sub>▶ Sentinel UGV 전체 시연 보기</sub>
</div>

### 🏆 [Recycle VQA Challenge](https://github.com/Janjonghwa/Recycle_VQA_Challenge) · 재활용품 이미지 VQA

이미지와 자연어 질문을 함께 이해해 정답을 선택하는 멀티모달 모델을 개발했습니다.

> **Contribution** · 보기 순서 TTA 실험, 모델별 예측 비교와 모델 선정, 프롬프트 엔지니어링<br/>
> **Result** · SSAFY AI Challenge **193팀 중 전국 1위** · Private score `0.97635`<br/>
> **Stack** · `PyTorch` `Transformers` `QLoRA` `Qwen` `InternVL`

### 🏛️ [HEOGAONv3](https://github.com/Janjonghwa/HEOGAONv3) · AI 인허가 사전 진단

자연어로 창업 계획을 입력하면 주소·건축물대장과 요구사항 그래프를 바탕으로 영업 가능 여부, 필요 서류와 처리 순서를 안내합니다.

> **Result** · SSAFY × KAKAO TECH BOOTCAMP AI Hackathon **103팀 중 본선 6팀 진출**<br/>
> **Design** · 상태 머신 기반 정보 수집 · 근거 중심 진단 · 모바일 우선 `thin client`<br/>
> **Stack** · `FastAPI` `Next.js` `PostgreSQL` `Docker`

### 📈 [Alphapick](https://github.com/ssafy-1-pjt/Alphapick) · 국내 주식 정량 분석

회사 품질·시장 검증·매수 타이밍을 분리해 평가하고, 생성형 AI는 계산 결과를 설명하는 역할로 제한한 종목 스크리너입니다.

> **Role** · Team Lead / FE / AI — AI 코멘트와 헤드라인 연동, UI/UX 설계, 프론트엔드 구현과 기능 통합<br/>
> **Engineering** · 규칙 기반 점수와 생성형 AI 분리 · 외부 장애를 격리하는 배치 수집 → DB → API 구조<br/>
> **Stack** · `Vue 3` `Pinia` `Django` `Python`

## 🛠️ Core Stack

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=python,cpp,pytorch,opencv,ros,linux,ts,docker&perline=4&theme=dark" />
  <source media="(prefers-color-scheme: light)" srcset="https://skillicons.dev/icons?i=python,cpp,pytorch,opencv,ros,linux,ts,docker&perline=4&theme=light" />
  <img src="https://skillicons.dev/icons?i=python,cpp,pytorch,opencv,ros,linux,ts,docker&perline=4&theme=dark" alt="Python, C++, PyTorch, OpenCV, ROS 2, Linux, TypeScript and Docker" />
</picture>

</div>

### AI & Vision

`PyTorch` · `OpenCV` · `YOLO / Ultralytics` · `Hugging Face Transformers` · `PEFT / QLoRA`

### Robotics & Edge

`ROS 2` · `C / C++` · `Linux` · `Jetson / CUDA` · `Qt` · `ESP32` · `MQTT`

### Product Engineering

`TypeScript` · `FastAPI` · `Spring Boot` · `Next.js` · `Vue 3` · `PostgreSQL` · `Prisma` · `Docker`

## 🧩 More Projects

- [**MRJ · 명리재**](https://github.com/Janjonghwa/MRJ) — 결정론적 만세력 계산과 LLM 스토리텔링, 동적 공유 이미지를 결합한 Next.js 서비스
- [**QuadQT**](https://github.com/VEDA-QuadZone/QuadQT) — RTSPS·MQTT·TCP를 연동한 Qt 기반 실시간 영상 감시·관제 데스크톱 애플리케이션

<div align="center">

## 🤝 Connect

프로젝트와 협업 이야기는 언제든 편하게 보내주세요.

<a href="mailto:parkjh1492@naver.com"><img src="https://img.shields.io/badge/Email-parkjh1492%40naver.com-03C75A?style=for-the-badge&logo=naver&logoColor=white" alt="Email parkjh1492@naver.com" /></a>
<a href="https://github.com/Janjonghwa"><img src="https://img.shields.io/badge/GitHub-Janjonghwa-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Janjonghwa" /></a>

<br/><br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:2C5364,50:203A43,100:0F2027&height=120&section=footer&text=From%20silicon%20to%20service.&fontSize=20&fontColor=ffffff&fontAlignY=72&animation=fadeIn" alt="From silicon to service" />

</div>
