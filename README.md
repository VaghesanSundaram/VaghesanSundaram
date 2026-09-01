I am a Computer Science and Mathematics student at the University of Maryland, College Park, with an ACES Cybersecurity minor and CompTIA Security+.

I build Python systems across security engineering and backend software. My current work covers application security, authorization, authentication, vulnerability analysis, developer tooling, and reproducible evaluation.

## Selected work

### [Agent Least Privilege](https://github.com/VaghesanSundaram/agent-least-privilege)

A local Python authorization gateway for filesystem tools exposed through the Model Context Protocol (MCP). An agent connects through the proxy, which checks a trusted launch-time policy before forwarding each tool call.

- Enforces allowed paths, exact arguments, and per-tool call quotas
- Serializes quota reservations and records redacted audit events for completed, denied, timed-out, and unknown outcomes
- Unit and actual proxy-to-server integration tests with strict mypy/Ruff and Windows/Linux CI
- In an [earlier synthetic feasibility run](https://github.com/VaghesanSundaram/agent-least-privilege/blob/main/docs/evaluation.md), prevented filesystem effects from all 12 unauthorized proposals while 10/12 executed attack tasks and 24/24 executed controls completed

### [CTI Claim Provenance](https://github.com/VaghesanSundaram/cti-claim-provenance)

A 64-question, point-in-time cyber threat intelligence benchmark across 24 dependency groups. The release records source authority, time cutoffs, evidence spans, source hashes, typed expected answers, abstention cases, and human review.

- Privacy-safe 192-cell result projection
- Offline verifier for corpus, split, documentation, privacy, and aggregate checks
- Evidence binding increased from 83.3% to 86.5% under constrained output
- Exact-answer matching decreased from 33.3% to 26.0%, showing that structured output did not solve temporal answer construction

### [Static SAST Triage Agent Benchmark](https://github.com/VaghesanSundaram/sast-alert-triage-benchmark)

A reproducible Bandit alert-triage benchmark with a 949-row dataset, a 265-row held-out split, trained and API-model comparisons, leakage checks, and published result artifacts.

### [Keystroke Authentication](https://github.com/VaghesanSundaram/keystroke-auth)

A two-service Flask authentication system using typing cadence, JWT-bound service exchange, SQLite, bcrypt fallback, rate limiting, and an end-to-end verification path.

## Technical toolkit

- **Languages:** Python, Java, C++, C, Assembly, Rust
- **Security:** application security, secure code review, vulnerability analysis, authentication and authorization review, evidence and severity triage
- **Engineering:** Pydantic, pytest, Hypothesis, mypy, GitHub Actions, Flask, SQLite, Git, Linux
- **Tools:** Semgrep, Wireshark, PowerShell; Burp Suite and Nmap in controlled labs

## Links

- [Portfolio](https://vaghesansundaram.github.io/Portfolio/)
- [LinkedIn](https://www.linkedin.com/in/vaghesan-sundaram-a2b999231/)
