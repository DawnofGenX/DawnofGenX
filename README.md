# Hi, I'm Priyansh Kansara 👋

**Applied ML & embedded systems.** 2nd-year Electronics & Telecommunication at KJ Somaiya College of Engineering (CGPA 9.15/10). I build verification and telemetry tools in Python, and I ship fixes into projects I don't maintain.

I work at the seam between applied ML and embedded: models that have to run on a CPU-only laptop, and protocols decoded off a serial line.

---

## 🔬 Projects

| | | |
|---|---|---|
| **[Vishwas](https://github.com/DawnofGenX/vishwas)** | ~34K LoC · 445 tests | Zero-cloud WhatsApp verification platform. A user messages a number; URLs, executables/APKs, documents (OCR) and images/audio get checked and answered with a plain-language verdict plus a confidence band, in 7 languages. Routing is deterministic — an LLM only narrates finished verdicts, behind a prompt-injection guard. |
| **[UARTScope](https://github.com/DawnofGenX/uartscope)** | ~13.9K LoC · 160 tests | "Wireshark for microcontrollers." Bidirectional UART/I²C/SPI/CAN/Modbus decoders, CAN from vendor DBC files, live charts, threshold alerts, session record/replay with golden-baseline diffing, plugin marketplace, MQTT bridge. |
| **[CiteSure](https://github.com/DawnofGenX/citesure)** | ~9.7K LoC · 288 tests | Local citation verifier (MCP server + CLI). Checks whether a cited source actually *supports* the claim, not just whether the link is alive. Unverifiable claims return "can't verify" instead of a hallucinated verdict. |
| **[blind-mcp](https://github.com/DawnofGenX/blind-mcp)** | ~1K LoC · 16 tests | MCP server for company research on Blind, extended from an upstream MIT scaffold. |

Everything above runs with no cloud dependency and no API keys. CiteSure's fast
path is fully offline with `--no-nli`; its NLI tier is opt-in and lazy-downloads a
local model on first use.

---

## 🌱 Open source

**3 merged PRs** into PyPA-ecosystem tooling:
- [tox-dev/filelock#752](https://github.com/tox-dev/filelock/pull/752) — `fix(read-write)`: honor instance defaults
- [tox-dev/filelock#751](https://github.com/tox-dev/filelock/pull/751) — `fix(marker)`: preserve live owners
- [pypa/pipx](https://github.com/pypa/pipx/pull/2041) — `fix(upgrade)`: don't claim "latest version" for local-path installs

**9 open and under review:** pytest, pytest-xdist, pandas, Hugging Face diffusers (×2), MCP reference servers, LMCache, Axl.

Also submitted fixes at sentry-python, setuptools, twine and towncrier.

The common thread: read the codebase, write the failing test first, make the smallest change that fixes the actual bug — not my symptom of it.

---

## 🛠️ Stack

- **Languages** — Python, C, TypeScript
- **ML/AI** — PyTorch, Hugging Face Transformers, LLM fine-tuning & evaluation, retrieval, MCP, OCR, deepfake detection
- **Backend** — FastAPI, REST, WebSockets, pytest, GitHub Actions CI
- **Embedded** — UART, I²C, SPI, CAN (DBC), Modbus, MQTT, ESP32, Raspberry Pi, Arduino, Betaflight

## 📓 Consistency

I keep a [public devlog](https://github.com/DawnofGenX/devlog) — one dated entry a day, each curating real arXiv cs.LG papers, so the learning is verifiable rather than claimed.

## 📬 Connect

- **Email** — pkansara0412@gmail.com
- **LinkedIn** — [linkedin.com/in/priyansh-kansara-a35826368](https://www.linkedin.com/in/priyansh-kansara-a35826368/)
- **Portfolio** — https://dawnofgenx.github.io
- **dev.to** — https://dev.to/dawnofgenx

---

**Open to** ML-engineer internships in applied ML, LLM inference / edge deployment, or Physical AI — available for 3-week windows from mid-December 2026.
