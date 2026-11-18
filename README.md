# 안녕하세요, 장준서입니다 🤖

**Physical AI 엔지니어 — 양팔 로봇 매니퓰레이션 · 모방학습(Imitation Learning)**

로봇 하드웨어 설계부터 데이터 수집, 모델 학습, 실물 검증까지 직접 다루며
사람 곁에서 함께하는 로봇을 만듭니다.

[![Portfolio](https://img.shields.io/badge/Portfolio-junseojang--portfolio-0E7490?style=for-the-badge&logo=netlify&logoColor=white)](https://junseojang-portfolio.netlify.app)

---

### 🏅 하이라이트

- 🥇 **동국대 DAPIER 피지컬 AI 부트캠프 최종 프로젝트 대상** (2026.11.04)
  — [HOLD THE FLOW: 이동형 양팔 물 서빙 로봇](https://github.com/jangjunseo05/bimanual-robot/blob/main/README.md) · 2인 팀, **팔 조작(모방학습) 담당**
  - 텔레옵 데이터 80+80개 수집, ACT · SmolVLA · π0 · GR00T 모델 32개 학습
  - 학습 손실이 아닌 실물 5회 연속 시험으로 최종 모델 선정 (SmolVLA **5/5**)
  - 안전 래퍼 5종과 로봇 탑재 노트북 로컬 추론으로 웹 주문 → 물따르기 → 서빙 → 도크 복귀 미션에 통합
- 🏆 **NVIDIA Agentic AI Hackathon 2026 최종 결선 TOP 5** (Team Mollet)
  — NVIDIA AI Day Seoul 2026 결선 무대 발표 (2026.11.10)
  - [RL Triage Agent](https://github.com/jangjunseo05/rl-triage-agent/blob/main/README.md): Isaac Lab 강화학습 실패 진단 에이전트 — 재현성 검증 · 결선 발표 담당
  - [한글동행](https://github.com/jangjunseo05/hangul-donghaeng/blob/main/README.md): 카메라로 랜드마크를 인식해 음성으로 안내하는 여행 에이전트

---

### 🦾 로봇 프로젝트 — 세미 휴머노이드를 단계적으로

| 단계 | 프로젝트 | 내용 |
|---|---|---|
| STEP 1 | [커스텀 4축 리더암](https://github.com/jangjunseo05/custom-4dof-leader-arm/blob/main/README.md) | SG90 서보를 개조해 관절 각도를 읽는 저비용 리더암 제작, MuJoCo real-to-sim 텔레옵 |
| STEP 2 | [SO-101 모방학습 대시보드](https://github.com/jangjunseo05/so101-il-dev-toolkit/blob/master/README.md) | 수집 → QA → 학습 → 추론을 하나의 웹 대시보드로, ACT 정책 MuJoCo 검증 |
| STEP 3 | [세미 휴머노이드 모바일 매니퓰레이터](https://github.com/jangjunseo05/semi-humanoid-mobile-manipulator/blob/main/README.md) | Gazebo에서 URDF · SLAM · Nav2 · YOLO+뎁스 · 해석적 IK 통합 — 멀리서 찾은 가방까지 접근해 팔 접촉, 같은 시작 위치 10/10 (시뮬레이션, 접촉 센서 확인) |

### 🧠 로봇 이전의 AI 연구

| 분야 | 프로젝트 | 결과 |
|---|---|---|
| 의료 AI (동국대 AIM Lab) | [커프리스 혈압 추정](https://github.com/jangjunseo05/bp-estimation/blob/main/README.md) · [PPG 부정맥 분류](https://github.com/jangjunseo05/ppg-abnormality-classification/blob/main/README.md) | MAE 4.87 / 4.25 mmHg · AUC 0.83 |
| 정신건강 AI (성균관대 LAMDA Lab) | [MindTrekking 코어 시스템](https://github.com/jangjunseo05/mindtrekking-core-system/blob/main/README.md) | MBCT 기반 청소년 디지털 치료 게임(Unity), IITP 과제 제안 선정 |
| LLM | [GPT-2 멀티태스크 NLP](https://github.com/jangjunseo05/nlp-multitask/blob/main/README.md) | GPT-2 직접 구현, LoRA · 각운 손실 등 과제별 개선 |

---

### 🛠️ 기술 스택

**로봇 학습 · 로보틱스**<br>
![LeRobot](https://img.shields.io/badge/LeRobot-FFD21E?style=flat&logo=huggingface&logoColor=black)
![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=flat&logo=ros&logoColor=white)
![MuJoCo](https://img.shields.io/badge/MuJoCo-1F6FEB?style=flat)
![Gazebo](https://img.shields.io/badge/Gazebo-F58113?style=flat)
![Isaac Lab](https://img.shields.io/badge/Isaac_Lab-76B900?style=flat&logo=nvidia&logoColor=white)

**ML / AI**<br>
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers-FFD21E?style=flat&logo=huggingface&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-111F68?style=flat)

**하드웨어 · 언어 · 도구**<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C/C++](https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=flat&logo=cplusplus&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat&logo=arduino&logoColor=white)
![Fusion 360](https://img.shields.io/badge/Fusion_360-FF6B00?style=flat&logo=autodesk&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat&logo=anthropic&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-412991?style=flat)

---

### 🧭 지금과 다음

| | |
|---|---|
| 🎯 관심 직무 | 로봇 매니퓰레이션 · VLA · 모방학습 · 로봇 데이터 수집 / 품질 관리 |
| 🎓 학력 | 동국대학교 컴퓨터·AI학과 (편입, GPA 3.68/4.5) · 동국대 DAPIER 피지컬 AI 부트캠프 수료 |
| 📚 먼저 볼 곳 | [포트폴리오](https://junseojang-portfolio.netlify.app) · [양팔 서빙 로봇](https://github.com/jangjunseo05/bimanual-robot/blob/main/README.md) · [SO-101 대시보드](https://github.com/jangjunseo05/so101-il-dev-toolkit/blob/master/README.md) · [RL Triage Agent](https://github.com/jangjunseo05/rl-triage-agent/blob/main/README.md) |

---

### 📫 연락처

[![Email](https://img.shields.io/badge/Email-jangjunseo05%40naver.com-03C75A?style=flat-square&logo=naver&logoColor=white)](mailto:jangjunseo05@naver.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-jangjunseo05-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jangjunseo05)
[![Portfolio](https://img.shields.io/badge/Portfolio-Netlify-0E7490?style=flat-square&logo=netlify&logoColor=white)](https://junseojang-portfolio.netlify.app)
