# Changelog

All notable changes to BlackCortex Lite are documented here.

---

## [1.0.0] — 2026-03-10

### Initial Release

**Core**
- Multi-user local chat with SQLite storage
- Python http.server backend, no external dependencies
- Runs on Windows (exe) and macOS/Linux (python main.py)
- System tray icon with LAN URL notification (Windows)

**Models**
- Ollama integration — local model inference
- Model Catalog with hardware compatibility scoring (VRAM/RAM color coding)
- PIN-protected model install/delete
- Support for NVIDIA (native), AMD (Vulkan), Intel Arc (IPEX-LLM), CPU-only

**Cloud APIs**
- Google Gemini (free tier)
- Per-user API keys with optional sharing
- Priority rule: own key always wins over shared key

**Chat**
- PDF upload and context extraction (up to 5 MB)
- Voice input (local desktop and mobile)
- Chat export to .txt
- Inline chat rename (pencil icon on hover)
- EU/US timestamp format toggle
- Dark/light chat theme toggle
- Built-in system prompts: No Prompt, Assistant, Coder
- Custom persona support

**UI**
- Dark theme, gold (#ffd700) accent
- LAN IP display in Model Catalog
- Real-time hardware monitor (CPU, GPU, RAM, disk)

---

*For older versions, see [black-cortex.com](https://www.black-cortex.com/)*
