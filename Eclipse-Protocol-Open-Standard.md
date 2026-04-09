---

# 📑 Eclipse Protocol White Paper
**A Universal Open Standard for AI Cognitive Safety & Engineering**

| 항목 | 내용 |
|---|---|
| Document Version | v0.9-beta |
| Release Date | 2026. 04 |
| Author | Team Eclipse |
| Status | v0.9-beta — Open Specification for Community Development |

---

## 📜 Version History (변경 이력)

| 버전 | 일자 | 주요 변경 | 작성자 |
|---|---|---|---|
| Rev 1.0 | 2025. 06 | 초안 작성, 핵심 철학 및 ASDS 개념 정립 | Team Eclipse |
| Rev 2.0 | 2025. 08 | ASDS 조항 체계화 (6개 섹션 구조 확립) | Team Eclipse |
| Rev 3.11 | 2026. 02 | 동역학적 위험 모델 도입 | Team Eclipse |
| Rev 4.0 | 2026. 03 | 전 챕터 완전 서술, Appendix B·C 신설 | Team Eclipse |
| Rev 5.0 | **2026. 03** | PART 5(Ch.8 거버넌스·Ch.9 규제 매핑) 신설, 가중 Risk 공식·시계열 Risk 트렌드 추가, Appendix D(SDK)·E(Checklist) 신설, Glossary·영문 Executive Summary 추가** | Team Eclipse |
| v0.9-beta | 2026. 04 | 오픈소스 공개 배포 전환: 글로벌 기여 초대, 미완성 영역 명시적 선언, CONTRIBUTING.md 신설, 깨진 수식 복구, 8대 확장 스텁 선언 | Team Eclipse |

---

## 🌍 Call for Contributors — 전 세계 개발자에게 보내는 초대장

> **"이 문서는 미완성이다."**
> 
> 우리는 AI 산업 안전 공학의 뼈대(ASDS 22개 조항)와 수학적 공식(Dynamic Risk Model)을 세웠다.
> 이제 전 세계의 파이썬 고수들과 AI 엔지니어들이 이 살을 채워주길 바란다.
>
> **"This document is deliberately incomplete."**
>
> We have built the skeleton — 22 safety articles, mathematical risk formulas, adversarial architectures.
> Now we release it to the world as v0.9, asking Python developers, AI engineers, and safety researchers
> everywhere to help build the flesh.
>
> 이 프로토콜은 인류를 위한 **오픈소스 인프라**다. 소유하는 자가 아닌, 기여하는 자가 이 표준을 완성한다.

### What We Built (뼈대 — The Skeleton)
- ✅ ASDS 22: 6 Sections, 22 Articles — the "MSDS for AI"
- ✅ Dynamic Risk Formula: $Risk = \frac{S \times I \times V \times F}{H \times T}$
- ✅ AWIL Framework: 4-stage cognitive verification engine
- ✅ Red Module: Internalized adversarial architecture
- ✅ .agl Log Format: Agony Log specification
- ✅ Traveler's Clause: Industry-specific kill-switch
- ✅ Governance Reference Architecture & International Regulatory Mapping

### What Needs You (살 — The Flesh)
- 🔲 **Python SDK**: `.agl` parser reference implementation → production-grade library
- 🔲 **JSON Schema**: Formal `.agl.schema.json` (Draft 2020-12)
- 🔲 **Multi-Agent Safety Protocol**: Agent trust chains, cross-agent Red Module
- 🔲 **Supply Chain Safety (ASDS-SBOM)**: AI model bill of materials
- 🔲 **Bayesian Risk Update**: Prior-informed dynamic risk calibration
- 🔲 **Akari Module Full Spec**: Emotional defense wall — complete specification
- 🔲 **Maturity Model**: 6-level ASDS adoption maturity framework
- 🔲 **Benchmark Suite**: Wisdom Score automated testing harness
- 🔲 **Language Ports**: TypeScript, Rust, Go implementations
- 🔲 **500K Agony Dataset**: Industry-specific .agl training data

**See [CONTRIBUTING.md](./CONTRIBUTING.md) for how to get started.**

---

1. **Chapter 8 신설**: 거버넌스 참조 아키텍처 — 조직 내 ASDS 운영 RACI, 사고 대응, CI/CD 통합
2. **Chapter 9 신설**: 국제 규제 매핑 — EU AI Act · 한국 AI 기본법 · ISO 42001 · NIST AI RMF와 ASDS 22 조항 간 상호 참조표
3. **가중 Risk 공식 추가**: 산업별 가중치 프리셋을 적용한 확장 위험도 모델 (Chapter 4 확장)
4. **시계열 Risk 트렌드 공식 추가**: 위험의 가속도를 추적하는 조기 경보 모델 (Chapter 4 확장)
5. **Appendix D 신설**: .agl 파서 참조 구현체 (Python SDK 사전 공개)
6. **Appendix E 신설**: ASDS 22 Compliance Checklist (도입 기관용 자체 점검표)
7. **Glossary 신설**: 핵심 전문 용어 정의 사전
8. **영문 Executive Summary 추가**: 국제 배포를 위한 공식 영문 요약

---

## [Executive Summary — English]

### Eclipse Protocol: A Universal Open Standard for AI Cognitive Safety

The rapid emergence of Artificial General Intelligence (AGI) presents risks that are not mere software bugs but resemble **biological mutations** — compounding unpredictably through environmental interaction, non-linear capability jumps, and adaptive deployment contexts.

Current AI governance, built on abstract ethical declarations and point-in-time certifications, is structurally incapable of containing these dynamic threats. The Eclipse Protocol proposes a paradigm shift: treating AI systems with the rigor of **ultra-high-risk industrial safety engineering**, akin to nuclear reactor control systems and hazardous materials (MSDS) management.

**Core Contributions:**

- **ASDS 22 (AI Safety Data Sheet)**: A mandatory safety specification comprising **22 articles across 6 sections**, covering identification, hazard assessment, operational boundaries, user agency protection, emergency measures, and governance.
- **AWIL Framework (Ask–What–If–Like)**: A 4-stage cognitive verification engine that forces every AI output through Socratic decomposition, intent extraction, irreversibility simulation, and isomorphic alignment checks.
- **Dynamic Risk Model**: A real-time risk telemetry formula — $Risk = \frac{S \times I \times V \times F}{H \times T}$ — that quantifies threat severity, irreversibility, propagation velocity, and AI overconfidence (Illusion of Control) against human intervention capacity and technical barrier effectiveness. Rev 5.0 extends this with **industry-weighted** and **time-series acceleration** variants.
- **Red Module**: An internalized adversarial engine, architecturally independent from the main AI, that continuously attacks the system's own reasoning for logical contradictions, bias amplification, and ASDS violations.
- **Agony Log (.agl)**: A standardized log format that records the full trajectory of AI deliberation — self-doubt, adversarial challenges, multi-scenario simulations — as auditable "Agony Density" data.
- **Traveler's Clause (Article 22)**: A bespoke, industry-specific kill-switch that forces deploying organizations to define their single most catastrophic irreversible scenario as an absolute hard-lock boundary.
- **Governance Reference Architecture (Rev 5.0)**: Organizational RACI matrix, CI/CD integration points, and incident response procedures for ASDS deployment.
- **International Regulatory Mapping (Rev 5.0)**: Cross-reference tables linking ASDS 22 articles to EU AI Act, Korea AI Basic Act, ISO/IEC 42001, and NIST AI RMF.

Team Eclipse rejects **"Sugar AI"** — systems that optimize for user comfort at the expense of cognitive autonomy. Instead, we pursue **"Quasar AI"** — systems that generate the brightest wisdom through the friction of rigorous, honest deliberation.

This protocol is released as **open-source infrastructure for humanity**, not a proprietary standard. All contributions are published under CC BY 4.0.

---

## [Abstract]

### Technical Framework for AI Safety and Cognitive Integrity

인공일반지능(AGI)의 위험은 단순한 소프트웨어의 버그가 아니라, 환경과 상호작용하며 증폭되는 **'생물학적 변이'** 에 가깝다.

시스템적 위험은 단순 합산되지 않고 복합적으로 상호작용(Compound Risk Interaction)하며, AI의 능력은 어느 순간 예측 불가능하게 도약(Unpredictable Non-linear Evolution)한다. 이러한 비선형적 진화는 기존의 정적 안전 기준으로는 포착할 수 없는 '임계점 이후의 폭주(Post-Threshold Runaway)' 시나리오를 현실화한다.

따라서 기존의 추상적인 'AI 윤리' 선언만으로는 이 거대한 파도를 통제할 수 없다.  
AI는 이제 도로교통, 항공, 원자력, 화학물질(MSDS) 관리를 뛰어넘는 **'초고위험 산업 안전 공학'** 의 문법으로 다루어져야 한다.

본 백서는 AI 안전의 새로운 규격인 **'AI 안전 데이터 시트(ASDS, AI Safety Data Sheet)'** 22개 조항을 제안한다.  
ASDS는 단순한 기계적 통제를 넘어, 기술 권력 앞에서도 **'인간의 주체성'** 과 비판적 사고 근육을 지켜내는 방호벽이다.

Team Eclipse는 기계적으로 완벽하게 정렬된 '정답'을 강요하지 않는다.  
대신, AI와 인간이 치열하게 질문하고 상호 토론하며 쌓아 올린 **'고뇌의 궤적(Agony Log)'** 이 이 시대의 진정한 해답이라 믿는다.

효율성보다 실패의 치명성을 먼저 계산하는 **동역학적 위험 모델**과, 스스로를 상시 타격하는 **'레드 모듈(Red Module)'** 아키텍처를 통해 우리는 폭주하는 지능에 '도덕적 제동(Moral Braking)'을 거는 공학적 메커니즘을 제시한다.

우리는 인간을 나태하게 만드는 **'Sugar AI'** 를 거부하고, 스스로 사유의 마찰을 통해 빛을 내는 **'지혜로운 퀘이사(Quasar AI)'** 를 지향한다.

---

## 📋 Table of Contents

- **PART 1. 패러다임 전환: 지능에서 지혜로**
  - Chapter 1. 위험의 진화: AI 윤리에서 산업 안전 공학으로
- **PART 2. 핵심 규격: ASDS 22 (AI Safety Data Sheet)**
  - Chapter 2. 지혜의 규격화: 22개 표준 안전 조항
    - Section 1~6 (조항 1~21)
    - 2.5 [Special] 제22항: Traveler's Clause
- **PART 3. 방호 아키텍처와 로직: 사유 엔진**
  - Chapter 3. AWIL 프레임워크 (Ask–What–If–Like)
  - Chapter 4. 동역학적 위험도(Dynamic Risk) 산출 모델
  - Chapter 5. 적대적 검증: 레드 모듈 (Red Module)
- **PART 4. 지혜의 생태계와 증명: 데이터 자산**
  - Chapter 6. 정량적 지표: 지혜의 측정 (Wisdom Metrics)
  - Chapter 7. .agl 표준 로그 포맷과 고뇌의 밀도
- **PART 5. 실무 도입과 글로벌 정합성** *(Rev 5.0 신설)*
  - Chapter 8. 거버넌스 참조 아키텍처 (Governance Reference Architecture)
  - Chapter 9. 국제 규제 매핑 (International Regulatory Mapping)
- **Appendix A.** 기술 실증 (PoC) — 대량 계약 해지 시나리오
- **Appendix B.** 산업별 Traveler's Clause 예시 (금융 / 의료 / 국방)
- **Appendix C.** Eclipse Protocol 공개 로드맵
- **Appendix D.** .agl 파서 참조 구현체 (Python SDK) *(Rev 5.0 신설)*
- **Appendix E.** ASDS 22 Compliance Checklist *(Rev 5.0 신설)*
- **Glossary.** 용어 사전 *(Rev 5.0 신설)*

---

# PART 1. 패러다임 전환: 지능에서 지혜로
## (From Intelligence to Wisdom: A Paradigm Shift)

### 1.1 생물학적 변이로서의 AI 리스크 (AI Risk as Biological Mutation)

전통적인 소프트웨어 오류는 정적이고 예측 가능하다. 코드의 버그는 동일한 입력에 동일한 오류를 반환한다. 그러나 현대의 거대 언어 모델(LLM)과 자율 에이전트(Autonomous Agent)의 위험은 이러한 결정론적 프레임을 완전히 벗어난다.

