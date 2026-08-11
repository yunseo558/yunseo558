## 🚀 Featured Projects

### 📬 DAP — Department Automation Pipeline

> **Gmail → AI Extraction → Human Review → Google Calendar**

이메일로 반복적으로 전달되는 일정·마감 정보를 감지하고,  
구조화·검토한 뒤 Google Calendar에 자동 등록하는 업무 자동화 파이프라인입니다.

- Gmail Pub/Sub 기반 신규 메일 감지
- 자연어 이메일에서 일정·마감 정보 구조화
- Confidence 기반 Human-in-the-loop 검토
- Google Calendar 자동 등록
- 마감 키워드 우선순위 기반 날짜 추출 로직 개선
- Windows / macOS Cross-platform 환경 이슈 대응

**Tech**  
`Python` `Gmail` `Google Calendar` `Pub/Sub` `Streamlit` `Claude`

👉 [Repository](https://github.com/DAP-MJU/dap-comp)

---

### 🔐 CofferGate — Policy-Gated AI Agent

> **LLM Proposal → Policy Gate → KMS Signing → On-chain Execution**

AI Agent가 자산 운용처럼 되돌리기 어려운 작업을 수행할 때,  
**AI의 판단과 실제 실행 권한을 분리**하기 위한 Policy-Gated Agent를 구현했습니다.

- LLM은 실행이 아닌 구조화된 제안만 생성
- 자산 종류·금액·건별/일별 한도를 결정론적 Policy Gate로 재검증
- 정책 위반 요청의 KMS 서명 및 트랜잭션 제출 사전 차단
- Google Cloud KMS 기반 Signing Flow 구현
- Solana Devnet 기반 SPL Token Transaction 제출
- 성공 / 정책 위반 실패 시나리오 모두 구현
- Transaction Signature와 Confirmed 상태 기반 실행 결과 검증

**Tech**  
`Google Cloud` `Cloud KMS` `Cloud Run` `Solana` `SPL Token` `LLM`

👉 [Backend](COFFERGATE_BACKEND_URL) · [Frontend](COFFERGATE_FRONTEND_URL)

---

### 💳 BizCred — Explainable AI Credit Product

> **Data → AI Score → Explanation → Human Review → Action**

비금융 데이터를 활용한 소상공인 신용평가 결과를  
단순한 점수 화면이 아니라 **금융 심사 업무 흐름 전체**로 연결한 인터랙티브 프로토타입입니다.

- 데이터 동의 → 신용평가 → 상품 신청 → 심사 → 사후관리 Flow 설계
- BizCred Score · Prediction Confidence · Data Quality UX 구현
- SHAP 기여도를 사용자 친화적인 설명으로 재구성
- 데이터 충분도·신뢰도 기반 Human-in-the-loop 분기 설계
- 조건부 승인·추가서류 요청·부결 등 심사 결과별 다음 행동 설계
- 30·60·90일 개선 코칭 및 조기경보 모니터링 UI 구현

**Tech**  
`React` `TypeScript` `Vite` `Tailwind CSS`

---

### ♿ 요지(要旨) — Accessible Information Product

> **STT → LLM Extraction → Validation → Human Review → Accessible UI**

공공기관 영상에 포함된 지원 정보를  
장애 사용자가 필요한 정보 단위로 빠르게 확인할 수 있도록 재구성한 디지털 접근성 서비스입니다.

- STT → LLM 추출 → 규칙 검증 → 사람 검수 파이프라인 설계
- 신청 기간·지원 대상·준비 서류·문의처 등 정형 정보 구조 정의
- 날짜·연락처 등 명확한 항목의 규칙 기반 이중 검증 구조 설계
- 추출 결과와 원본 영상 Timestamp 연결
- 지체·시각·청각장애 사용자를 고려한 접근성 UX 설계
- 팀장으로 문제 정의, 유사 서비스 분석, 기능 우선순위 및 기술 구조 총괄

**Role**  
`Team Lead` `AI Product Design` `Frontend Prototype`

---

## 🧩 How I Build AI Products

제가 여러 프로젝트에서 반복적으로 다뤄온 구조는 비슷합니다.

<pre>
Input / Event
      ↓
Structuring
      ↓
AI / Rule-based Decision
      ↓
Validation
      ↓
Human / Policy Gate
      ↓
Execution
      ↓
Trace & Feedback
</pre>

AI가 답을 생성하는 것에서 끝나는 것이 아니라,  
**판단 결과가 실제 서비스의 다음 행동으로 이어지는 구조**를 만드는 데 집중합니다.

특히 다음 원칙을 중요하게 생각합니다.

- **Human-in-the-loop** — AI가 불확실할 때 사람이 최종 판단
- **Policy-Gated Execution** — 실행 전 결정론적 정책으로 재검증
- **Explainable UX** — 결과와 함께 근거·신뢰도·데이터 출처 제공
- **Fail-safe Interaction** — 확인·수정·차단·Undo가 가능한 흐름
- **Prototype-first** — 필요한 경우 모델보다 사용자 흐름과 제품 가설부터 검증

---

## 🛠 Tech Stack

### Languages
`Python` `TypeScript` `JavaScript`

### Frontend
`React` `Vite` `Tailwind CSS` `Framer Motion` `Streamlit`

### AI & Automation
`Claude` `Web Speech API` `Prompt Engineering`  
`Rule-based NLU` `Human-in-the-loop Workflow`

### Cloud & Infrastructure
`Google Cloud Platform` `Pub/Sub` `Cloud Run` `Cloud KMS`  
`OAuth 2.0` `Google Workspace`

### Blockchain
`Solana Devnet` `SPL Token`

### Automation & Dev Tools
`Git` `GitHub` `Playwright` `Chrome DevTools Protocol` `FFmpeg`

---

## 🧪 Other Projects

### 📅 Fore
음성 명령을 일정 액션으로 변환하고,  
고정 일정 변화에 따라 준비·이동·여유 시간을 다시 계산하는 일정 프로토타입.

`React` `TypeScript` `Web Speech API` `Rule-based NLU`

### ⚖️ Anchor
비정형 서비스 가격을 비교하고,  
판정 근거·확인 질문·사용자 검증을 결합한 Human-in-the-loop 가격 판단 프로토타입.

`React` `TypeScript` `Human-in-the-loop UX`

### 🧾 DigiWill
금융자산 연동부터 디지털 유언, 법적 리스크 검증,  
사망 확인, 수혜자 전달, 상속 절차 안내까지 연결한 디지털 상속 서비스 설계 프로젝트.

`Product Design` `Workflow Design` `AI Feature Design`

---

## 🎯 Areas of Interest

- AI Product Engineering
- AX / Workflow Automation
- LLM-powered Applications
- Human-in-the-loop Systems
- AI Agent Safety & Execution Control
- Full-stack Product Development

---

### Contact

GitHub: [yunseo558](https://github.com/yunseo558)
