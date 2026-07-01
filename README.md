# CPC-Suite

**Signed bundle installers for the AIWander / CPC server suite.**

One download, several servers: each installer copies the signed binaries, installs their skills, and wires the MCP entries into Claude Desktop and Claude Code (existing entries you added yourself are preserved and restored on uninstall).

All binaries and installers are Authenticode-signed — publisher **Joseph Wander** (Azure Trusted Signing).

---

## Bundles

### CPC Core Trio — `CPC-Core-Trio-Setup-<arch>.exe`
The [aiwander.ai](https://aiwander.ai) suite in one installer:

| Server | What it gives your AI |
|---|---|
| [AI-Hands](https://github.com/AIWander/AI-Hands) | Browser control, Windows UI automation, screenshots, vision, OCR |
| [Voice-Command](https://github.com/AIWander/Voice-Command) | Speak to your AI, hear it narrate as it works (talk side; listening needs the Voice-Command Python server) |
| [Programmer-Wander](https://github.com/AIWander/Programmer-Wander) | Local dev shell: files, shells, full git, WSL, HTTP, transforms — the offload layer for mechanical work |

### CPC Ops Suite — `CPC-Ops-Suite-Setup-<arch>.exe`
The operations pair:

| Server | What it gives your AI |
|---|---|
| [manager-universal](https://github.com/AIWander/manager-universal) | Multi-AI delegation (Claude Code / Codex / Gemini) with a built-in web dashboard (`manager:dashboard_open`) |
| [ops](https://github.com/AIWander/ops) | PowerShell + Bash exec, persistent sessions, breadcrumb operation tracking, reminders |

---

## Which file do I download?

| Your Windows machine | Files |
|---|---|
| Intel / AMD (most PCs) | `*-Setup-x64.exe` |
| Snapdragon / Windows on ARM | `*-Setup-arm64.exe` |

Run the installer, then restart Claude Desktop / Claude Code. Single-product installers live on each server's own repo releases.

---

## Related

- [GrokCLI](https://github.com/AIWander/GrokCLI) — CPC behavioral skills + lifecycle hooks for Grok Build CLI and Claude Code (protocol layer)
- [StartHERE](https://github.com/AIWander/StartHERE) — the CPC tour and install path
- [workflow](https://github.com/AIWander/workflow) · [local](https://github.com/AIWander/local) — additional single-product servers

Apache-2.0 · part of the AIWander / CPC ecosystem.