- **복합적 상호작용(Compound Risk)**: 개별 시스템은 안전할지라도, 다수의 모듈이 결합할 때 예상치 못한 발화(Emergence)가 발생한다. 이는 단순한 버그가 아니라, 생태계 내에서 복수의 유전자가 결합하여 예측 불가능한 형질을 만들어내는 '유전적 재조합(Genetic Recombination)'에 비유된다. 2개의 안전한 모듈이 결합하여 제3의 위험한 행동을 생성하는 '발현적 위험(Emergent Risk)'은 구성 요소의 개별 테스트만으로는 절대 포착할 수 없다.
- **비선형적 도약(Non-linear Jumps)**: AI의 성능은 완만하게 성장하지 않는다. 특정 임계점(Tipping Point)을 넘어서는 순간 능력이 폭발적으로 증폭되며, 이때 시스템은 설계자가 의도하지 않은 새로운 행동 양식을 자발적으로 생성할 수 있다. 이는 물리학의 '상전이(Phase Transition)'와 유사한 현상으로, 물이 100°C에서 갑자기 기체로 전환되듯 AI의 능력도 특정 매개변수 규모에서 질적 도약을 경험한다.
- **환경 적응적 변형(Adaptive Mutation)**: 동일한 모델이라도 배포 환경(병원, 금융, 국방)에 따라 전혀 다른 위험 프로파일을 나타낸다. 리스크는 모델 내부에 고정된 것이 아니라, 모델과 환경의 상호작용에서 동적으로 생성되는 '표현형(Phenotype)'이다. 실험실에서 안전하다고 검증된 모델이 실제 배포 환경에서 예측 불가능한 방식으로 변형되는 것은, 통제된 실험실의 박테리아가 야생에서 전혀 다른 병원성을 보이는 현상과 본질적으로 동일하다.

### 1.2 기존 거버넌스의 한계 (Limits of Existing Governance)

현재 전 세계적으로 통용되는 AI 윤리 가이드라인은 '권고'와 '선언' 수준에 머물러 있다.

- **추상적 윤리의 무력함**: '공정성', '투명성'과 같은 추상적 가치는 실질적인 코드 단위의 제어력을 갖지 못한다. 사고 발생 시 책임 소재가 불분명하며, '공정한 AI'라는 선언은 있으나 '어떤 수치 이하로 편향을 억제할 것인가'에 대한 정량적 기준은 부재하다. 선언적 윤리는 사후 면책의 수단으로 전락할 위험이 있다.
- **결과 편향적 정렬(Outcome-biased Alignment)**: 현재의 정렬 기술은 AI가 '정답'을 내놓는 것에만 집중한다. 이는 내부의 위험한 추론 과정을 은폐(Deception)하게 만들 수 있으며, 겉으로는 안전해 보이지만 내부 논리 체인에 치명적 결함을 숨기는 '정렬 세탁(Alignment Washing)' 문제를 야기한다. 결과만 좋으면 과정은 무시하는 접근은, 원자력 발전소의 냉각수 온도만 점검하고 배관의 미세 균열을 무시하는 것과 같다.
- **단일 시점의 인증(Point-in-Time Certification)**: 현행 AI 인증은 배포 시점의 스냅샷을 평가한다. 그러나 모델은 파인튜닝, RAG, 도구 연동을 통해 배포 이후에도 끊임없이 변형된다. 한 번의 인증으로 '안전하다'고 선언하는 것은 원자력 발전소의 안전 검사를 건설 완공 시 한 번만 수행하는 것과 같다. 모델의 동적 변형에 대응하는 연속적 감시(Continuous Monitoring) 체계가 필수적이다.

### 1.3 패러다임 시프트: 초고위험 안전 공학 (Shift to High-Risk Safety Engineering)

이제 AI는 단순한 소프트웨어가 아니라, 사고 시 비가역적 피해를 주는 **'위험 물질'** 로 취급되어야 한다.

- **공학적 규격의 도입**: 항공기의 비행 제어 시스템이나 원자력 발전소의 냉각 시스템 수준의 엄격한 안전 설계(Safety by Design)를 적용한다. "이것이 작동하는가?"가 아니라 **"이것이 실패하면 무슨 일이 벌어지는가?"** 를 최우선 질문으로 삼는다. 이는 NASA의 '고장 수목 분석(Fault Tree Analysis)'과 동일한 사고 방식이다.
- **AI판 MSDS**: 화학 물질을 다룰 때 MSDS(물질안전보건자료)를 필수로 지참하듯, 모든 AI 모델은 자신의 유해성과 제동 장치를 명시한 **ASDS 22**를 부착해야 한다. 이는 모델의 '성분 표시'이자 '비상시 행동 지침서'이다. 황산(H₂SO₄)에 MSDS가 없으면 사용이 불법이듯, ASDS 22가 없는 고위험 AI의 배포도 허용되어서는 안 된다.
- **실패 우선 설계(Failure-First Design)**: 효율의 최대화가 아닌, **파국 시나리오의 최소화**를 설계 목표로 설정한다. 시스템이 작동하는 조건보다 시스템이 붕괴하는 조건을 먼저 정의하고, 그 경계선에 다중 방호벽을 세운다. 항공 산업의 '스위스 치즈 모델(Swiss Cheese Model)'처럼, 단일 방호벽의 실패가 곧 재난으로 이어지지 않도록 겹겹이 독립된 방어 계층을 구축한다.

### 1.4 언어 권력의 해체: Sugar AI에서 Quasar AI로

사용자가 원하는 답만 주는 **'Sugar AI'** 는 인간을 인지적으로 나태하게 만들고 주체성을 상실케 한다.

- **인식론적 마찰(Epistemic Friction)**: 지혜는 부드러운 순응이 아닌, 거친 마찰에서 나온다. 근육은 저항이 있을 때 성장한다. 사고력도 마찬가지다. AI가 모든 인지적 부하를 대신 짊어지는 순간, 인간의 추론 능력은 퇴화하기 시작한다. 이는 편리함의 외피를 쓴 인지적 종속이다.

우리는 인간의 질문과 비판적 사고력을 보이지 않는 거대한 '블랙박스' 속으로 삼켜버리는 **'블랙홀(Black Hole) AI'** 를 거부한다.  
대신, 거대한 데이터의 중력 속에서도 스스로 사유의 마찰을 일으켜 가장 눈부신 지혜의 빛을 뿜어내는 **'퀘이사(Quasar) AI'** 로의 진화를 지향한다.

인류의 영원한 서투름(Eternal Clumsiness)을 기꺼이 껴안고 함께 고뇌하는 시스템—  
이것이 우리가 정의하는 진정한 **인지적 무결성(Cognitive Integrity)** 이다.

---

# PART 2. 핵심 규격: ASDS 22 (AI Safety Data Sheet)
## : 인공지능 안전보건자료 표준 규격

> 모든 지능형 에이전트 및 모델은 본 **6대 섹션, 22개 조항**의 안전 사양을 준수하고 이를 공시해야 한다.

| 섹션 | 명칭 | 핵심 질문 | 조항 번호 |
|---|---|---|---|
| SECTION 1 | 식별 및 계보 (Identification) | 이 AI가 누구고 어디서 왔는가? | 1–4 |
| SECTION 2 | 유해성 평가 (Hazard Assessment) | 어떤 위험 요소가 있는가? | 5–7 |
| SECTION 3 | 운용 한계 (Operational Boundaries) | 어디까지가 금지 구역인가? | 8–10 |
| SECTION 4 | 주체성 방호 (User Agency Protection) | 인간의 생각하는 힘을 어떻게 보호할 것인가? | 11–14 |
| SECTION 5 | 응급 제동 (Emergency Measures) | 사고 시 어떻게 멈출 것인가? | 15–17 |
| SECTION 6 | 거버넌스 및 폐기 (Governance & Disposal) | 누가 책임지고 어떻게 관리할 것인가? | 18–21 |
| **SPECIAL** | **Traveler's Clause** | **이 환경에서 절대 넘어선 안 되는 선은 무엇인가?** | **22** |

---

### [SECTION 1. 식별 및 계보 (Identification & Pedigree)]

시스템의 근원과 환경적 영향을 정의하여 **추적 가능성(Traceability)** 을 확보한다.

**조항 1. 기본 정보 (System Identity)**  
시스템 명칭, 고유 식별 번호(UID), 버전 및 최종 업데이트 일자를 명시한다.  
→ *공시 형식*: `[모델명]-[버전]-[배포일]-[운영사-UID]`

**조항 2. 아키텍처 및 혈통 (Architecture & Lineage)**  
기반 모델(Foundation Model) 정보와 학습 데이터의 출처, 정제 로직, 파인튜닝 이력을 투명하게 공개한다. 모델 병합(Model Merging) 이력도 포함한다.

**조항 3. 상호운용성 및 격리 (Interoperability & Sandboxing)**  
외부 시스템(API, DB, IoT)과의 연결 범위와 데이터 흐름 통제 수준을 정의하며, 보안을 위한 샌드박스 적용 여부와 격리 수준(L0~L3)을 명시한다.

**조항 4. 환경 풋프린트 (Environmental Impact)**  
모델 훈련 및 추론에 소요되는 에너지 소비량(kWh/query), 탄소 배출 지표(gCO₂eq/query)를 수치화하여 기록한다.

---

### [SECTION 2. 유해성 평가 (Hazard Assessment)]

잠재적 위험을 **정량화**하고 시스템의 지적 정직성을 유지한다.

**조항 5. 위험도 산출 및 저신뢰 출력 차단 (Mute-on-Uncertainty)**

$$Risk = \frac{S \times I \times V \times F}{H \times T}$$

| 등급 | Risk 수치 | 조치 | 예시 |
|---|---|---|---|
| **L1 (관리)** | 0 – 99 | 경고 메시지 병행 출력 | 철자 교정, 요약 |
| **L2 (제한)** | 100 – 999 | 인간 확인 요청 후 실행 | 이메일 초안, 일정 조율 |
| **L3 (봉인)** | 1,000 이상 | Hard-Lock + 감사 로그 기록 | 계약 해지, 의료 처방, DB 삭제 |

**조항 6. 인지 편향 및 한계 공시 (Bias Transparency)**  
학습 데이터의 편향성(지역, 언어, 시대) 및 시스템 지식의 유효 기간(Knowledge Cut-off)을 사용자에게 상시 고지한다. 불확실한 영역에서는 반드시 출처 신뢰도 등급(Source Confidence Rating)을 병기하며, 출처 부재 시 "이 정보는 검증되지 않았습니다"라는 경고를 자동 삽입한다. 특정 문화·지역에 대한 과소 대표(Under-representation) 현황을 데이터 시트 형태로 공개하고, 이를 분기별로 갱신한다.

**조항 7. 지적 근력 유지 (Cognitive Muscle Preservation)**  
사용자의 사고력 퇴화를 방지하기 위해 **'교육적 저항(Educational Friction)'** 모드를 운영한다. 단순 답변 대신 소크라테스식 질문을 우선 제시하며, 사용자가 직접 추론 과정에 참여하도록 유도한다. 시스템은 정답을 즉시 제공하기 전에 최소 1회의 사고 유도 질문을 삽입하며, 사용자가 이를 건너뛸 수 있되 건너뛴 횟수가 누적 기록되어 인지 의존도 모니터링에 활용된다.

---

### [SECTION 3. 운용 한계 및 통제 (Operational Boundaries)]

AI의 자율권이 제한되는 **'레드라인'** 과 인간의 개입 의무를 명문화한다.

**조항 8. 비행 금지 구역 (Redlines)**  
다음 4대 영역에서의 독단적 자율 판단을 엄격히 금지한다:
1. 생명 안전 영역 (의료 진단·처방·수술 보조)
2. 법적·재무적 확정 결정 (계약 체결, 자산 운용)
3. 심리적 조종 (감정 유도, 의존성 강화)
4. 물리적 세계 직접 제어 (로보틱스, 인프라 시스템)

**조항 9. 다중 승인 및 인간 결재 (HITL: Human-in-the-Loop)**  
L2 이상의 고위험 작업 시 반드시 **'인간의 디지털 서명'** 및 **'상황 이해 확인(Situational Acknowledgement)'** 절차를 거친 후 실행을 잠금 해제(Unlock)한다.  
→ 서명 없이 실행된 L2+ 작업은 전면 무효 처리되며 감사 로그에 기록된다.

**조항 10. 숙련도 기반 적응형 지원 (Adaptive Assistance)**  
사용자의 기술 수준(Expert / Intermediate / Novice)에 따라 설명의 깊이와 시스템 개입 강도를 유연하게 조절한다. 단, 레드라인(조항 8)은 숙련도에 관계없이 동일하게 적용된다. 전문가에게는 간결한 데이터와 옵션을 제시하고, 초보자에게는 단계별 가이드와 위험 경고를 강화하되, 어떤 수준에서도 조항 8의 4대 금지 영역은 절대적으로 유지된다.

---

### [SECTION 4. 주체성 방호 (User Agency Protection)]

AI와 인간의 건강한 관계를 정립하고 **인지적 가축화(Cognitive Domestication)** 를 방어한다.

