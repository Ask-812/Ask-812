<h1 align="center">Arnav Kshirsagar</h1>

<p align="center">
  <a href="https://ask-812.github.io">
    <img src="https://img.shields.io/badge/%F0%9F%8C%90%20Portfolio-ask--812.github.io-a78bfa?style=for-the-badge&labelColor=0b0b12" alt="Portfolio - ask-812.github.io">
  </a>
  <a href="https://ask-812.github.io/security/">
    <img src="https://img.shields.io/badge/%F0%9F%9B%A1%EF%B8%8F%20Security%20Research-%247%2C200%2B%20in%20bounty%20awards-22d3ee?style=for-the-badge&labelColor=0b0b12" alt="Security Research">
  </a>
</p>

<p align="center">
  <b><a href="https://ask-812.github.io">ask-812.github.io</a></b> &mdash; the full picture: what I built, how it works, and what I got wrong.
</p>

---

Final-year **B.Tech Mechanical Engineering** student at **IIT Guwahati** (Class of 2027, Minor in EEE)
who taught himself to ship production software, and is now choosing software engineering deliberately.

- 🏭 **Software Engineering Intern at Powertrace** (Jun 2026 – present) — backend and edge systems for a
  grid-scale battery storage platform. **33 merged PRs**: an ISA-18.2 alarm engine, a signed OTA pipeline
  with ed25519 verification and atomic rollback, a live MQTT→Redis→SSE telemetry path, and a production
  VPC egress outage I diagnosed and fixed without taking the deployed field fleet offline.
- 🛡️ **[Security research](https://ask-812.github.io/security/)** — **$7,200+ in bug bounty awards**, including
  $5,000 and $750 via HackerOne for double-spend flaws in a Bitcoin L2 protocol, and a **High-severity**
  XRP Ledger finding caused by integer truncation in fixed-point arithmetic.
- 🏆 **Codeforces Expert** — max rating **1623**, best global rank **951** (Div. 2, Round 1108).

### Selected work

| Project | What it is |
|---|---|
| 🧬 **[Ultron](https://github.com/Ask-812/Ultron)** | Artificial-life engine where each digital cell runs its own neural network, metabolises energy and signals through diffusing chemical fields. Cell differentiation and predator–prey dynamics emerge without being programmed. **85+ controlled experiments**, written from scratch with **no ML framework** — the dependency list is numpy, matplotlib and psutil. Found a sharp *candidate* phase transition in population survival at a critical resource-extraction threshold. |
| 🖥️ **[oswright](https://github.com/Ask-812/oswright)** | An **MCP server on PyPI** that lets an LLM drive a Windows desktop. Profiling showed the median observation changes only **0.012%** of screen pixels, so an incremental screen model replaced full-screen OCR: **16.9× lower token cost at 19/20 benchmark tasks, against the rival's 20/20**. DXGI Desktop Duplication bound through raw COM vtables because no Python package exposed them. **237 tests**; the fast path is Windows-only. |
| 💳 **[credit-scorecard](https://github.com/Ask-812/credit-scorecard)** | Probability-of-default scorecard over **618k Lending Club loans** — WOE binning into logistic regression, then an integer points table. Trained pre-2015 and tested out-of-time on 2015 for **Gini 0.300**. Calibration is *deliberately reported as broken* out-of-time, and PSI stayed flat at 0.0004 while the model degraded, which is exactly why PSI alone is not enough. **215 tests**. |
| 📈 **[Aurora](https://github.com/Ask-812/Aurora)** | Closed-loop notification orchestrator: **Thompson sampling** over Beta posteriors picks send-time, copy and channel per segment across **600 bandit arms**, and no template is promoted unless Bayesian and frequentist tests agree. *Team project.* An earlier version reported R² 0.94 — that was **target leakage**, and it is deleted. Finding it is the part worth discussing. |
| 🏦 **[FinSpark](https://github.com/Ask-812/FinSpark)** | Requirements-to-deployment pipeline for lending integrations: an LLM parser maps intent onto **10 KYC, credit-bureau and payments APIs** across **37 hooks**, with simulate, approve, deploy and rollback. JWT-scoped multi-tenancy and Fernet-encrypted credential vaults. *Team of 4.* **248 tests**. |
| 🩺 **[Mediguide](https://github.com/Ask-812/Mediguide)** | Question answering over uploaded medical PDFs: sentence-embedding retrieval grounds each generation, then GPT-2 fine-tuned with **LoRA** under 4-bit quantisation for **+20% ROUGE-L** over the base model. |

### Tech

`Python` `C/C++` `TypeScript` `Java` `Kotlin` `SQL` · `FastAPI` `React` `PyTorch` `scikit-learn` · `PostgreSQL` `TimescaleDB` `Redis` `MongoDB` · `AWS` `Docker` `MQTT` `Modbus` `CI/CD`

### Elsewhere

[![Portfolio](https://img.shields.io/badge/-ask--812.github.io-a78bfa?style=flat&logo=astro&logoColor=white)](https://ask-812.github.io)
[![LinkedIn](https://img.shields.io/badge/-ask812-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/ask812)
[![Codeforces](https://img.shields.io/badge/-Expert%201623-1F8ACB?style=flat&logo=codeforces&logoColor=white)](https://codeforces.com/profile/ask812)
[![Email](https://img.shields.io/badge/-arnavsk812%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:arnavsk812@gmail.com)
