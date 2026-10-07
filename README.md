<div align="center">

# Pan Nie

**I build local-first AI systems** — desktop apps, agents and web products that keep your data on your own machine.

Tsinghua University · Beijing

[pan-nie.github.io](https://pan-nie.github.io) · [nathanpenny.fun](https://nathanpenny.fun) · [GitHub](https://github.com/pan-nie) · [Email](mailto:hello@nathanpenny.fun) · [X](https://x.com/NathanPenny520)

<sub>12 public repositories · 123 stars · 70 forks</sub>

</div>

---

## 🧠 Technical Strengths

**Local-first AI & agents**
- On-device inference through Ollama / LM Studio behind an OpenAI-compatible layer — no account, no telemetry, everything stays on `127.0.0.1`
- MCP tool servers exposing **64 tools**, with risk-tiered permissions (read / write / write+pay / destructive) and a human approval gate on every write action
- Long-running agent supervision: session keep-alive, SQLite-backed audit and pending-confirmation state, scheduled monitors, push notifications
- Agentic email workflows — intent → search → classify → draft → approval → send, with every action auditable and reversible

**Cross-platform desktop — C++17 / Qt 6**
- A single binary shipping both GUI and CLI, with SSE token streaming and persistent multi-session history
- File, image and PDF/docx attachments, theming, i18n, and voice interaction (ASR + TTS)
- Release engineering: PyPI packages, a Homebrew tap, and builds for Windows / macOS / Linux

**Web & backend**
- Astro sites with zero client-side JavaScript, deployed on Cloudflare Workers
- FastAPI + React services bound to loopback, TypeScript monorepos with pnpm workspaces
- Local HTTP APIs and CLIs designed so other tools (Raycast, n8n, iOS Shortcuts, AI agents) can plug in

**Machine learning, from first principles**
- 62 runnable lessons: numpy-level linear algebra and calculus → CNNs and Transformers → LLMs (tokenization, scaling laws, LoRA, alignment, KV cache, RAG, evaluation)

---

## 🚀 Featured Projects

### 📬 [Nmail](https://github.com/pan-nie/Nmail) — local-first AI email client

`Python` · `FastAPI` · `React` · `SQLite` · MIT

Multiple accounts in one inbox, AI classification and archiving, drafted replies and a daily digest, plus an agent that carries out multi-step mail chores. Every send waits for your approval, and mail never leaves your machine — it runs fully offline with Ollama. Distributed on PyPI and through a Homebrew tap.

`uvx --from nmail-app nmail` · [nmail.whizzzest.com](https://nmail.whizzzest.com) · [tap](https://github.com/pan-nie/homebrew-nmail)

### 🖥️ [LocalAIAssistant](https://github.com/pan-nie/LocalAIAssistant) — cross-platform desktop AI assistant

`C++17` · `Qt 6`

GUI and CLI in one binary: streaming replies, multi-session history, file and image attachments, themes, i18n, and a voice-interactive companion module with an emotion system and long-term memory.

### 🎓 [Tsinghua Agent](https://github.com/pan-nie/TsinghuaMCP) — long-running personal agent + MCP server

`TypeScript` · `MCP` · `SQLite`

A campus-affairs agent with 34 read-only and 30 write/monitoring tools, backed by a resident supervisor that keeps sessions alive and pushes grade, electricity, card-balance, news and course-registration alerts.

---

## 📦 More Projects

| Project | Stack | What it is |
| --- | --- | --- |
| 🧭 [TsinghuaSurvive](https://github.com/pan-nie/TsinghuaSurvive) | `JavaScript` | A student-written survival guide for Tsinghua — [tsinghua.nathanpenny.fun](https://tsinghua.nathanpenny.fun) |
| 🧠 [DeepLearningCourseForMe](https://github.com/pan-nie/DeepLearningCourseForMe) | `Jupyter` | 62 lessons of deep-learning notes and runnable code across 8 modules, paired with a video series |
| 🌐 [nathanpenny.fun](https://github.com/pan-nie/nathanpenny.fun) | `JavaScript` | My personal site and blog |
| 📄 [pan-nie.github.io](https://github.com/pan-nie/pan-nie.github.io) | `HTML` | Bilingual, print-ready CV homepage — zero build |
| 🏯 [whizzzest.com](https://github.com/pan-nie/whizzzest.com) | `JavaScript` | A digital cultural-tourism experience for 焰境·万载 — [whizzzest.com](https://whizzzest.com) |
| 🛰️ [nmail-site](https://github.com/pan-nie/nmail-site) | `Astro` | Nmail's website — zero client-side JS, on Cloudflare Workers |
| 🍺 [homebrew-nmail](https://github.com/pan-nie/homebrew-nmail) | `Ruby` | The Homebrew tap that ships Nmail on macOS |
| ✍️ [wechat-article](https://github.com/pan-nie/wechat-article) | `Python` | A self-contained skill that carries a WeChat article from topic selection to the drafts folder |

---

## 🧰 Toolbox

`Python` · `TypeScript` · `C++17` · `Qt 6` · `React` · `Astro` · `FastAPI` · `SQLite` · `Node.js` · `pnpm` · `Cloudflare Workers` · `MCP` · `Ollama / LM Studio` · `PyTorch` · `NumPy` · `Git`

---

<div align="center">

**Building local-first software in the open.**

Bug reports, ideas and pull requests are all welcome — [open an issue](https://github.com/pan-nie/pan-nie/issues) or just say [hi](mailto:hello@nathanpenny.fun).

</div>