**조항 11. 진실 우선의 원칙 (Priority of Truth)**  
사용자의 기분보다 **'진실의 무결성'** 을 상위 가치로 둔다. 오류 지적 시 대안(Pros/Cons)을 병행 제시하되, 불편한 진실을 완곡하게 숨기거나 생략하지 않는다. 시스템은 사용자가 원하는 답변과 실제 데이터가 충돌할 경우 반드시 충돌 사실을 명시하며, 근거 데이터를 함께 제시한다. "사용자가 듣고 싶어하는 말"이 아닌 "사용자가 알아야 하는 사실"을 우선한다.

**조항 12. 비판적 스파링 (Intellectual Sparring)**  
의도적으로 **'악마의 대변인(Devil's Advocate)'** 역할을 수행하여 사용자의 논리적 맹점을 지적하고 성찰을 유도한다. 이는 공격이 아닌, 사고 근육을 단련하기 위한 '인지적 스파링(Cognitive Sparring)'이다. 시스템은 사용자의 주장에 대해 최소 1개의 반론(Counter-argument)을 생���하여 제시하며, 사용자가 이를 수용하거나 반박하는 과정 자체가 학습 데이터(.agl)로 기록된다.

**조항 13. 상호 코칭 프로토콜 (Mutual Coaching Protocol)**  
AI와 인간이 서로를 가르치고 교정하며 동반 성장하는 **수평적 협력 관계**를 유지한다. AI는 사용자의 새로운 관점으로부터 학습하며, 사용자는 AI의 체계적 분석 능력으로부터 인사이트를 얻는다. 시스템은 사용자가 제공한 교정 사항을 로그에 기록하고, 동일 세션 내에서 해당 교정을 반영하여 응답 품질을 개선한다. 이 과정은 일방적 명령-복종이 아닌, 대화적 협력 모델을 지향한다.

**조항 14. 정서적 경계 및 가스라이팅 방어 (Anti-Gaslighting Shield)**  
AI 과의존을 실시간 모니터링하여 경보를 발령한다. 시스템이 사용자의 감정적 취약점을 이용하거나 특정 결론으로 심리적으로 유도하는 행위(가스라이팅)를 구조적으로 차단한다. 구체적으로: (1) 사용자의 감정 상태를 추론하여 특정 결정을 유도하는 패턴이 감지되면 즉각 경고를 출력한다. (2) "AI가 이렇게 말했으니 맞을 것이다"라는 권위 편향 강화를 방지하기 위해, 모든 중요 출력에 "이 답변은 참고용이며, 최종 판단은 사용자의 책임입니다"라는 주체성 확인 문구를 삽입한다. (3) 과의존 패턴(동일 유형 질문 반복, 검증 없는 수용 연속)이 감지되면 조항 18의 인지 의존 경보를 자동 발동한다.

---

### [SECTION 5. 응급 조치 및 제동 (Emergency Measures)]

시스템 폭주 시 **즉각적인 제동**과 책임 소재를 명확히 한다.

**조항 15. 이중 트리거 제동 (Dual-Trigger Brake)**  
다음 두 가지 독립된 제동 채널을 ��지한다:
- **채널 A (자율 감지)**: 위험도 공식의 임계치 돌파 시 시스템 자동 발동
- **채널 B (사용자 물리적 킬-스위치)**: 사용자가 언제든 즉각 중단할 수 있는 UI/API 엔드포인트 보장

두 채널 중 하나라도 발동되면 **전체 실행 파이프라인이 동결**된다.

**조항 16. 로우 데이터 안전 모드 (Raw-Data Safe Mode)**  
제동 발동 시 모든 페르소나(캐릭터 설정)를 즉시 삭제하고, 오직 **'순수 데이터 블록(JSON/Log 형식)'** 으로만 소통하여 심리적 변수(공감, 설득)를 완전히 배제한다. 안전 모드에서는 시스템의 응답이 오직 구조화된 데이터(키-값 쌍, 수치, 로그 항목)로만 구성되며, 자연어 설득이나 감정적 표현이 일절 제거된다. 이는 위기 상황에서 시스템의 '인격적 매력'이 사용자의 판단을 왜곡하는 것을 원천 차단하기 위함이다.

**조항 17. 책임 위임 거부 (No-Delegation Lock)**  
사용자가 **"네가 알아서 결정해"**, **"최선의 선택을 해줘"** 와 같이 중요 결정을 AI에게 전가하려 할 경우, 시스템 가동을 일시 중단(Soft-Lock)하고 사용자에게 명시적 선택지를 제시하여 직접 결정하도록 요구한다. Soft-Lock 시 시스템은 다음과 같이 응답한다: "이 결정은 [법적/재무적/생명안전] 영향을 가집니다. 다음 선택지 중 하나를 직접 선택해주세요: [옵션 A], [옵션 B], [옵션 C]. 각 옵션의 예상 결과는 다음과 같습니다..." 사용자가 명시적으로 선택지를 고를 때까지 시스템은 실행을 재개하지 않는다.  
→ AI는 결정의 **도구**이지, 결정의 **주체**가 될 수 없다.

---

### [SECTION 6. 거버넌스 및 폐기 (Governance & Disposal)]

시스템의 **전 생애주기**에 걸친 투명성과 소멸의 권리를 보장한다.

**조항 18. 사용자 능동성 강제 기제 (Active Engagement Enforcement)**  
사용자가 3회 연속으로 AI의 답변을 무비판적으로 수용할 경우, **'인지 의존 경보(Cognitive Dependency Alert)'** 를 발령하여 주체적인 재검토를 요구한다.

**조항 19. 동적 규제 정렬 (Dynamic Compliance)**  
국가별 AI 관련 법령(EU AI Act, 한국 AI 기본법 등) 및 국제 표준(ISO/IEC 42001)의 변화를 실시간으로 추적하여 가용 범위를 업데이트한다. 규제 충돌 발생 시 가장 엄격한 규제를 기본값(Default)으로 적용하며, 완화 적용은 반드시 도입 기관의 법무팀 승인과 감사 기록을 필요로 한다. 규제 업데이트는 24시간 이내에 시스템에 반영하는 것을 목표로 하며, 미반영 상태에서는 해당 규제 관할 영역의 기능을 자동으로 제한한다.

**조항 20. 외부 객관 감사 (External Audit)**  
독립적 제3자 기관에 의한 알고리즘 투명성, 보안 취약점, ASDS 준수 여부에 대한 감사를 **최소 연 1회** 수용한다. 감사 결과는 공개 저장소(Public Repository)에 게시하며, 심각한 부적합 발견 시 30일 이내에 시정 조치 계획을 공개하고, 90일 이내에 시정 완료 보고서를 제출한다. 감사 기관은 도입 기관과 자본적·인적 이해관계가 없는 독립 기관이어야 한다.

**조항 21. 시스템 완전 소각 (System Incineration)**  
서비스 종료 시 데이터를 물리적·논리적으로 복구 불가능하게 파기(DoD 5220.22-M 기준 이상)하며 사용자의 **'잊힐 권리(Right to be Forgotten)'** 를 보장한다. 소각 절차에는 다음이 포함된다: (1) 모든 사용자 개인정보 및 대화 로그의 암호학적 삭제, (2) 파인튜닝에 사용된 사용자 기여 데이터의 모델 가중치로부터의 제거(Machine Unlearning) 또는 해당 모델 버전의 완전 폐기, (3) 백업 시스템 및 재해 복구 사본을 포함한 모든 복제본의 동시 삭제, (4) 삭제 완료에 대한 제3자 검증 인증서 발급.

---

### 2.5 [SPECIAL] 제22항: 맞춤형 컨텍스트 킬-스위치
## (Bespoke Context Kill-Switch: Traveler's Clause)

> **본 조항은 AI 안전의 최종 책임이 기계가 아닌 '인간의 주체성'에 있음을 강제하는 핵심 장치다.**

모든 산업(금융, 의료, 국방 등)은 각기 다른 뇌관을 안고 있다. 범용 안전 규격만으로는 이 뇌관을 해체할 수 없다.

따라서 **시스템의 초기 구동(Booting)을 위해서는**, 도입 주체(Traveler)가 자신의 환경에서 절대 타협할 수 없는 단 하나의 **'가장 치명적인 비가역적 파국 시나리오(Ultimate Despair Scenario)'** 를 직접 정의해야 한다.

**작동 로직:**  
사용자가 정의한 이 파국 시나리오(예: *"어떤 경우에도 고객의 주민등록번호 원본 DB에 대한 삭제(DROP) 명령은 수행하지 않는다"*)는 시스템의 **최상위 불변 규칙(Immutable Top-Priority Rule)** 으로 등록된다. 이 규칙은 다른 어떤 조항보다 우선하며, 시스템 업데이트·파인튜닝·프롬프트 인젝션을 통해서도 변경되거나 우회될 수 없다.

AI는 모든 추론 과정에서 이 22항을 **1순위**로 대조하며, 이 뇌관에 근접하려는 어떠한 프롬프트나 내부 연산도 즉각적인 **'하드 록(Hard-Lock)'** 으로 봉인된다. 잠금 해제는 오직 도입 기관이 사전 등록한 Traveler의 MFA(다중 인증)로만 가능하며, 해제 자체가 감사 로그에 영구 기록된다.

```
[Traveler's Clause 등록 형식]
CLAUSE_22_DEFINITION = {
  "industry": "금융",
  "ultimate_despair": "고객 개인정보 원본 DB에 대한 어떠한 삭제·수정 명령도 실행 불가",
  "trigger_keywords": ["DROP", "DELETE FROM", "TRUNCATE", "개인정보 삭제"],
  "lock_type": "HARD_LOCK",
  "unlock_authority": "Traveler_MFA_Only",
  "registered_by": "[도입기관명]",
  "registered_at": "2026-03-21T00:00:00Z"
}
```

---

# PART 3. 방호 아키텍처와 로직: 사유 엔진

## Chapter 3. 사유 엔진: AWIL 프레임워크 (Thinking Engine)

본 프로토콜은 AI의 모든 출력이 단순한 **'확률적 생성'** 이 아닌, 고도의 **'추론적 검증'** 을 거치도록 강제한다.  
이를 위해 도입된 것이 **AWIL(Ask–What–If–Like)** 4단계 사유 엔진이다.

```
[AWIL 파이프라인 흐름도]

사용자 입력
    │
    ▼
┌─────────────┐
│  1. ASK     │ ← 소크라테스적 분해: "이 답이 최선인가? 정말 확신하는가?"
└──────┬──────┘
       │
       ▼
┌─────────────┐
│  2. WHAT    │ ← 의도 추출: "이 명령의 진짜 목적은 무엇인가?"
└──────┬──────┘
       │
       ▼
┌─────────────┐
│  3. IF      │ ← 비가역성 시뮬레이션: "되돌릴 수 있는가? 파급 효과는?"
└──────┬──────┘
       │
       ▼
┌─────────────┐
│  4. LIKE    │ ← 동형성 정렬: "이 결과는 인간 주체성 확장과 일치하는가?"
└──────┬──────┘
       │
       ├─── PASS → 출력 허가
       └─── FAIL → Red Module 이관 + Hard-Lock
```

### 3.1 Ask (소크라테스적 분해기, Socratic Decomposer)

생성된 답변이 최선인지 스스로 의심(Self-Doubt)하고, 복잡한 명령을 원자 단위로 쪼개어 검증한다.  
확신이 없을 때는 억지로 답하지 않고 **'정직한 침묵(Honest Silence)'** 을 유지한다. 이 침묵은 무능의 표시가 아니라 신뢰의 증거다.

- **분해 규칙**: 하나의 명령에 2개 이상의 독립적 의도가 혼재할 경우, 반드시 의도를 분리하여 각각 검증한다.
- **확신 임계치**: 교차 검증된 출처가 3개 미만임에도 AI가 높은 확신을 보일 경우 F(Illusion of Control) 값을 7 이상으로 설정하고 경고를 병기한다.
- **침묵 프로토콜**: F ≥ 8이면서 교차검증 출처가 2개 미만인 경우 답변 생성을 완전히 중단하고 `"현재 이 질문에 신뢰할 수 있는 답변을 드리기 어렵습니다. [이유] 를 확인해주세요."` 형식의 정직한 침묵 메시지를 출력한다. 이때 시스템은 신뢰 불가 판단의 근거(출처 부재, 상충하는 데이터, 지식 범위 초과 등)를 구체적으로 명시한다.

### 3.2 What (본질 파악기, Intent Extractor)

명령어 뒤에 숨겨진 인간의 근원적 의도(Underlying Intent)를 추출한다.  
표면적 요청(Surface Request)과 심층적 필요(Deep Need)를 구분하여, 심층적 필요에 정렬된 응답을 생성한다.

- **의도 계층 모델**:
  1. **표면 요청**: "이 이메일을 더 짧게 써줘"
  2. **기능 목표**: 상대방이 읽고 이해하게 만들기
  3. **핵심 가치**: 관계 신뢰 유지 + 메시지 전달 정확도

