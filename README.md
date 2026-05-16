# [중소기업 전산 담당자를 위한 NemoClaw 실무 운영 커리큘럼]

![NemoClaw School](https://img.shields.io/badge/NemoClaw-School-green?style=for-the-badge)
![AI Agent](https://img.shields.io/badge/AI-Agent-orange?style=for-the-badge)

**NemoClaw 실전 운영 입문: OpenClaw를 더 안전하게 실행하고 자동화하는 4시간**

## 🚀 과정 소개

이 과정은 OpenClaw를 이미 사용해 보았거나 도입을 고려 중인 사용자를 위해, NVIDIA OpenShell 기반의 NemoClaw를 활용하여 안전하고 효율적인 AI 에이전트 운영 환경을 구축하는 방법을 다룹니다. 단순히 기능을 익히는 것을 넘어, 보안 정책과 운영 체크리스트를 통해 실제 업무에 적용 가능한 수준의 에이전트 설계를 목표로 합니다.

## 📚 커리큘럼 구성 [중소기업 전산 담당자를 위한 NemoClaw 실무 운영 커리큘럼]

| 차시 | 주제 | 핵심 내용 | 상세 링크 |
| :--- | :--- | :--- | :--- |
| **1차시** | **안전한 샌드박스 구축** | 에이전트 보안 위협 이해, 4계층 아키텍처, `nemoclaw onboard` 설치, 텔레그램 보안 설정 | [바로가기](./1차시.md) |
| **2차시** | **통제 및 트러블슈팅** | 4대 정책 도메인, L7 통제 설계, Headless 서버 관리(SSH 포워딩), CLI 및 파일 기반 문제 해결 | [바로가기](./2차시.md) |
| **3차시** | **워크플로우 및 다중 에이전트** | 미션 컨트롤(DB) 구축, 7대 핵심 두뇌 파일 세팅, 3계층 협업 프레임워크 설계 | [바로가기](./3차시.md) |
| **4차시** | **비용 최적화 및 로컬 RAG** | 로컬 RAG 파이프라인, 티어 기반 모델 라우팅, 토큰 최적화, 안전한 환경 재구축 가이드 | [바로가기](./4차시.md) |

## 🛠 주요 기술 스택

- **Platform:** [NemoClaw](https://github.com/OpenClaw) (OpenClaw plugin for NVIDIA OpenShell)
- **Runtime:** NVIDIA OpenShell (Secure Sandbox Environment)
- **Inference:** Open Source Models & Model Routing
- **Integration:** Telegram, Slack, Discord, Maton API

## 💻 시작하기

1. 이 저장소를 클론합니다.
2. `1차시.md`부터 순서대로 학습을 진행하며 본인의 업무 자동화 분류표를 작성합니다.
3. 각 차시별 실습 결과물을 저장소에 기록하여 본인만의 운영 정책을 완성합니다.

---

> "모든 것을 자동화하는 것이 아니라, 위험한 실행을 검토 가능하게 만드는 것이 진정한 에이전트 운영입니다."
