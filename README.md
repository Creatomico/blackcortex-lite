# BlackCortex Lite

> **This is a proprietary closed-source release. GitHub is used only for distribution and documentation. Full source code is not public.**

**Local AI chat for home networks**

BlackCortex Lite is a self-hosted, multi-user AI chat application that runs entirely on your machine — no cloud, no subscriptions, no data leaving your network.

Built for home use. Connect everyone on your LAN, share one machine, keep full control of your data.

> ⚠ **Designed for trusted home networks only.** Not recommended for public or corporate deployment — no SSL encryption, no role-based access control, no audit logging.

---

## Screenshots

![Chat](screenshots/chat.png)
*PDF analysis — ask questions about any document*

![Model Catalog AMD](screenshots/model-catalog.png)
*Model Catalog — AMD Vulkan Ready, hardware compatibility scoring*

![Model Catalog NVIDIA](screenshots/model-catalog-nvidia.png)
*Model Catalog — NVIDIA CUDA + Tensor Cores*

![Cloud APIs](screenshots/cloud-apis.png)
*Cloud APIs — Google Gemini free, Lite+ unlocks more*

![Custom Persona](screenshots/custom-persona.png)
*Custom Persona — give your AI a name and personality*

![Help](screenshots/help.png)
*Built-in Help — 9 sections, always available*

---

## Features

- 🖥️ **Runs locally** — powered by Ollama, no internet required for local models
- 👥 **Multi-user** — each person gets their own chat history and settings
- 🌐 **LAN access** — anyone on the network connects via browser, no install needed
- 🤖 **Model Catalog** — browse and install Ollama models with hardware compatibility scoring
- ☁️ **Cloud APIs** — Google Gemini support in free tier (Lite+ unlocks more)
- 📄 **PDF chat** — attach documents and ask questions about them
- 🎤 **Voice input** — dictate messages on mobile and local desktop
- 🔒 **PIN protection** — model install/delete protected from accidental changes
- 🌙 **Dark UI** — gold accent, built for extended use

---

## Hardware Support

| GPU | Status |
|-----|--------|
| NVIDIA | ✅ Native |
| AMD | ✅ Vulkan (`OLLAMA_VULKAN=1`) |
| Intel Arc | ⚠️ Via IPEX-LLM |
| CPU only | ✅ Supported (slower) |

---

## Requirements

- Windows 10/11
- [Ollama](https://ollama.com) installed
- macOS and Linux versions coming soon

---

## Download

👉 **[black-cortex.com](https://www.black-cortex.com/)** — latest release, changelog, and install guide.

---

## Editions

| | **Lite** (Free) | **Lite+** | **Coming in v1.x** |
|---|---|---|---|
| Local Ollama models | ✅ | ✅ | |
| Google Gemini | ✅ | ✅ | |
| OpenAI, Claude, xAI, DeepSeek, Qwen | ❌ | ✅ | |
| PDF chat | ✅ up to 5 MB | ✅ 5 MB+ | |
| Office files (Word, Excel) | ❌ | ✅ 5 MB+ | |
| Web search | ❌ | ✅ | |
| Cross-chat memory | ❌ | ❌ | ✅ v1.x |
| Image generation (local) | ❌ | ❌ | ✅ v1.x |
| Updates | ❌ | ✅ | |

---

## Contact

📧 hello@black-cortex.com
🌐 [black-cortex.com](https://www.black-cortex.com/)

---

## About

BlackCortex Lite is an indie project. Creatomico LLC is a one-person company — no investors, no team, no VC money. Just one developer building tools they actually want to use.

This means:
- **No roadmap pressure** — features ship when they're ready and stable
- **No open-source obligation** — proprietary model funds continued development
- **Support is best-effort** — not a helpdesk SLA

If you're here to demand open source, complain about antivirus warnings, or ask why Linux isn't supported yet — please read [INSTALL.md](INSTALL.md) first. Most questions are already answered there.

Genuine bug reports and feedback are welcome at hello@black-cortex.com.

---

## License

Copyright © 2026 Creatomico LLC. All rights reserved.

This software is proprietary. Source code is not available for redistribution, modification, or commercial use without explicit written permission from Creatomico LLC.