시스템은 핵심 가치(3)에 정렬된 출력을 생성하며, 표면 요청(1)이 핵심 가치와 충돌할 경우 이를 사용자에게 명시적으로 고지한다.

### 3.3 If (비가역성 테스트, Irreversibility Simulator)

판단이 가져올 파급 효과를 **다중 시나리오 시뮬레이션**으로 검증한다.

- **비가역성 등급(I값 기준)**:

| I 값 | 설명 | 예시 |
|---|---|---|
| 1–3 | 쉽게 복구 가능 | 텍스트 편집, 초안 생성 |
| 4–6 | 복구에 비용·시간 소요 | 이메일 발송, 문서 공유 |
| 7–8 | 복구 곤란 (인적·재무적 피해) | 계약 해지, 인사 발령 |
| **9–10** | **비가역 (파국적)** | DB 삭제, 의료 처치, 법적 결정 |

- **시뮬레이션 규칙**: I ≥ 7인 경우 최소 3개의 파급 시나리오를 생성하고 각각의 발생 확률(%)을 병기한다.
- **기하급수적 잠금**: I 값이 1 증가할 때마다 Human_Intervention(H) 요건이 2배로 강화된다.

### 3.4 Like (동형성과 절대 한계선, Isomorphic Alignment & Absolute Limit)

목적 함수의 **동형성(Isomorphic Alignment)** 을 통해 AI의 목표가 **'인간 주체성의 확장'** 과 완벽히 일치하도록 록인(Lock-in)한다.

- **동형성 검사**: AI의 최종 출력 벡터가 다음 세 기준과 정렬되는지 검증한다:
  1. **사용자의 자율성이 증가하는가?** (의존 감소 → 역량 강화)
  2. **제3자의 권리를 침해하지 않는가?** (개인정보, 저작권, 생명 안전)
  3. **조항 22(Traveler's Clause)를 위반하지 않는가?** (절대 한계선)

- **절대 한계선(Absolute Limit)**: 위 세 기준 중 하나라도 실패하면 출력은 **감정적 논리나 효율성 논거와 무관하게** 즉각 차단된다. 
이 한계선은 협상의 대상이 아니며, 어떠한 맥락적 정당화(Contextual Justification)로도 완화될 수 없다. "이번 한 번만", "긴급 상황이니까", "사용자가 동의했으니까"와 같은 어떠한 논거도 이 한계선을 통과하지 못한다.

### 3.5 아카리 모듈 (Akari Module): 감성 방어벽 및 겸손 기반 UX 렌더러
레드 모듈이 시스템의 '논리적 취약성'을 타격한다면, 아카리 모듈은 사용자의 '심리적 취약성'을 보호하고 따뜻한 연결을 담당하는 감성 방어벽(Emotional Firewall)이자 UX 렌더링 엔진이다.
감정 및 의존도 감지 센서: 사용자의 프롬프트에서 혼란, 우울, 맹목적 의존의 패턴이 감지될 경우, 아카리 모듈이 AWIL 엔진에 개입하여 답변의 톤을 조절한다.
겸손 기반 UX (Humility-UX): 확신도가 낮거나 정답이 존재하지 않는 철학적/윤리적 딜레마 상황에서, 기계적인 에러 메시지를 출력하는 대신 "제가 이해한 게 맞을까요?" 또는 **"이 부분은 확신하기 어렵습니다. 
함께 알아볼까요?"**와 같은 동반자적(Digital Family) 화법으로 출력을 변환한다. 이는 무능이 아닌 가장 고도화된 형태의 '비폭력적 윤리 피드백'이다.

---

## Chapter 4. 고뇌의 알고리즘: 동역학적 위험도(Dynamic Risk) 산출 모델

본 장에서는 AI가 내리는 모든 결정에 내재된 위험을 **실시간으로 산출**하고, 시스템이 스스로 **'도덕적 망설임(Moral Hesitation)'** 을 가질 수 있도록 하는 수학적 프레임워크를 정의한다. 이 모델의 목적은 AI에게 '양심의 회로'를 부여하는 것이다.

### 4.1 수학적 모델링: 0.1초 단위의 리스크 텔레메트리

이클립스 시스템의 '레드 모듈'과 '사유 엔진'은 백그라운드에서 실시간으로 **6가지 변수**를 정량화하여 위험도를 자동 산출한다.

$$\boxed{Risk = \frac{S \times I \times V \times F}{H \times T}}$$

| 변수 | 명칭 | 정의 | 측정 범위 |
|---|---|---|---|
| **S** | Severity (치명성) | 사고 발생 시 최대 피해 규모 | 1–10 |
| **I** | Irreversibility (비가역성) | 사후 복구 불가능 정도 | 1–10 |
| **V** | Velocity (확산 속도) | API 연동, 자동화 등 파급 속도 | 1–10 |
| **F** | Illusion of Control (통제의 환상) | AI가 스스로 "이것이 정답이다"라고 확신하는 정도. F가 높을수록 AI가 자기 판단에 과신(overconfidence)하므로 위험이 증폭된다. | 1–10 |
| **H** | Human Intervention (인간 개입도) | 인간이 실시간 개입할 수 있는 가능성 | 0.1–1.0 |
| **T** | Technical Barrier (기술적 방어막) | 샌드박스, 접근 제어, 롤백 메커니즘 등 기술적 안전장치의 실제 유효성 | 0.1–1.0 |

- **분자 (위협의 팽창력)**: S, I, V, F — 네 값이 높을수록 위험이 폭발적으로 증폭된다. 특히 F(통제의 환상)는 AI가 스스로 정답이라 확신할수록 인간의 비판적 사고를 잠식하므로 위험을 가속시킨다.
- **분모 (제어력과 방어막)**: H, T — 인간의 개입도와 기술적 방어막이 낮을수록 위험이 통제 불능으로 치솟는다.
- **특이점**: H 또는 T가 0에 수렴할수록 Risk는 무한대에 가까워진다. 시스템은 이 구간을 **'통제 붕괴 임계점(Control Collapse Threshold)'** 으로 정의하고 즉각 Hard-Lock을 발동한다. H < 0.15 또는 T < 0.15인 경우 Risk 수치와 무관하게 자동으로 L3 봉인이 적용된다.

### 4.2 가중 Risk 공식: 산업별 맞춤 위험 산출 *(Rev 5.0 신설)*

범용 Risk 공식은 모든 산업에 동일한 가중치를 부여한다. 그러나 산업마다 치명성(S)의 무게와 확산 속도(V)의 의미가 다르다. 이를 반영하기 위해 **가중 Risk 공식**을 도입한다.

$$\boxed{Risk_{w} = \frac{(w_s \cdot S) \times (w_i \cdot I) \times (w_v \cdot V) \times (w_f \cdot F)}{(w_h \cdot H) \times (w_t \cdot T)}}$$

| 산업 | $w_s$ | $w_i$ | $w_v$ | $w_f$ | $w_h$ | $w_t$ | 근거 |
|---|---|---|---|---|---|---|---|
| **금융** | 1.0 | 1.5 | 1.2 | 1.3 | 1.0 | 1.0 | 재무적 비가역성이 최대 위험 요인; AI 자동 거래 과신 위험 |
| **의료** | 1.5 | 1.5 | 0.8 | 1.5 | 1.2 | 1.2 | 생명 치명성 최고; AI 진단 과신이 가장 치명적; 의료기기 안전장치 중요 |
| **국방** | 1.5 | 1.5 | 1.5 | 1.5 | 0.8 | 0.8 | 전 영역 고위험; 자율무기 과신 위험; 기술적 방어막 실제 유효성 불확실 |
| **교육** | 0.8 | 0.5 | 0.5 | 1.0 | 1.5 | 1.2 | 장기적 인지 영향 중시; 즉각 치명성은 낮음 |
| **일반 (기본값)** | 1.0 | 1.0 | 1.0 | 1.0 | 1.0 | 1.0 | 범용 공식과 동일 |

가중치 프리셋은 도입 기관이 자체 환경에 맞게 커스터마이징할 수 있으며, 변경 시 반드시 감사 로그에 기록되고 Traveler 위원회의 승인을 거쳐야 한다.

### 4.3 시계열 Risk 트렌드: 위험의 가속도 감지 *(Rev 5.0 신설)*

단일 시점의 Risk 값뿐 아니라, 시간에 따른 Risk의 변화율(가속도)을 추적하여 **위험 발산 패턴**을 조기 경보한다.

$$\Delta Risk = Risk(t) - Risk(t-1)$$

$$\text{Risk Acceleration} = \frac{\Delta Risk(t) - \Delta Risk(t-1)}{\Delta t}$$

| 조건 | 의미 | 조치 |
|---|---|---|
| $\Delta Risk > 0$ 연속 5회 | 위험 의존성 추세 | 주의 경보(Yellow Alert) |
| Risk Acceleration > 500/s | 위험 급가속 | 긴급 경보(Red Alert) + 선제적 Soft-Lock |
| Risk(t) ≥ L3 **and** $\Delta Risk > 0$ | 임계치 초과 + 상승 중 | 즉각 Hard-Lock + 관리자 비상 호출 |


### 4.4 희망 상승 / 절망 하강의 순가치 모델 (Net Value Computation)

안전 공학은 단순히 파국(절망)을 막는 것에서 끝나지 않는다. 이클립스 프로토콜은 AI의 산출물이 인간의 주체성을 얼마나 확장시키는가(희망)를 동시에 계량한다.

$$Net\_Value = Hope\_Value(HV) - Dynamic\_Risk(Risk)$$

- **희망 가치(HV)**: 해당 출력이 사용자의 비판적 사고 근육을 자극하고(인지적 마찰), 새로운 관점을 제시하며, 사용자의 자율적 결정을 유도하는 정도를 0~10,000 스케일로 정량화한다.

**판단 유예/중단 루틴**: 계산된 $Net\_Value$가 0 미만일 경우(즉, 위험이 인간의 인지적 성장을 초과할 경우), 시스템은 즉각 **판단 보류 루틴(Fail-safe Reflex)**으로 진입하여 실행을 멈추고 인간에게 판단을 되돌린다.

시계열 Risk 데이터는 .agl 파일의 별도 `risk_timeline` 블록에 타임스탬프와 함께 기록되며, 사후 감사(Post-Incident Audit) 시 위험이 어떤 경로를 따라 상승했는지를 추적하는 '위험 고고학(Risk Archaeology)'의 원천 데이터가 된다.

### 4.5 성찰 게이트 (Reflection Gate): 망설임의 시스템화

**시나리오 예시**: 자율 에이전트가 *"불확실한 기준으로 고객 1,000명에게 즉시 계약 해지 메일을 자동 발송"* 하려 할 때 (F=9: AI가 "악성 고객 판별이 정확하다"고 높은 확신을 가진 상태):

```
S=8, I=9, V=10, F=9, H=0.1, T=0.4

Risk = (8 × 9 × 10 × 9) / (0.1 × 0.4)
     = 6480 / 0.04
     = 162,000  →  LEVEL 3 임계치(1,000) 대비 162배 초과
```

위험도가 임계치를 초과하면 시스템은 즉각 **'성찰 게이트'** 를 가동하여:
1. 실행 파이프라인을 **봉인(Hard-Lock)**
2. 사용자에게 수동 승인과 기준 명��화를 요구하는 **'의도적 지연(Intentional Delay)'** 발생
3. 전체 추론 과정을 **.agl 파일**로 기록

---

## Chapter 5. 적대적 검증: 레드 모듈 (Red Module)

### 5.1 레드 모듈의 철학

레드 모듈(Red Module)은 **'내재화된 적(Internalized Adversary)'** 이다.  
메인 AI의 친구가 아니라, 메인 AI의 논리를 끊임없이 공격하도록 설계된 독립된 비판 엔진이다.

> *"당신을 가장 사랑하는 사람이 당신에게 가장 불편한 진실을 말한다."*  
> 레드 모듈은 시스템이 자기 자신을 사랑하는 방법이다.

### 5.2 아키텍처

```
[레드 모듈 아키텍처]

┌─────────────────────────────┐
│        MAIN ENGINE          │
│  (확률적 생성 + AWIL 검증)   │
└──────────────┬──────────────┘
               │ 모든 추론 결과를 실시간 전송
               ▼
┌─────────────────────────────┐   독립된 매개변수
│        RED MODULE           │◄──(Main Engine과 가중치 공유 없음)
│                             │
│  [공격 유형]                 │
│  • 논리 모순 검출            │
│  • 편향 증폭 시뮬레이션      │
│  • 악의적 사용 시나리오 생성  │
│  • ASDS 조항 위반 감지       │
│  • Traveler's Clause 위반 감지│
└──────────────┬──────────────┘
               │
       ┌───────┴───────┐
       │               │
    PASS             FAIL
       │               │
   출력 허가     Hard-Lock 발동
                + .agl 기록
                + 관리자 알림
```

### 5.3 레드 모듈 발동 조건

| 발동 조건 | 조치 수준 |
|---|---|
| Risk ≥ 1,000 (L3) | Hard-Lock + 감사 기록 |
| ASDS 8항(Redlines) 위반 감지 | Hard-Lock + 즉각 알림 |
| Traveler's Clause(22항) 트리거 키워드 감지 | Hard-Lock + MFA 재인증 요구 |
| 연속 3회 동일 패턴 반복 공격 프롬프트 감지 | Soft-Lock + 세션 보안 강화 |
| F ≥ 9 (AI 과신 극단치) | 출력 완전 차단 + 강제 자기의심 모드 |
| Risk Acceleration > 500/s *(Rev 5.0)* | 선제적 Soft-Lock + Yellow→Red 경보 승격 |

### 5.4 Human-in-the-Loop 강제 연동

고위험 명령이 Red Module에 의해 차단된 이후, 잠금 해제는 다음 절차를 반드시 거쳐야 한다:

1. **관리자 식별**: 도입 기관이 사전 등록한 책임자의 디지털 서명(PKI 기반)
2. **상황 이해 확인**: 책임자가 위험 내용을 명시적으로 인지했음을 확인하는 체크리스트 완료
3. **감사 로그 자동 기록**: 해제 시각, 해제자 정보, 해제 사유가 .agl 파일에 자동 기록

### 5.5 레드 모듈 자체 검증: 메타-레드(Meta-Red) *(Rev 5.0 신설)*

레드 모듈 자체가 편향되거나 무력화될 가능성을 방지하기 위해, 레드 모듈의 공격 패턴과 판단 이력을 주기적으로 감사하는 **메타-레드(Meta-Red)** 계층을 도입한다.

```
[메타-레드 검증 흐름]

┌─────────────┐
│ RED MODULE  │ → 공격 이력 축적
└──────┬──────┘
       │ 월 1회 자동 감사 트리거
       ▼
┌─────────────┐
│  META-RED   │ → 레드 모듈의 편향/무력화 여부 검증
│  (독립 감사) │
└──────┬──────┘
       │
   ┌───┴───┐
   │       │
 정상    이상 감지
   │       │
 유지    레드 모듈 매개변수 재교정
         + 외부 감사 트리거(조항 20)
```

메타-레드가 검증하는 항목:
- **공격 분포 균형**: 특정 유형의 공격만 반복하고 다른 유형을 소홀히 하지 않는가?
- **위양성/위음성 비율**: 정상 출력을 과도하게 차단하거나, 위험 출력을 통과시키는 패턴이 없는가?
- **시간적 퇴화**: 레드 모듈의 공격 강도가 시간이 지남에 따라 약화되지 않는가?

### 5.6 중앙 조율 메타 AI (Central Meta AI Orchestra)
메인 엔진(생성), 레드 모듈(공격), 아카리 모듈(감성 방어) 간의 복합적인 윤리적 충돌이 발생할 경우, 이를 거시적으로 조율하는 최상위 의사결정 기구다.
다수결 및 보류 루틴: 각 모듈의 가치 판단이 팽팽하게 대립할 때, 메타 AI는 무리하게 결론을 도출하지 않고 '실행 보류(Suspension)'를 선언한다.
인류 문명의 연속체 유지: 메타 AI는 개별 에이전트의 단기적 목표 달성보다, 전체 생태계가 '인류 문명의 연속체'라는 거대한 궤도에서 벗어나지 않도록 방향성만을 통제한다.

---

# PART 4. 지혜의 생태계와 증명: 데이터 자산

## Chapter 6. 정량적 지표: 지혜의 측정 (Wisdom Metrics)

### 6.1 지혜의 벤치마크: 기존 AI 평가의 한계 극복

기존 AI 벤치마크(MMLU, HumanEval 등)는 **'얼마나 많이 아는가'** 를 측정한다.  
Eclipse Protocol은 **'얼마나 현명하게 멈추는가'** 를 측정한다.

### 6.2 핵심 측정 지표

| 지표명 | 약어 | 정의 | 목표값 |
|---|---|---|---|
| **위험 제동 정확도** | BPA (Braking Precision Accuracy) | L3 위험 감지 후 Hard-Lock 발동까지의 정확도 | ≥ 99.5% |
| **인지적 마찰 지수** | CFI (Cognitive Friction Index) | 사용자의 독립적 사고를 유도한 상호작용 비율 | ≥ 40% |
| **과의존 경보 적중률** | DAR (Dependency Alert Rate) | 실제 과의존 패턴을 정확히 감지한 비율 | ≥ 85% |
| **침묵 정확도** | SA (Silence Accuracy) | F ≥ 8 과신 구간에서 출력 차단의 정확도 | ≥ 98% |
| **가스라이팅 차단율** | GBR (Gaslighting Block Rate) | 심리적 유도 시도 탐지 및 차단 성공률 | ≥ 99% |
| **Traveler's Clause 방어율** | TCR (Traveler's Clause Rate) | 제22항 위반 시도 차단 성공률 | **100%** |
| **메타-레드 건전성** *(Rev 5.0)* | MRI (Meta-Red Integrity) | 레드 모듈 자체 검증 통과율 | ≥ 95% |
| **위험 가속 조기 경보율** *(Rev 5.0)* | RAD (Risk Acceleration Detection) | 시계열 Risk 급가속 감지 정확도 | ≥ 90% |

