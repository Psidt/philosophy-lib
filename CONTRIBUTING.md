# 🤝 Contributing to Eclipse Protocol
## 이클립스 프로토콜에 기여하기

### "Welcome to Team Eclipse — Empowering Humanity through AI Safety."
우리는 인류의 안전을 위해 모였습니다. 당신의 지혜를 더해 팀 이클립스의 코덱스를 완성해 주세요.

---

## 🌍 Welcome / 환영합니다

Eclipse Protocol is a universal open standard for AI cognitive safety. We welcome contributions from:

- 🐍 **Python Developers**: SDK implementation, .agl parser, benchmark tools
- 🤖 **AI/ML Engineers**: Risk model implementation, Red Module simulation, Bayesian updates
- 🔒 **Safety Researchers**: Protocol analysis, attack surface mapping, formal verification
- 📋 **Policy Experts**: Regulatory mapping extensions, compliance frameworks
- 🌐 **Translators**: Localization to additional languages
- 📝 **Technical Writers**: Documentation improvements, tutorials, guides

---

## 📍 Where to Start / 어디서 시작할까?

### Open Specification Stubs (미완성 영역)

The White Paper ([Eclipse-Protocol-Open-Standard.md](./Eclipse-Protocol-Open-Standard.md)) contains **8 Open Specification Stubs** in PART 6 — deliberately incomplete areas awaiting community implementation:

| Stub | Area | Priority | Complexity |
|---|---|---|---|
| 1 | Multi-Agent Safety Protocol | 🔴 CRITICAL | High |
| 2 | .agl JSON Schema | 🟠 HIGH | Medium |
| 3 | Bayesian Risk Update | 🟠 HIGH | High |
| 4 | Akari Module Full Spec | 🟡 MEDIUM | Medium |
| 5 | Supply Chain Safety (ASDS-SBOM) | 🟠 HIGH | High |
| 6 | ASDS Maturity Model | 🟡 MEDIUM | Low |
| 7 | Wisdom Score v1.0 Formula | 🟡 MEDIUM | Low |
| 8 | Benchmark Suite & 500K Agony Dataset | 🟠 HIGH | Very High |

---

## 🔀 How to Contribute / 기여 방법

### 1. Pick a Stub or Issue
- Check the [Open Specification Stubs](./Eclipse-Protocol-Open-Standard.md#part-6-미완성-영역-선언-오픈-명세-스텁-open-specification-stubs) in the White Paper
- Or browse [GitHub Issues](../../issues) for tagged tasks

### 2. Fork & Branch
```bash
git clone https://github.com/YOUR_USERNAME/philosophy-lib.git
cd philosophy-lib
git checkout -b stub/your-contribution-name
```

### 3. Implement
- **Specifications**: Place in `specs/` directory (Markdown)
- **Python SDK**: Place in `eclipse-sdk/` directory
- **Schemas**: Place in `schemas/` directory
- **Benchmarks**: Place in `benchmarks/` directory
- **Datasets**: Place in `datasets/` directory (or link to external hosting)

### 4. Submit a Pull Request
- Reference the Stub number (e.g., "Implements Stub 2: .agl JSON Schema")
- Include tests where applicable
- Bilingual (Korean + English) documentation is appreciated but not required

---

## 📏 Contribution Guidelines / 기여 가이드라인

### Code
- Python 3.10+
- Type hints required
- Docstrings in English (Korean comments welcome)
- Tests with pytest

### Specifications
- Markdown format
- Must reference relevant ASDS 22 articles
- Must include rationale/design intent section

### Philosophy
- **We reject Sugar AI.** Contributions that prioritize convenience over cognitive safety will not be merged.
- **Failure-First Design.** Always consider catastrophic scenarios before optimizing for efficiency.
- **Honest Silence > Confident Hallucination.** It's better to say "I don't know" than to fabricate.

---

## 📜 License

All contributions are published under  Apache License Version 2.0

By submitting a PR, you agree that your contribution will be licensed under  Apache Licens Version 2.0

---

## 💬 Community

- GitHub Discussions: For design debates and RFC proposals
- Issues: For bugs, feature requests, and stub implementations

---

*"인류의 영원한 서투름을 기꺼이 껴안고 함께 고뇌하는 시스템 — 이것이 우리가 정의하는 진정한 인지적 무결성이다."*

*"A system that willingly embraces humanity's eternal clumsiness and agonizes alongside us — this is what we define as true cognitive integrity."*
