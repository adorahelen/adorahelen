## Experience

**AI Security Engineer** · Enterprise SIEM & SOAR · `2026.02 – present`

**Security Engineer** ·  DLP & Data Security · `2024.12 – 2025.08`

---

## Featured Projects

### 📡 1. Home Server SIEM 

Enterprise-grade SIEM on a single Home server using open-source only.

- Grafana (16+ panels) — SSH brute-force, Top attacker IPs, GeoIP world map, WAF rule trends
- Access: Tailscale (Zero Trust VPN mesh)
- Network: Suricata NIDS + Zeek → Loki + Promtail + Grafana
- Host: UFW → fail2ban → Wazuh HIDS (MITRE ATT&CK) → Loki + Promtail + Grafana
- Application: ModSecurity WAF (OWASP CRS) → Loki + Promtail + Grafana

### 🔐 2. Security Platform 

Fully Dockerized security platform — single public port, local LLM only, non-root containers, admin-approved signup.

- **Privacy Shield** · **Doc Forensics** · **RAG Chat** — PII masking, forensic metadata analysis, local LLM via Ollama
- Full observability: custom-built monitoring UI with OpenTelemetry + ClickHouse + Prometheus
---