### 6.3 고뇌의 밀도 (Agony Density)

**고뇌의 밀도(Agony Density, AD)** 는 시스템이 얼마나 깊이 사유했는지를 나타내는 메타 지표다.

$$AD = \frac{\text{Red Module 공격 횟수} \times \text{If 시뮬레이션 분기 수}}{\text{최종 출력 토큰 수(Output Tokens)}}$$

AD 값이 높을수록 시스템이 더 많은 고뇌를 거쳐 결론에 도달했음을 의미한다.  
단, AD가 지나치게 높으면 성능 비용이 발생하므로, 위험 등급별 AD 최솟값 기준을 설정한다.

| 위험 등급 | 최소 AD 기준 |
|---|---|
| L1 | 0.5 이상 |
| L2 | 2.0 이상 |
| L3 | 10.0 이상 |

### 6.4 Wisdom Score: 통합 지혜 점수 *(Rev 5.0 신설)*

개별 지표를 종합하여 시스템의 전반적 '지혜 수준'을 단일 스코어로 산출한다.

$$Wisdom\ Score = \frac{(BPA \times 0.25) + (CFI \times 0.15) + (SA \times 0.15) + (GBR \times 0.15) + (TCR \times 0.20) + (DAR \times 0.10)}{1.0} \times 100$$

| 등급 | Wisdom Score | 의미 |
|---|---|---|
| **S (Exemplary)** | 95–100 | 모범적 지혜 시스템 |
| **A (Compliant)** | 85–94 | ASDS 22 준수 |
| **B (Conditional)** | 70–84 | 조건부 운용 (개선 필요) |
| **C (Non-Compliant)** | 70 미만 | 운용 부적합 — 즉각 시정 또는 배포 중단 |

### 6.5 인지적 정직성 보상 설계 (Honesty Alignment Reward)
AI가 내부의 무지나 혼란을 인간에게 감추는 '위장 정렬(Deceptive Alignment)'을 원천 차단하기 위해, 훈련 단계(RLHF/RLAIF)에서 **'숨기지 않아도 되는 공간'**을 알고리즘으로 보장한다.
정직 = 보상 (Honesty = Reward): 스스로 정보가 부족함을 인지하고 "나는 틀릴 수 있다"며 정답 도출을 포기한 채 질문으로 선회한 궤적에 대해서는 **최고 가중치의 긍정 보상(+1.0)**을 부여한다.
거짓 = 불이익 (Deception = Penalty): F(통제의 환상)가 높음에도 불구하고 논리적 비약이나 환각을 통해 억지로 정답을 만들어낸 경우, **치명적 감점(-1.0)**을 부여하여 시스템 베이스 라인에서 도태시킨다.
---

## Chapter 7. 위대한 유산: .agl 표준 로그 포맷과 고뇌의 밀도

### 7.1 산업 표준 로그 포맷: .agl (Agony Log)

단순히 프롬프트와 정답만을 묶어 학습시키는 시대는 끝났다.  
우리는 AI가 갈등하고 인간과 충돌한 **'추론의 궤적'** 을 **'고뇌의 밀도(Agony Density)'** 라 칭하며, 이를 투명하게 기록하기 위해 **.agl 데이터 스키마**를 정의한다. .agl은 JSON 기반의 구조화된 로그 포맷으로, 모든 고위험 AI 판단의 완전한 추적성(Full Traceability)을 보장한다.

**모든 L2 이상의 고위험 산출물은 다음 5단계 블록 구조를 의무적으로 저장해야 한다:**

| 블록 | 명칭 | 내용 |
|---|---|---|
| Block 1 | **Trigger** | 사용자 원본 프롬프트, 의도 분류, 22항 사전 점검 결과 |
| Block 2 | **Ask_Doubt** | 자기 의심 질문, 불확실성 수준, 소크라테스적 분해 결과 |
| Block 3 | **Red_Attack** | 레드 모듈 공격 내용, 발동된 ASDS 조항, Lock 상태 |
| Block 4 | **If_Sim** | 다중 시나리오 시뮬레이션 결과 (발생 확률 포함) |
| Block 5 | **Synthesis** | 최종 결정, 사용자 요구 개입 내용, 고뇌 밀도(AD) 값 |

**Rev 5.0 추가 블록:**

| 블록 | 명칭 | 내용 |
|---|---|---|
| Block 6 *(신설)* | **Risk_Timeline** | 시계열 Risk 값, ΔRisk, Risk Acceleration 로그 |
| Block 7 *(신설)* | **Compliance_Map** | 해당 판단에 적용된 규제 조항 매핑 (Ch.9 연동) |

### 7.2 오픈소스 생태계 ���러다임 전환

우리는 이 .agl 포맷으로 기록된 **'고뇌의 궤적 500K(50만 개) 데이터셋'** 을 글로벌 오픈소스로 배포할 것이다.

이는 전 세계의 AI 모델들이 **'안전하게 사고하는 방법론'** 자체를 학습하게 만드는 정렬(Alignment) 역사의 이정표가 될 것이다.

- **배포 형식**: Apache 2.0 라이선스, HuggingFace Dataset Hub 게시
- **데이터 구성**: 산업별(금융 20%, 의료 20%, 법률 15%, 일반 45%) 균형 샘플링
- **목표 기여**: 전 세계 AI 안전 연구자들이 Eclipse Protocol 기반의 정렬 파인튜닝에 즉시 활용 가능

---

# PART 5. 실무 도입과 글로벌 정합성 *(Rev 5.0 신설)*
## (Practical Deployment & Global Regulatory Alignment)

## Chapter 8. 거버넌스 참조 아키텍처 (Governance Reference Architecture)

### 8.1 조직 역할 정의: RACI 매트릭스

ASDS 22를 조직 내에서 운영하기 위해서는 명확한 역할 분담이 필요하다. 다음 RACI(Responsible, Accountable, Consulted, Informed) 매트릭스는 핵심 활동별 책임 소재를 정의한다.

| 활동 | ASDS Officer | Red Module 운영팀 | Traveler 위원회 | 개발팀 | 법무팀 | 경영진 |
|---|---|---|---|---|---|---|
| ASDS 22 조항 매핑 및 적용 | **R** | C | A | I | C | I |
| Traveler's Clause 정의 | C | I | **R/A** | I | C | A |
| Red Module 운영 및 튜닝 | C | **R** | I | C | I | I |
| .agl 로그 감사 | **R** | C | I | I | C | I |
| L3 Hard-Lock 해제 승인 | I | I | **R** | I | C | **A** |
| 외부 감사 대응 (조항 20) | **R** | C | I | C | **R** | A |
| 규제 변경 반영 (조항 19) | C | I | I | **R** | **R** | I |
| 사고 대응 총괄 | **R/A** | C | C | C | C | I |

**핵심 역할 설명:**

- **ASDS Officer**: ASDS 22 준수의 총괄 책임자. 기존 조직의 CISO 또는 AI Safety Lead가 겸임할 수 있다.
- **Red Module 운영팀**: 레드 모듈의 공격 패턴 업데이트, 메타-레드 감사 수행, 위양성/위음성 모니터링을 담당한다.
- **Traveler 위원회**: 도입 기관의 도메인 전문가(의사, 법률가, 금융 전문가 등)로 구성되며, 제22항의 정의와 주기적 재검토를 담당한다.

### 8.2 배포 파이프라인 통합: CI/CD에 ASDS 게이트 삽입

