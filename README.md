# AI Product & Workflow Automation

입력을 구조화하고, AI·규칙 기반 판단을 검증한 뒤  
실제 행동으로 연결하는 제품 흐름을 설계하고 구현합니다.

---

## Featured Projects

### DAP — Department Automation Pipeline

`Gmail → Email Parsing → Event Extraction → Google Calendar`

이메일에서 일정 정보를 추출해 Google Calendar 등록까지 연결한 업무 자동화 파이프라인입니다.

- Gmail 신규 메일 감지와 메시지 단위 처리
- MIME·HTML·Base64 이메일 본문 파싱
- 날짜·시간 추출 및 Calendar Event 변환
- 개별 메시지 오류 격리와 Windows·macOS 실행 환경 대응

`Python` `Gmail` `Google Calendar` `Google Workspace CLI`

[Repository](https://github.com/DAP-MJU/dap-comp)

---

### CofferGate — Policy-Gated AI Agent

`LLM Proposal → Policy Validation → KMS Signing → On-chain Execution`

AI가 실행안을 제안하되, 실제 실행 권한은 결정론적 정책과 서명 계층이 통제하도록 설계한 에이전트 시스템입니다.

- LLM의 제안과 실제 실행 권한 분리
- 자산 종류·금액·건별·일별 한도 검증
- 정책을 통과한 요청에만 Cloud KMS 서명 허용
- Solana Devnet 실행 결과와 정책 차단 근거 확인

`TypeScript` `Google Cloud KMS` `Cloud Run` `Solana` `SPL Token`

[Backend](https://github.com/CofferGate/CofferGate_backend) · [Frontend](https://github.com/CofferGate/CofferGate_frontend)

---

### BizCred — Credit Review Workflow Prototype

`Consent → Assessment → Explanation → Human Review → Follow-up`

소상공인 신용평가 결과가 실제 심사와 후속 행동으로 이어지는 흐름을 검증한 프론트엔드 프로토타입입니다.

- 데이터 동의부터 상품 신청·심사·사후관리까지 전체 흐름 설계
- 점수·신뢰도·데이터 품질과 평가 요인별 설명 UI
- 데이터 충분도에 따른 평가 방식과 심사역 검토 분기
- 심사 결과별 후속 행동과 30·60·90일 코칭·조기경보 UI

`React` `TypeScript` `Vite` `Tailwind CSS`

---

### 요지(要旨) — Accessible Information Prototype

`STT → Information Extraction → Validation → Human Review → Accessible UI`

공공기관 영상 속 지원 정보를 장애 사용자가 필요한 항목 단위로 확인할 수 있도록 재구성한 접근성 서비스 프로토타입입니다.

- STT·LLM 추출·규칙 검증·사람 검수를 결합한 파이프라인 설계
- 신청 기간·지원 대상·준비 서류·문의처를 위한 정보 구조 정의
- 추출 결과와 원본 영상 Timestamp 연결
- 지체·시각·청각장애 사용자를 고려한 접근성 UX 설계

`Team Lead` `Product & System Design` `Frontend Prototype`

---

## How I Build

`Input / Event → Structuring → Decision → Validation → Human / Policy Gate → Execution → Trace`

AI의 응답 자체보다 판단 결과가 실제 서비스의 다음 행동으로 이어지는 구조에 관심이 있습니다.

- **Human-in-the-loop** — 불확실한 판단은 사람이 확인
- **Policy-gated execution** — 실행 전 결정론적 규칙으로 재검증
- **Explainable, fail-safe UX** — 근거를 보여주고 수정·차단할 수 있는 흐름

---

## Tech Stack

**Languages**  
`Python` `TypeScript` `JavaScript`

**Frontend**  
`React` `Vite` `Tailwind CSS` `Streamlit`

**AI & Automation**  
`LLM Integration` `Google Workspace` `Web Speech API` `Rule-based NLU`

**Cloud & Infrastructure**  
`Google Cloud Platform` `Cloud Run` `Cloud KMS` `OAuth 2.0`

**Blockchain**  
`Solana` `SPL Token`

---

## Additional Projects

**Fore** — 음성 명령과 일정 변화를 반영해 준비·이동·여유 시간을 다시 계산하는 일정 프로토타입  
`React` `TypeScript` `Web Speech API`

**Anchor** — 판정 근거·확인 질문·사용자 검증을 결합한 가격 비교 프로토타입  
`React` `TypeScript` `Human-in-the-loop UX`

**DigiWill** — 금융자산 연동부터 디지털 유언과 상속 절차까지 연결한 서비스 설계 프로젝트  
`Product Design` `Workflow Design` `AI Feature Design`

---

## Contact

📧 [Email](mailto:yunseo0154@naver.com)
