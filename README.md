I am a Computer Science and Mathematics student at the University of Maryland, College Park, with an ACES Cybersecurity minor and CompTIA Security+.

I build Python systems across security engineering and backend software. My current work covers application security, authorization, authentication, vulnerability analysis, developer tooling, and reproducible evaluation.

## Selected work

### [Agent Least Privilege](https://github.com/VaghesanSundaram/agent-least-privilege)

A default-deny authorization monitor for tool-using agents. It binds calls to task-scoped functions, resources, arguments, approvals, and call limits, with append-only audit events and deterministic replay.

- 93 automated tests with Hypothesis property checks
- Strict mypy and Ruff checks on Windows and Linux
- 60-episode synthetic evaluation across three permission models
- 0/10 unauthorized state-changing effects under task-conditioned enforcement, compared with 4/10 unrestricted and 6/10 with a static action allowlist

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