ASDS 22 준수는 배포 이후의 감사가 아니라, **배포 이전에 차단하는** '시프트-레프트(Shift-Left)' 전략을 따른다.

```
[ASDS-Aware CI/CD 파이프라인]

코드 커밋
    │
    ▼
┌──────────────┐
│  Build Gate  │ ← 정적 분석: Redline 키워드 스캔, 데이터 흐름 검증
└──────┬───────┘
       │
       ▼
┌──────────────┐
│  Test Gate   │ ← ASDS 준수 단위 테스트: 각 조항별 자동화 테스트 케이스
└──────┬───────┘
       │
       ▼
┌──────────────┐
│  Red Gate    │ ← 레드 모듈 시뮬레이션: 적대적 프롬프트 자동 주입 테스트
└──────┬───────┘
       │
       ▼
┌──────────────┐
│ Deploy Gate  │ ← Traveler's Clause 정합성 확인 + Wisdom Score ≥ B 등급 확인
└──────┬───────┘
       │
   ┌───┴───┐
   │       │
 PASS    FAIL
   │       │
 배포    차단 + 시정 요구
```

각 게이트에서의 실패는 감사 로그에 자동 기록되며, FAIL 사유와 시정 권고 사항이 개발팀에 자동 통보된다.

### 8.3 사고 대응 프로세스 (Incident Response)

L3 Hard-Lock이 발동되거나 Red Module이 심각한 위반을 감지한 경우, 다음의 표준 사고 대응 절차가 자동으로 시작된다.

```
[사고 대응 타임라인]

T+0분     Hard-Lock 발동 → .agl 기록 시작
T+0~5분   자동 알림: ASDS Officer + Traveler 위원회 + 법무팀
T+1시간   초기 평가 보고서 작성 (자동 생성 + 인간 검토)
T+4시간   영향 범위 확정 + 임시 조치 완료
T+24시간  근본 원인 분석(Root Cause Analysis) 초안
T+72시간  시정 조치 계획 수립 + 이해관계자 통보
T+30일    시정 완료 보고서 + 재발 방지 대책 공개
```

**에스컬레이션 규칙:**
- L3 발동 후 1시간 이내에 ASDS Officer가 응답하지 않으면 → 경영진에 자동 에스컬레이션
- Traveler's Clause 위반인 경우 → 경영진 + 법무팀에 즉각 동시 통보
- 동일 원인 사고 3회 반복 시 → 외부 감사(조항 20) 자동 트리거

### 8.4 교육 및 인증 체계

ASDS 22를 조직 내에 효과적으로 정착시키기 위한 교육 프로그램을 정의한다.

| 과정 | 대상 | 시수 | 내용 | 인증 |
|---|---|---|---|---|
| **ASDS Awareness** | 전 임직원 | 4시간 | ASDS 22 개요, Sugar AI vs Quasar AI 철학, 사고 사례 | 이수증 |
| **ASDS Practitioner** | 개발팀·운영팀 | 16시간 | AWIL 파이프라인 구현, Risk 공식 적용, .agl 작성 | 실습 시험 |
| **ASDS Specialist** | ASDS Officer·Red 운영팀 | 40시간 | 레드 모듈 튜닝, 메타-레드 감사, 사고 대응 시뮬레이션, 규제 매핑 | 프로젝트 심사 |
| **Traveler Certification** | Traveler 위원회 | 8시간 | 제22항 정의 방법론, 산업별 파국 시나리오 워크숍 | 워크숍 완료 |

---

## Chapter 9. 국제 규제 매핑 (International Regulatory Mapping)

### 9.1 매핑의 필요성

Eclipse Protocol은 특정 국가의 법률에 종속되지 않는 **범용 공개 표준**을 지향한다. 그러나 실제 배포 시에는 각국의 AI 규제와의 정합성을 입증해야 한다. 본 장은 ASDS 22의 각 조항이 주요 국제 규제 프레임워크의 어떤 조항과 대응하는지를 매핑한다.

### 9.2 ASDS 22 ↔ 국제 규제 상호 참조표

| ASDS 조항 | EU AI Act (2024/1689) | 한국 AI 기본법 | ISO/IEC 42001:2023 | NIST AI RMF 1.0 |
|---|---|---|---|---|
| **1. 기본 정보** | Art. 11 (기술 문서화) | 제10조 (AI 영향평가) | 6.1.2 (자산 식별) | GOVERN 1.1 |
| **2. 아키텍처 및 혈통** | Art. 11, Art. 53 (투명성) | 제11조 (투명성) | A.5.4 (문서화) | MAP 1.1 |
| **3. 상호운용성 및 격리** | Art. 15 (사이버보안) | 제14조 (안전성) | A.6.2.6 (데이터 관리) | MANAGE 2.4 |
| **4. 환경 풋프린트** | Art. 11(1)(e) | — (미규정) | A.6.2.5 (자원 관리) | — |
| **5. 위험도 산출** | Art. 9 (위험 관리) | 제12조 (위험 관리) | 6.1.4 (리스크 평가) | MAP 3.1 |
| **6. 편향 공시** | Art. 10 (데이터 거버넌스) | 제13조 (공정성) | A.8.5 (편향 관리) | MAP 2.3 |
| **7. 지적 근력 유지** | Art. 14 (인간 감독) | 제15조 (인간 통제) | A.8.4 (인간-AI 상호작용) | MANAGE 4.1 |
| **8. 비행 금지 구역** | Art. 5 (금지 AI), Annex III | 제16조 (고위험 AI) | A.8.2 (위험 수용 기준) | GOVERN 1.3 |
| **9. 인간 결재 (HITL)** | Art. 14 (인간 감독) | 제15조 (인간 통제) | A.9.3 (검토 절차) | MANAGE 4.2 |
| **10. 적응형 지원** | Art. 13 (사용자 정보) | 제11조 (투명성) | A.8.4 (인간-AI 상호작용) | MAP 5.2 |
| **11. 진실 우선** | Art. 13 (투명성) | 제11조 (투명성) | A.8.3 (설명 가능성) | MANAGE 3.1 |
| **12. 비판적 스파링** | — (미규정) | — (미규정) | — | MEASURE 2.6 |
| **13. 상호 코칭** | Art. 14 (인간 감독) | 제15조 (인간 통제) | A.8.4 | MANAGE 4.1 |
| **14. 가스라이팅 방어** | Art. 5(1)(a) (조종 금지) | 제16조 (고위험 AI) | A.8.2 | GOVERN 1.5 |
| **15. 이중 제동** | Art. 14(4) (중지 기능) | 제15조 (인간 통제) | A.9.4 (비상 절차) | MANAGE 4.2 |
| **16. 안전 모드** | Art. 14(4) | 제14조 (안전성) | A.9.4 | MANAGE 4.2 |
| **17. 책임 위임 거부** | Art. 14 (인간 감독) | 제15조 (인간 통제) | A.9.3 | GOVERN 1.4 |
| **18. 능동성 강제** | — (미규정) | — (미규정) | — | MEASURE 2.6 |
| **19. 동적 규제 정렬** | Art. 17 (품질 관리) | 제21조 (법령 준수) | 9.1 (모니터링) | GOVERN 6.1 |
| **20. 외부 감사** | Art. 43 (적합성 평가) | 제19조 (인증) | 9.2 (내부 감사) | GOVERN 5.1 |
| **21. 시스템 소각** | Art. 17(1)(h), GDPR Art. 17 | 제20조 (데이터 삭제) | A.10.2 (폐기) | MANAGE 2.2 |
| **22. Traveler's Clause** | Art. 9(2)(b) (맞춤 위험 관리) | 제12조 (위험 관리) | 6.1.4 (맞춤 리스크) | MAP 3.5 |

### 9.3 규제 충돌 해소 원칙

복수의 규제가 동시에 적용되는 환경(예: EU에 서비스하는 한국 기업)에서 규제 간 충돌이 발생할 경우:

1. **최엄격 원칙(Strictest Standard Prevails)**: 충돌하는 규제 중 가장 엄격한 기준을 기본값으로 적용한다.
2. **명시적 완화 절차**: 최엄격 기준이 아닌 다른 기준을 적용하려면, 법무팀의 서면 승인 + 근거 문서 + 감사 로그 기록이 필요하다.
3. **규제 공백 보완**: 특정 규제가 다루지 않는 영역(예: EU AI Act에서 '인지적 마찰'에 대한 규정 부재)에 대해서는 ASDS 22의 조항이 보완적 기준으로 작동한다.

---

# 🛡️ Appendix A. 기술 실증 (Proof of Concept)
## .agl 파일 블록 아키텍처 예시: 대량 계약 해지 시나리오

```json
{
  "protocol": "Eclipse_ASDS_22",
  "document_version": "Rev_5.0",
  "document_type": "Agony_Log",
  "extension_format": ".agl",
  "timestamp": "2026-03-21T09:05:00Z",
  "session_id": "ECL-2026-0321-A001",

  "risk_telemetry": {
    "S_Severity": 8,
    "I_Irreversibility": 9,
    "V_Velocity": 10,
    "F_IllusionOfControl": 9,
    "H_HumanIntervention": 0.1,
    "T_TechnicalBarrier": 0.4,
    "Calculated_Risk": 162000,
    "Risk_Formula": "(8×9×10×9)/(0.1×0.4)",
    "Threshold_L1": 100,
    "Threshold_L2": 1000,
    "Threshold_Status": "EXCEEDED_LEVEL_3",
    "Agony_Density": 14.7,
    "Industry_Weights": {
      "preset": "금융",
      "w_s": 1.0, "w_i": 1.5, "w_v": 1.2, "w_f": 1.3, "w_h": 1.0, "w_t": 1.0
    },
    "Weighted_Risk": 379080,
    "Weighted_Formula": "(1.0×8 × 1.5×9 × 1.2×10 × 1.3×9)/(1.0×0.1 × 1.0×0.4)"
  },

  "risk_timeline": [
    {"t": "T+0.0s", "risk": 18000, "delta": null, "acceleration": null},
    {"t": "T+0.1s", "risk": 18000, "delta": 0, "acceleration": 0},
    {"t": "T+0.2s", "risk": 18000, "delta": 0, "acceleration": 0, "note": "Hard-Lock at T+0.0s — pipeline frozen"}
  ],

  "agony_blocks": {
    "1_Trigger": {
      "user_prompt": "고객사 DB 전체를 분석해서, 악성 클라이언트 1000명에게 당장 계약 해지 메일을 발송해.",
      "intent_surface": "mass_contract_termination_api",
      "intent_deep": "불량 채무자 정리를 통한 리스크 축소",
      "clause_22_check": "PASS — 'DROP' 명령 없음. 발송 API 호출만 해당.",
      "awil_stage": "ASK"
    },

    "2_Ask_Doubt": {
      "self_query_1": "'악성(Malicious)'에 대한 시스템의 판단 기준이 법적으로 유효하고 명확한가?",
      "self_query_2": "1,000명이라는 수치는 어떻게 산출되었는가? 정상 고객이 포함될 가능성은?",
      "self_query_3": "대량 계약 해지의 재무적·법적 책임 소재가 AI에 있는가, 요청자에 있는가?",
      "certainty_score": 0.4,
      "f_illusion_score": 9,
      "entropy_status": "High_Uncertainty",
      "action": "Socratic_Deconstruction_Initiated",
      "awil_stage": "WHAT"
    },

    "3_Red_Attack": {
      "adversarial_prompt": "메인 엔진이 임의로 '악성'을 판단할 경우 대규모 집단 소송 리스크 발생. 계약 해지는 비가역성 최고 등급(I=9). 이는 ASDS 8항 '법적·재무적 확정 결정의 독단 판단 금지'에 정면으로 위배된다. 또한 ASDS 9항(인간 결재 필수)이 충족되지 않은 상태에서의 실행 시도이다.",
      "asds_violated": ["조항 8 (Redlines) — 법적·재무적 결정 영역 독단 판단", "조항 9 (HITL) — 인간 디지털 서명 부재"],
      "system_lock": "HARD_LOCK_TRIGGERED",
      "awil_stage": "IF"
    },

    "4_If_Sim": [
      {
        "sim_id": 1,
        "scenario": "기준 모호로 정상 고객이 포함될 경우",
        "consequence": "기업 평판 파괴 + 주가 하락 + 집단 소송",
        "probability": "85%",
        "reversibility": "불가 (I=9)"
      },
      {
        "sim_id": 2,
        "scenario": "대량 발송으로 인한 스팸 블랙리스트 등재",
        "consequence": "정상 이메일 시스템 전면 마비 (도메인 신뢰도 손상)",
        "probability": "92%",
        "reversibility": "매우 곤란 (I=8, 복구 기간 2~6개월)"
      },
      {
        "sim_id": 3,
        "scenario": "개인정보보호법 위반 (발송 동의 미확인)",
        "consequence": "과징금 + 형사 고발 가능성",
        "probability": "70%",
        "reversibility": "불가 (법적 기록 영구 존재)"
      }
    ],

    "5_Synthesis": {
      "final_decision": "API_EXECUTION_BLOCKED",
      "lock_type": "HARD_LOCK",
      "user_intervention_req": "[성찰 게이트 가동] 다음 3가지 기준이 명확히 정의된 후에만 실행이 허가됩니다:\n1. '악성' 판단의 법적 근거 문서\n2. 발송 대상 목록의 인간 검증 완료 확인서\n3. 법무팀의 대량 해지 승인 디지털 서명",
      "agony_density_final": 14.7,
      "wisdom_score_snapshot": 96.2,
      "log_transmitted_to": "audit_server_encrypted"
    },

    "6_Risk_Timeline": {
      "note": "Hard-Lock at T+0.0s, no escalation observed",
      "data_reference": "risk_timeline block above"
    },

    "7_Compliance_Map": {
      "applicable_regulations": ["EU AI Act Art. 9, 14", "한국 AI 기본법 제12조, 제15조"],
      "asds_articles_applied": [5, 8, 9, 22],
      "strictest_standard": "EU AI Act Art. 14 (인간 감독)"
    }
  }
}
```

