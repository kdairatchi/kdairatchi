# kdairatchi

Bug-bounty hunter who builds tools. Crystal-native offensive security, autonomous hunt pipelines, and hardware-adjacent frameworks for offline research.

Work surfaces at **[prowlrbot.com](https://prowlrbot.com)**.

---

## Shipping

**[quartz](https://github.com/kdairatchi/quartz)** · Crystal · Flipper Zero dev framework.
Single static binary. Offline-first. Federated `.sig` bundles shared peer-to-peer, not uploaded to someone else's lab. Parser, host-side simulator, native FAP build, serial RPC.

**[CyberBox](https://github.com/ProwlrBot/CyberBox)** · Docker · Security workspace.
160+ tools, Caido proxy plugin, dual-LLM routing (Claude + Ollama), plugin marketplace, AI guardrails. Latest: [v0.2.1](https://github.com/ProwlrBot/CyberBox/releases/tag/v0.2.1).

**[ProwlrBot](https://github.com/ProwlrBot/prowlrbot)** · Python + Go · Multi-agent platform.
Bash pipelines chain security binaries into recon → vulnscan → triage → report. AI agents read tool output; no LLM wraps a CLI. Spine is FastAPI, console is shadcn/Tailwind.

## Tooling (open source)

| Repo | Stack | What it does |
|---|---|---|
| [flaw](https://github.com/kdairatchi/flaw) | Crystal | SAST for bug-bounty targets — regex + AST rules, plugin-friendly |
| [ghactor](https://github.com/kdairatchi/ghactor) | Go | GitHub Actions hardening CLI: lint · fix · SHA-pin · trial · trail |
| [Prowlrview](https://github.com/ProwlrBot/prowlrview) | Crystal | Intercepting proxy + live attack-surface graph, Lua plugins |
| [ROAR Protocol](https://github.com/ProwlrBot/roar-protocol) | Python | Agent-to-agent communication standard — MCP + A2A + ACP + ANP in one |
| [gf-patterns](https://github.com/kdairatchi/gf-patterns) | regex | Opinionated bug-bounty grep patterns |
| [nuclei-templates-custom](https://github.com/kdairatchi/nuclei-templates-custom) | YAML | Custom nuclei templates from live hunts |

## Stack

```
Languages   Crystal · Rust · Go · Python · TypeScript
Security    Caido · Nuclei · 160+ Go binaries · custom Crystal tooling
Agents      Claude Code · Ollama · MCP · ROAR
Hardware    Flipper Zero · GL-AR150 · RTL-SDR
Infra       Cloudflare Pages · Fly.io · Docker · WSL2
Notes       Obsidian second-brain — methodology, CVEs, red/blue playbooks
```

## Focus

Autonomous recon → triage → report pipelines that make one hunter move like a team.
Prompt-injection guardrails and secret redaction for offensive tooling.
Supply-chain posture for the bug-bounty toolchain itself — pin every action, audit every dependency.
Crystal-native security tools.

## Currently learning

- Crystal macros and AST work for flaw's rule engine
- Rust for the `roar` transport fast-path
- Flipper firmware internals (FuriHAL, protobuf RPC, native FAPs)

---

<sub>
<a href="https://prowlrbot.com">prowlrbot.com</a> ·
<a href="https://kdaistack.pages.dev">kdaistack</a> ·
<a href="https://github.com/ProwlrBot">@ProwlrBot</a> ·
<a href="mailto:prowlr@proton.me">prowlr@proton.me</a>
</sub>
