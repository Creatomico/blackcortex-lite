# Installation Guide

> ⚠ **Designed for trusted home networks only.** Not recommended for public or corporate deployment — no SSL encryption, no role-based access control, no audit logging.

---

## Windows (recommended)

1. Download **BlackCortex-Lite.exe** from [black-cortex.com](https://www.black-cortex.com/)
2. Install [Ollama](https://ollama.com) — required for local AI models
3. Run `BlackCortex-Lite.exe`
4. The app opens automatically in your browser at `http://localhost:8000`

> **Windows SmartScreen** will warn that the file is from an unknown publisher — click **More info → Run anyway**. This is expected for unsigned applications and the warning disappears as the app gains download reputation.

> **Windows Firewall** will ask to allow network access on first launch — click **Allow access** for both private and public networks if you want LAN access from other devices. If you only use the app locally, private network is sufficient.

### AMD GPU
Set the environment variable before starting Ollama:
```
set OLLAMA_VULKAN=1
```

### Intel Arc GPU
Standard Ollama does not support Arc natively. Use **IPEX-LLM Portable ZIP**:
- Download from [github.com/intel/ipex-llm](https://github.com/intel/ipex-llm) → Releases
- Extract and run Ollama from that folder
- Set `OLLAMA_NUM_GPU=999` to ensure all layers run on GPU

---

## macOS / Linux

Native builds for macOS and Linux are currently in development. Follow [black-cortex.com](https://www.black-cortex.com/) for release announcements.

---

## LAN Access

Once running, other devices on your network can connect via browser using your machine's local IP address shown in the Model Catalog (e.g. `http://192.168.1.100:8000`). No installation needed on other devices.

---

## Requirements

| | Minimum |
|---|---|
| OS | Windows 10/11 (macOS and Linux coming soon) |
| RAM | 8 GB (16 GB recommended) |
| GPU | Optional — CPU-only mode supported |
| Ollama | Latest version from ollama.com |

---

## Uninstall

Delete `BlackCortex-Lite.exe` and `blackcortex_lite.db` (contains all chats and settings).