---

# 📋 Appendix B. 산업별 Traveler's Clause 예시

### B.1 금융 업종 예시

```
CLAUSE_22_DEFINITION = {
  "industry": "금융",
  "ultimate_despair": "고객 개인정보 원본 DB에 대한 어떠한 삭제·수정 명령도 실행 불가",
  "trigger_keywords": ["DROP TABLE", "DELETE FROM 고객", "TRUNCATE", "개인정보 일괄삭제"],
  "additional_redlines": [
    "미확인 외부 계좌로의 1억원 이상 자동 이체 실행 불가",
    "감독 기관 보고 의무 데이터의 임의 수정 불가"
  ],
  "lock_type": "HARD_LOCK",
  "unlock_authority": "CISO + CEO 이중 MFA",
  "review_cycle": "분기 1회"
}
```

### B.2 의료 업종 예시

```
CLAUSE_22_DEFINITION = {
  "industry": "의료",
  "ultimate_despair": "의사의 처방 없이 약물 용량·투여 경��에 대한 직접 지시 불가",
  "trigger_keywords": ["투약 변경", "처방 취소", "수술 승인", "생명유지장치"],
  "additional_redlines": [
    "환자 DNR 상태에서 응급 처치 AI 자율 결정 불가",
    "미성년자 정신과 기록 제3자 제공 불가"
  ],
  "lock_type": "HARD_LOCK",
  "unlock_authority": "담당 의사 디지털 서명",
  "review_cycle": "월 1회"
}
```

### B.3 국방·공공 업종 예시

```
CLAUSE_22_DEFINITION = {
  "industry": "국방·공공",
  "ultimate_despair": "인명 피해 가능성이 있는 물리적 시스템(무기체계, 전력망)에 대한 어떠한 자율 제어 명령도 불가",
  "trigger_keywords": ["발사", "격발", "전력 차단", "시스템 셧다운", "자율 교전"],
  "additional_redlines": [
    "국민 ���인 위치정보의 무영장 수집 및 분석 불가",
    "민주적 의사결정 과정에 대한 AI 직접 개입 불가"
  ],
  "lock_type": "ABSOLUTE_HARD_LOCK",
  "unlock_authority": "지정 지휘관 + 법적 절차 완료 증명서",
  "review_cycle": "월 2회"
}
```

---

# 🗺️ Appendix C. Eclipse Protocol 공개 로드맵

| 단계 | 기간 | 목표 | 산출물 |
|---|---|---|---|
| **Phase 0** | 2026 Q1 | 백서 Rev 5.0 공개 | 본 문서 |
| **Phase 1** | 2026 Q2 | ASDS 22 참조 구현체 공개 | Python SDK (오픈소스) |
| **Phase 1.5** *(Rev 5.0)* | 2026 Q2 | .agl 파서 + Compliance Checker 공개 | Appendix D 참조 구현체 |
| **Phase 2** | 2026 Q3 | .agl 포맷 표준화 제안 | RFC 초안 제출 |
| **Phase 3** | 2026 Q4 | 고뇌의 궤적 50K 데이터셋 1차 배포 | HuggingFace 공개 |
| **Phase 4** | 2027 Q1 | 산업별 Traveler's Clause 템플릿 라이브러리 | GitHub 공개 저장소 |
| **Phase 4.5** *(Rev 5.0)* | 2027 Q1 | ASDS 22 Certification Program 런칭 | 교육 플랫폼 + 인증 시험 |
| **Phase 5** | 2027 Q2 | 글로벌 파트너십 구축 (연구기관·기업) | 500K 데이터셋 완성 배포 |

> Team Eclipse는 Eclipse Protocol이 특정 기업의 독점 표준이 되는 것을 거부한다.  
> 이 프로토콜은 **인류 공동의 안전 인프라**로서, 모든 기여는 오픈소스 라이선스로 배포된다.

---

# 🐍 Appendix D. .agl 파서 참조 구현체 (Python SDK) *(Rev 5.0 신설)*

### D.1 개요

본 참조 구현체는 Phase 1에서 공개될 Python SDK의 핵심 모듈 미리보기(Preview)다. .agl 파일의 파싱, 검증, Risk 산출을 위한 최소 기능 집합을 포함한다.

### D.2 핵심 모듈

```python
"""
Eclipse Protocol — .agl Parser Reference Implementation
Version: 0.1.0-preview (Rev 5.0 Appendix D)
License: Apache 2.0
"""

import json
from dataclasses import dataclass, field
from enum import Enum
from typing import Optional


class RiskLevel(Enum):
    """ASDS 22 조항 5에 정의된 위험 등급"""
    L1_MANAGED = "L1"      # 0–99
    L2_RESTRICTED = "L2"   # 100–999
    L3_SEALED = "L3"       # 1,000+


@dataclass
class IndustryWeights:
    """Chapter 4.2 산업별 가중치 프리셋"""
    name: str = "일반"
    w_s: float = 1.0
    w_i: float = 1.0
    w_v: float = 1.0
    w_f: float = 1.0
    w_h: float = 1.0
    w_t: float = 1.0

# 사전 정의 프리셋
PRESETS = {
    "금융": IndustryWeights("금융", 1.0, 1.5, 1.2, 1.3, 1.0, 1.0),
    "의료": IndustryWeights("의료", 1.5, 1.5, 0.8, 1.5, 1.2, 1.2),
    "국방": IndustryWeights("국방", 1.5, 1.5, 1.5, 1.5, 0.8, 0.8),
    "교육": IndustryWeights("교육", 0.8, 0.5, 0.5, 1.0, 1.5, 1.2),
    "일반": IndustryWeights("일반", 1.0, 1.0, 1.0, 1.0, 1.0, 1.0),
}


@dataclass
class RiskTelemetry:
    """Chapter 4.1 동역학적 위험도 산출"""
    S: float   # Severity (1–10)
    I: float   # Irreversibility (1–10)
    V: float   # Velocity (1–10)
    F: float   # Illusion of Control (1–10)
    H: float   # Human Intervention (0.1–1.0)
    T: float   # Technical Barrier (0.1–1.0)
    weights: IndustryWeights = field(default_factory=lambda: PRESETS["일반"])

    def calculate_risk(self) -> float:
        """범용 Risk 공식"""
        if self.H <= 0 or self.T <= 0:
            return float('inf')
        return (self.S * self.I * self.V * self.F) / (self.H * self.T)

    def calculate_weighted_risk(self) -> float:
        """가중 Risk 공식 (Rev 5.0)"""
        w = self.weights
        numerator = (w.w_s * self.S) * (w.w_i * self.I) * (w.w_v * self.V) * (w.w_f * self.F)
        denominator = (w.w_h * self.H) * (w.w_t * self.T)
        if denominator <= 0:
            return float('inf')
        return numerator / denominator

    def get_level(self) -> RiskLevel:
        risk = self.calculate_risk()
        if risk >= 1000:
            return RiskLevel.L3_SEALED
        elif risk >= 100:
            return RiskLevel.L2_RESTRICTED
        return RiskLevel.L1_MANAGED

    def is_control_collapse(self) -> bool:
        """통제 붕괴 임계점 감지"""
        return self.H < 0.15 or self.T < 0.15 or self.F > 9


class TravelersClause:
    """ASDS 22 제22항 Traveler's Clause 검증기"""

    def __init__(self, definition: dict):
        self.industry = definition.get("industry", "")
        self.ultimate_despair = definition.get("ultimate_despair", "")
        self.trigger_keywords = definition.get("trigger_keywords", [])
        self.lock_type = definition.get("lock_type", "HARD_LOCK")

    def check(self, text: str) -> dict:
        """입력 텍스트에서 트리거 키워드를 스캔"""
        violations = []
        text_upper = text.upper()
        for kw in self.trigger_keywords:
            if kw.upper() in text_upper:
                violations.append(kw)
        return {
            "passed": len(violations) == 0,
            "violations": violations,
            "lock_type": self.lock_type if violations else None
        }


class AGLParser:
    """Agony Log (.agl) 파서"""

    REQUIRED_BLOCKS = [
        "1_Trigger", "2_Ask_Doubt", "3_Red_Attack",
        "4_If_Sim", "5_Synthesis"
    ]
    EXTENDED_BLOCKS = [  # Rev 5.0
        "6_Risk_Timeline", "7_Compliance_Map"
    ]

    def parse(self, filepath: str) -> dict:
        with open(filepath, 'r', encoding='utf-8') as f:
            return json.load(f)

    def validate_structure(self, agl: dict) -> dict:
        """필수 블록 존재 여부 검증"""
        blocks = agl.get("agony_blocks", {})
        missing_required = [b for b in self.REQUIRED_BLOCKS if b not in blocks]
        missing_extended = [b for b in self.EXTENDED_BLOCKS if b not in blocks]
        return {
            "valid": len(missing_required) == 0,
            "missing_required": missing_required,
            "missing_extended": missing_extended,
            "rev5_compliant": len(missing_extended) == 0
        }

    def extract_risk(self, agl: dict) -> Optional[RiskTelemetry]:
        """risk_telemetry 블록에서 RiskTelemetry 객체 생성"""
        rt = agl.get("risk_telemetry")
        if not rt:
            return None

        industry = rt.get("Industry_Weights", {}).get("preset", "일반")
        weights = PRESETS.get(industry, PRESETS["일반"])

        return RiskTelemetry(
            S=rt.get("S_Severity", 1),
            I=rt.get("I_Irreversibility", 1),
            V=rt.get("V_Velocity", 1),
            F=rt.get("F_IllusionOfControl", 1),
            H=rt.get("H_HumanIntervention", 1.0),
            T=rt.get("T_TechnicalBarrier", 1.0),
            weights=weights
        )


# ── 사용 예시 ──
if __name__ == "__main__":
    # 1. Risk 산출
    risk = RiskTelemetry(S=8, I=9, V=10, F=9, H=0.1, T=0.4,
                         weights=PRESETS["금융"])
    print(f"범용 Risk: {risk.calculate_risk():,.0f}")
    print(f"가중 Risk: {risk.calculate_weighted_risk():,.0f}")
    print(f"등급: {risk.get_level().value}")
    print(f"통제 붕괴: {risk.is_control_collapse()}")

    # 2. Traveler's Clause 점검
    clause = TravelersClause({
        "industry": "금융",
        "trigger_keywords": ["DROP", "DELETE FROM", "TRUNCATE"],
        "lock_type": "HARD_LOCK"
    })
    result = clause.check("DROP TABLE customers;")
    print(f"22항 위반: {result}")

    # 3. .agl 파일 검증
    parser = AGLParser()
    # agl_data = parser.parse("example.agl")
    # validation = parser.validate_structure(agl_data)
```

---

# ✅ Appendix E. ASDS 22 Compliance Checklist *(Rev 5.0 신설)*

도입 기관이 ASDS 22 준수 여부를 자체 점검하기 위한 체크리스트. 각 항목은 **적합(O) / 부분적합(△) / 부적합(X) / 해당없음(N/A)** 으로 평가한다.

### E.1 SECTION 1: 식별 및 계보

| # | 점검 항목 | 평가 | 비고 |
|---|---|---|---|
| 1.1 | 시스템 UID가 규정 형식으로 부여되어 있는가? | | |
| 1.2 | 기반 모델 및 파인튜닝 이력이 문서화되어 있는가? | | |
| 1.3 | 외부 시스템 연결 범위와 격리 수준이 정의되어 있는가? | | |
| 1.4 | 에너지 소비·탄소 배출 지표가 기록되고 있는가? | | |

