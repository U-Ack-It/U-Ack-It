# Hi, I'm Olivier 👋

I build **AI agent systems with the safety written in code**: the AI proposes, plain code decides, and every decision leaves a record. Based in Miami. Before AI, I spent 9 years coordinating construction crews in Paris and 11 years as a network administrator, so I build for real operations, not demos.

🌍 French (native) · English (fluent) · Spanish (conversational)

---

### What I'm building

| Project | What it is |
|---|---|
| **[Obrava](https://github.com/U-Ack-It/obrava)** *(new · working name)* | A bilingual chief of staff for small construction companies: crew chat, job photos, and an assistant that turns calls, texts and voice notes into tasks and safe actions. Runs on real phone calls in the lab: **533 checks, 235 sabotage tests, all caught.** This repo is a first look plus three safety modules with tests. |
| **[CHANCO OS](https://github.com/U-Ack-It/chanco-os)** | My local-first AI operating system: knowledge graph, overnight AI investigator, evidence grading, a morning report. Case study plus its safety core (gate, safe self-repair, chunker) with tests. |
| **[two-brain-relay](https://github.com/U-Ack-It/two-brain-relay)** | A task runner that alternates a cloud LLM and a local LLM on the same job, under a hard daily spend cap, with a handoff protocol so neither the context window nor the budget runs out. |
| **[ouroboros.v2](https://github.com/U-Ack-It/ouroboros.v2)** | An algorithmic paper-trading system with a Smart-Money-Concepts signal layer and LLM decision gates. |
| **[muni_scanner](https://github.com/U-Ack-It/muni_scanner)** | A municipal-bond anomaly detector that flags small issues paying well above their peer average. |
| **[sovereign-ops-intelligence](https://github.com/U-Ack-It/sovereign-ops-intelligence)** | An operations-intelligence toolkit for key rotation and secure automation baselines. |

---

### Latest: AI governance & client-data protection
In **CHANCO OS** (private parts, demo on request), client confidentiality is enforced in code:

- **Data-loss prevention for AI:** account numbers, card data, credentials and private client details are stopped or masked before any request leaves the machine; validated live end to end.
- **Audit trail by design:** every AI request is recorded in a tamper-evident log, so any change or deletion is detectable at review.
- **Independent testing:** an outside tester's blind evaluation scored version 1 at **43%**; every gap was closed and locked in as a permanent control test.
- **Controls in code, not in instructions:** when the AI tried to bypass a source restriction, the system refused it automatically.
- **116 automated tests** gate every change; nothing goes live unless all pass.

*Former Ritz-Carlton VIP client-services professional (UHNW clientele), now combining client discretion with AI engineering. Code available for review in interviews.*

---

### How I work

- **The AI proposes, plain code decides.** A rule in a prompt is a wish; a rule in code is a wall. Money, files and deletes go through gates the AI can't change.
- **Proof over promises.** Every feature is tested in a lab first, then **break tests** sabotage each rule on purpose to prove the tests notice.
- **Everything on the record.** Append-only, hash-chained logs, so any later edit is visible.
- **Cost-aware by default.** Budget caps, spend ledgers, and local models first, so automation stays affordable.
- **Standard library first.** Small, auditable tools over heavy frameworks: easy to read, easy to run anywhere.

### Tech

`Python` · `LLM orchestration (Claude, local models)` · `Whisper` · `Twilio` · `FastAPI / Flask` · `SQLite` · `Qdrant` · `Neo4j` · `systemd` · `Linux`

---

📫 Open to AI engineering, AI operations and AI governance roles, including in wealth management. [LinkedIn](https://www.linkedin.com/in/olivier-boukli-2a82b146)
