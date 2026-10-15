<h1 align="center">Hi, I'm Jorge 👋</h1>

<p align="center">
  Developer and sysadmin at <a href="https://enfoquestic.com">EnfoquesTIC</a> · Galicia, Spain
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/jorgealonsoalfonso/"><img src="assets/linkedin-badge.svg" alt="LinkedIn"></a>
</p>

<p align="center">
  <img src="assets/stack-languages.svg" alt="Go, TypeScript, Kotlin, Python, Rust, Dart, C++, PHP, Bash"><br>
  <img src="assets/stack-platforms.svg" alt="Next.js, WordPress, Flutter, Android, Arduino, Linux, Docker, Nginx"><br>
  <img src="assets/stack-ops.svg" alt="AWS, Terraform, Prometheus, Grafana, GitHub Actions, PostgreSQL, MySQL">
</p>

At work I build whatever a project needs, which usually means more than one layer. If I have to do
something by hand twice, I usually end up writing a tool for it, and most of the public code below
started that way.

## What I work on

<table>
<tr>
<td width="50%" valign="top">

### IoT and mobile

- Go services and Next.js portal for an IoT platform for wearables
- Wear OS app that handles calls and sends health telemetry over MQTT
- ESP32 firmware and a Flutter app that talk to each other over BLE

</td>
<td width="50%" valign="top">

### Backend and AI

- MCP servers that let AI agents query SAP Business One on HANA, SQL Server and MySQL
- AI agent workflows in n8n
- Python service that unfolds sheet-metal parts from STEP files (OpenCascade, DIN 6935 K factor)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Linux and hosting

- Plesk hosting servers, Nginx and Apache
- DNS and mail: SPF, DMARC, relay through AWS SES
- Docker and Portainer, Prometheus and Grafana, Zitadel

</td>
<td width="50%" valign="top">

### Security

- Server audits and pentests with Strix
- Cleanup of compromised WordPress and PrestaShop sites
- Linux hardening against CIS Benchmarks with [Vallumix](https://github.com/jorgealonsodev/vallumix)

</td>
</tr>
</table>

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

## Also in the toolbox

| Area | Tools |
|---|---|
| Mobile and IoT | Wear OS, ESP32, BLE, NFC, MQTT, NATS |
| Data | TimescaleDB, SQL Server, SAP HANA (SAP Business One) |
| Platforms | Plesk, Portainer, Apache, Zitadel, n8n, PrestaShop, Loki |
| AI tooling | MCP servers, Claude Code, OpenCode, Pi, Gentle Shell |
| Practices | Incident response, spec-first and test-first development |

---

<sub>If you want to talk about Linux, IoT or AI agents, you can reach me on [LinkedIn](https://www.linkedin.com/in/jorgealonsoalfonso/).</sub>
