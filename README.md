**Security × AI engineer.** I build SIEM, SOAR and EDR at work, then rebuild the same things from scratch on my own hardware — to find out where they actually break.

📝 [Blog](https://adorahelen.github.io) · 🛰 [siem-trinity-public](https://github.com/adorahelen/siem-trinity-public) · 🤖 [ai-console-public](https://github.com/adorahelen/ai-console-public)

## Experience

**AI Security Engineer** · Enterprise SIEM & SOAR · `2026.02 – present`

**Security Engineer** · DLP & Data Security · `2024.12 – 2025.08`

---

## Featured Projects

### 🤖 1. AI Threat Detection & Incident Analysis Stack
> [`siem-trinity-public`](https://github.com/adorahelen/siem-trinity-public) · public · `02-detection/` · `03-intelligence/`
- **ML Detector**
  - Applied unsupervised learning models for flow anomaly detection and implemented real-time C2 beacon detection logic
  - Developed a DGA domain classifier and IP risk scoring engine using statistical feature extraction
- **LLM Analyst**
  - Designed a LangGraph-based ReAct agent architecture to automate security monitoring workflows
  - Built a KISA guideline and MITRE ATT&CK knowledge base in Vector DB to generate reliable Korean security reports

### 📡 2. Home Server SIEM
> [`siem-trinity-public`](https://github.com/adorahelen/siem-trinity-public) · public · `01-collection/`
- Designed a network analysis layer with Suricata NIDS + Zeek and built a log ingestion pipeline on Loki
- Implemented a multi-layered defense architecture: Wazuh HIDS (MITRE ATT&CK mapping) + ModSecurity WAF (OWASP CRS) + fail2ban
- Built a Grafana dashboard with 30+ panels — GeoIP attack world map, Top attacker IPs, WAF rule trends
- Four layers and a SOC console on a single host: ten containers, exactly one exposed port, everything else bound to localhost

### 🧠 3. On-Prem LLM Agent Console
> [`ai-console-public`](https://github.com/adorahelen/ai-console-public) · public · MIT
- Fixed engine, swappable domain: prompts, knowledge and model are three cartridge slots, so a new domain costs no code change
- RAG on BGE-M3 dense retrieval + ColBERT 2-way RRF reranking, vectors in Qdrant
- Serves through a local `llama-server` or any OpenAI-compatible API; `install.sh` detects VRAM/RAM, picks a preset, registers systemd and waits for readiness
- Verified end to end on a clean VM with no GPU — install, model load, file auth, wizard generation, chat template, RAG retrieval

### 🔐 4. Self-Hosted Security Platform
> `dodgers-labs` · private — access on request
- **Privacy Shield** — Built a PII detection and masking pipeline using spaCy NER and Korean regex (PDF/DOCX/Image)
- **Doc Forensics** — Developed a metadata forensics engine with Apache Tika and semantic search via ChromaDB
- **Observability** — Implemented distributed tracing with OpenTelemetry + ClickHouse + Jaeger and a custom monitoring UI

---

## Research

**First author** — *User behaviour analysis of Threads from a digital forensics perspective*
CISC-W'25 (Korea Institute of Information Security & Cryptology), paper #328, oral session "Digital Forensics I"
**KISTI Director's Award**

Recovered direct-message bodies stored in plaintext on a rooted Android device, and showed that a procedure reading only the main database misses the newest messages held in the write-ahead log.

---

Most of my repositories are private — the two linked above are the public editions. Happy to grant access on request.
