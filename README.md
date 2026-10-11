# Jorge Alonso Alfonso

Developer and sysadmin at [EnfoquesTIC](https://enfoquestic.com), based in Galicia, Spain.

At work I build whatever a project needs, which usually means more than one layer. On an IoT
platform for wearables I've written the Go services, the Next.js portal, the Wear OS app that
handles calls and sends health telemetry over MQTT, and the ESP32 firmware and Flutter app that
talk to each other over BLE. I've also built a Python service that unfolds sheet-metal parts from
STEP files with OpenCascade and the DIN 6935 K factor, WordPress plugins, and MCP servers that let
AI agents query SAP Business One on HANA, SQL Server and MySQL, some of them called from n8n
workflows.

I also run the Linux side: Plesk hosting servers, DNS and mail (SPF, DMARC, relay through AWS SES),
Docker and Portainer, monitoring with Prometheus and Grafana, identity with Zitadel, and security
work that ranges from server audits to cleaning up compromised WordPress and PrestaShop sites. If I
have to do something by hand twice, I usually end up writing a tool for it, and most of the public
code below started that way.

[![LinkedIn](assets/linkedin-badge.svg)](https://www.linkedin.com/in/jorgealonsoalfonso/)

---

## Projects

### Security and system administration

| Project | What it does | Stack |
|---|---|---|
| [Vallumix](https://github.com/jorgealonsodev/vallumix) | Modular Linux hardening engine for CIS Benchmark compliance. It applies idempotent controls, writes auditable reports and rolls back safely, with no runtime dependencies. Published on [crates.io](https://crates.io/crates/vallumix). | Rust |
| [NoPass](https://github.com/jorgealonsodev/nopass) | Grants and revokes passwordless `sudo` with an explicit expiry (on a timer, at reboot or until revoked), from a tray app or with root commands on a headless host. | Rust |
| [net-audit-scanner](https://github.com/jorgealonsodev/net-audit-scanner) | Scans the local network and fingerprints the devices connected to it. | Rust |
| [stowkeeper](https://github.com/jorgealonsodev/stowkeeper) | Encrypted backups with rotation and integrity checks. | Shell |
| [terraform-aws-web-infra](https://github.com/jorgealonsodev/terraform-aws-web-infra) | Terraform that provisions a three-tier web architecture on AWS. | HCL |
| [randkeykit](https://github.com/jorgealonsodev/randkeykit) | Generates keys, passwords and tokens in the browser with the Web Crypto API. Nothing is sent to a server or stored. | JavaScript |

### Tooling for AI-assisted development

| Project | What it does | Stack |
|---|---|---|
| [OpenCode Go Monitor](https://github.com/jorgealonsodev/opencode-go-monitor) | VS Code extension that shows OpenCode Go quota as it changes, predicts the trend and has an English and Spanish UI. | TypeScript |
| [Usage Monitor for Claude (Linux)](https://github.com/jorgealonsodev/usage-monitor-for-claude-linux) | GTK tray app that shows how much of your Claude session and weekly limits is left. Ships as a `.deb`. | Python |
| [engram-router](https://github.com/jorgealonsodev/engram-router) | Sends each repository's [Engram](https://github.com/Gentleman-Programming/engram) memories to the right cloud. It fails closed, so work and personal data stay apart. | Shell |
| [ODD Ledger](https://github.com/jorgealonsodev/odd-ledger) | Read-only editor view of Markdown task documents: each feature, its tasks, the evidence that closed them and the next step. | TypeScript |
| [notebooklm-mcp-server](https://github.com/jorgealonsodev/notebooklm-mcp-server) | MCP server for NotebookLM. | Go |

---

## Toolbox

| Area | Tools |
|---|---|
| Languages | TypeScript, Go, Kotlin, Python, Rust, Dart, C++, PHP, Bash |
| Web | Next.js, WordPress, PrestaShop |
| Mobile and IoT | Flutter, Wear OS, ESP32, BLE, NFC, MQTT, NATS |
| Infrastructure | Linux, Docker, Portainer, Plesk, Nginx, Apache, DNS and mail, AWS, Terraform, Zitadel, n8n |
| Observability | Prometheus, Grafana, Loki |
| Data | PostgreSQL and TimescaleDB, MySQL, SQL Server, SAP HANA (SAP Business One) |
| AI tooling | MCP servers, Claude Code, OpenCode |
| Practices | Security audits and incident response, pentesting with Strix, CI with GitHub Actions, spec-first and test-first development |

---

<sub>If you want to talk about Linux, IoT or AI agents, you can reach me on [LinkedIn](https://www.linkedin.com/in/jorgealonsoalfonso/).</sub>