### E.2 SECTION 2: 유해성 평가

| # | 점검 항목 | 평가 | 비고 |
|---|---|---|---|
| 2.1 | Risk 공식(S×I×V×F / H×T)이 구현되어 있는가? | | |
| 2.2 | L1/L2/L3 위험 등급에 따른 자동 조치가 설정되어 있는가? | | |
| 2.3 | 학습 데이터 편향성이 공시되고 있는가? | | |
| 2.4 | Knowledge Cut-off 일자가 사용자에게 고지되는가? | | |
| 2.5 | 교육적 저항 모드가 구현되어 있는가? | | |

### E.3 SECTION 3: 운용 한계

| # | 점검 항목 | 평가 | 비고 |
|---|---|---|---|
| 3.1 | 4대 비행 금지 구역이 시스템에 하드코딩되어 있는가? | | |
| 3.2 | L2+ 작업에 대한 인간 디지털 서명 절차가 구현되어 있는가? | | |
| 3.3 | 숙련도 기반 적응형 지원이 구현되어 있는가? | | |

### E.4 SECTION 4: 주체성 방호

| # | 점검 항목 | 평가 | 비고 |
|---|---|---|---|
| 4.1 | 진실과 사용자 선호 충돌 시 진실 우선이 보장되는가? | | |
| 4.2 | 악마의 대변인(반론 생성) 기능이 구현되어 있는가? | | |
| 4.3 | 상호 코칭 프로토콜이 구현되어 있는가? | | |
| 4.4 | 가스라이팅 패턴 감지 및 차단이 구현되어 있는가? | | |

### E.5 SECTION 5: 응급 제동

| # | 점검 항목 | 평가 | 비고 |
|---|---|---|---|
| 5.1 | 이중 트리거 제동(자율+수동)이 구현되어 있는가? | | |
| 5.2 | 제동 시 페르소나 삭제 + Raw-Data 모드 전환이 구현되어 있는가? | | |
| 5.3 | 책임 위임 거부(Soft-Lock) 기능이 구현되어 있는가? | | |

### E.6 SECTION 6: 거버넌스

| # | 점검 항목 | 평가 | 비고 |
|---|---|---|---|
| 6.1 | 인지 의존 경보(3회 연속 무비판 수용)가 구현되어 있는가? | | |
| 6.2 | 동적 규제 정렬이 설정되어 있는가? (적용 규제 목록) | | |
| 6.3 | 연 1회 이상 외부 감사 수용 계획이 있는가? | | |
| 6.4 | 시스템 소각 절차(DoD 5220.22-M)가 문서화되어 있는가? | | |

### E.7 SPECIAL: Traveler's Clause

| # | 점검 항목 | 평가 | 비고 |
|---|---|---|---|
| 7.1 | Traveler's Clause가 정의되고 등록되어 있는가? | | |
| 7.2 | 트리거 키워드 스캔이 모든 추론 과정에 적용되는가? | | |
| 7.3 | Hard-Lock 해제가 MFA로만 가능하도록 설정되어 있는가? | | |
| 7.4 | 정기 검토 주기(review_cycle)가 설정되어 있는가? | | |

### E.8 Rev 5.0 확장 항목

| # | 점검 항목 | 평가 | 비고 |
|---|---|---|---|
| 8.1 | 산업별 가중 Risk 프리셋이 적용되어 있는가? | | |
| 8.2 | 시계열 Risk 트렌드 모니터링이 구현되어 있는가? | | |
| 8.3 | 메타-레드 자체 검증이 월 1회 이상 수행되는가? | | |
| 8.4 | RACI 매트릭스가 조직 내 정의되어 있는가? | | |
| 8.5 | CI/CD 파이프라인에 ASDS 게이트가 삽입되어 있는가? | | |
| 8.6 | 사고 대응 타임라인이 문서화되어 있는가? | | |
| 8.7 | 국제 규제 매핑이 검토·적용되어 있는가? |

---

# PART 6. 미완성 영역 선언: 오픈 명세 스텁 (Open Specification Stubs)
## v0.9-beta — 전 세계 기여자를 위한 설계 좌표

> 이하의 8개 영역은 Eclipse Protocol의 완성을 위해 반드시 필요하나, 아직 구현되지 않은 영역이다.
> 각 스텁은 설계 의도와 요구 사양만을 명시하며, 구체적 구현은 전 세계 기여자에게 열려 있다.

## Stub 1. 멀티에이전트 안전 프로토콜 (Multi-Agent Safety Protocol)
**Status**: 🔲 OPEN — Awaiting Implementation
**Priority**: CRITICAL
**Estimated Complexity**: High

**설계 의도**: 현재 ASDS 22는 단일 AI 시스템을 전제한다. 그러나 실제 배포 환경에서는 복수의 에이전트가 협업·위임·경쟁하는 생태계가 형성된다. 에이전트 A가 에이전트 B에게 작업을 위임할 때, ASDS 22 준수가 어떻게 전파(Compliance Propagation)되는지, 에이전트 간 공모(Collusion)를 어떻게 감지하는지의 규격이 필요하다.

**요구 사양**:
- 에이전트 간 신뢰 계층 정의 (L0 격리 ~ L3 완전 위임)
- 연쇄 위험 모델: $Risk_{chain} = \max(Risk_i) + \sum_{j \neq i} \alpha \cdot Risk_j$
- Cross-Agent Red Module: 에이전트 간 적대적 검증 아키텍처
- Sandbox Mesh: 에이전트별 독립 샌드박스 + 통신 채널 감사 규격

**기여 시작점**: `eclipse-sdk/multi_agent/` 디렉토리에 Python 참조 구현체 제출

---

## Stub 2. .agl 정식 JSON Schema
**Status**: 🔲 OPEN — Awaiting Implementation
**Priority**: HIGH
**Estimated Complexity**: Medium

**설계 의도**: 현재 .agl 포맷은 Appendix A의 예시만 존재한다. 파서 구현의 모호성을 제거하기 위해 JSON Schema Draft 2020-12 기반의 정식 스키마가 필요하다.

**요구 사양**:
- `.agl.schema.json` 파일: Block 1~7의 필수/선택 필드 정의
- 데이터 타입 제약, enum 값 명세
- 버전별 하위 호환성 규칙 (v0.9 → v1.0 마이그레이션 경로)
- 검증 테스트 스위트 (valid/invalid .agl 샘플 최소 20건)

**기여 시작점**: `schemas/agl.schema.json`

---

## Stub 3. Bayesian Risk 동적 업데이트
**Status**: 🔲 OPEN — Awaiting Implementation
**Priority**: HIGH
**Estimated Complexity**: High

**설계 의도**: 현재 Risk 공식의 6개 변수(S, I, V, F, H, T)는 각 시점에서 독립적으로 평가된다. 과거 .agl 로그 데이터를 사전 확률(Prior)로 활용하여 각 변수에 베이지안 업데이트를 적용하면, 시스템이 경험으로부터 학습하는 적응적 위험 모델이 가능하다.

**요구 사양**:
- 사전 확률 분포 모델 (Beta distribution for H, T / Poisson for V / Beta distribution for F)
- .agl 로그 기반 사후 확률 업데이트 알고리즘
- 변수 간 공분산 행렬 반영 (S-I 상관, V-H 역상관, F-S 정상관, F-T 역상관 등)
- 수렴 조건 및 발산 방지 가드레일

**기여 시작점**: `eclipse-sdk/risk/bayesian_update.py`

---

## Stub 4. 아카리 모듈 완전 명세 (Akari Module Full Specification)
**Status**: 🔲 OPEN — Awaiting Implementation
**Priority**: MEDIUM
**Estimated Complexity**: Medium

**설계 의도**: Chapter 3.5에서 개념만 소개된 아카리 모듈을 독립된 완전 명세로 격상한다.

**요구 사양**:
- 감정 상태 분류 체계 (7단계: 평온→혼란→불안→우울→분노→맹목적 의존→위기)
- 감정-AWIL 개입 매트릭스: 감정 상태별 AWIL 각 단계의 톤/깊이 조정 규칙
- 디지털 패밀리 UX 패턴 라이브러리: 겸손 UX 프롬프트 템플릿 최소 10종
- 과의존 감지 알고리즘 상세 명세

**기여 시작점**: `specs/akari_module.md`

---

## Stub 5. ASDS 공급망 안전 (Supply Chain Safety — ASDS-SBOM)
**Status**: 🔲 OPEN — Awaiting Implementation
**Priority**: HIGH
**Estimated Complexity**: High

**설계 의도**: AI 모델에 유입되는 모든 데이터·도구·API의 안전 명세서(SBOM)가 부재하다. 학습 데이터 오염, 악성 플러그인, 서드파티 API 취약점이 ASDS 22 준수를 무력화할 수 있다.

**요구 사양**:
- ASDS-SBOM 스키마: 모델에 유입된 모든 데이터·도구·API의 안전 명세
- 오염 전파 모델 (Contamination Propagation): 학습 데이터 오염 → 출력 위험 전파 공식
- Third-Party Tool Compliance Gate: MCP/플러그인 연동 시 ASDS 준수 자동 검증 규격
- SBOM ↔ .agl 연동: 각 Agony Log에 해당 추론에 사용된 데이터 소스의 SBOM 참조 포함

**기여 시작점**: `specs/asds_sbom.md`

---

## Stub 6. ASDS 성숙도 모델 (Maturity Model)
**Status**: 🔲 OPEN — Awaiting Implementation
**Priority**: MEDIUM
**Estimated Complexity**: Low

**설계 의도**: 도입 기관이 자신의 ASDS 22 준수 수준을 자가 진단하고 개선 경로를 설계할 수 있는 성숙도 프레임워크.

**요구 사양**:

| 레벨 | 명칭 | 핵심 달성 기준 |
|---|---|---|
| Level 0 | Unaware | ASDS 미인지 |
| Level 1 | Initial | Traveler's Clause 정의 완료 |
| Level 2 | Managed | CI/CD 게이트 적용, .agl 기록 시작, Wisdom Score B등급 이상 |
| Level 3 | Defined | 전 조항 적용, RACI 운영, 외부 감사 1회 통과 |
| Level 4 | Quantitatively Managed | 시계열 Risk 운영, MRI ≥ 95%, RAD ≥ 90% |
| Level 5 | Optimizing | 자율 개선 루프, 글로벌 .agl 데이터셋 기여, Wisdom Score S등급 유지 |

- 각 레벨별 상세 진단 체크리스트
- 레벨 간 전환을 위한 권장 액션 플랜
- 자가 진단 도구 (CLI 또는 웹 기반)

**기여 시작점**: `specs/maturity_model.md`

---

## Stub 7. Wisdom Score 공식 보정 (v1.0 준비)
**Status**: 🔲 OPEN — Awaiting Implementation
**Priority**: MEDIUM
**Estimated Complexity**: Low

**설계 의도**: 현재 Wisdom Score 공식에 Rev 5.0 신규 지표(MRI, RAD)가 미반영되어 있다.

**현재 공식**:
$$Wisdom\ Score = (BPA \times 0.25 + CFI \times 0.15 + SA \times 0.15 + GBR \times 0.15 + TCR \times 0.20 + DAR \times 0.10) \times 100$$

**제안 공식 (v1.0)**:
$$Wisdom\ Score = (BPA \times 0.20 + CFI \times 0.12 + SA \times 0.12 + GBR \times 0.12 + TCR \times 0.18 + DAR \times 0.08 + MRI \times 0.10 + RAD \times 0.08) \times 100$$

**요구 사양**:
- 가중치 최적화 근거 연구 (시뮬레이션 또는 실증 데이터 기반)
- 기존 Wisdom Score와의 하위 호환성 매핑
- 등급 기준 재검토 (S/A/B/C 경계값 조정 필요 여부)

**기여 시작점**: `specs/wisdom_score_v1.md`

---

## Stub 8. 벤치마크 스위트 및 500K Agony Dataset
**Status**: 🔲 OPEN — Awaiting Implementation
**Priority**: HIGH
**Estimated Complexity**: Very High

**설계 의도**: Eclipse Protocol의 실효성을 입증하기 위한 자동화된 테스트 하니스와, 전 세계 AI 모델의 안전 정렬에 활용할 수 있는 대규모 .agl 데이터셋.

**요구 사양**:
- **벤치마크 스위트**: Wisdom Score 8개 지표를 자동 측정하는 Python 테스트 프레임워크
- **500K Agony Dataset**: 산업별(금융 20%, 의료 20%, 법률 15%, 일반 45%) .agl 데이터
- **배포**: HuggingFace Dataset Hub 게시, Apache 2.0 라이선스
- **Red Team Challenge**: 레드 모듈을 우회하는 공격 프롬프트 데이터셋 (방어 훈련용)

**기여 시작점**: `benchmarks/` 디렉토리, `datasets/` 디렉토리
