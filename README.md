<h1 align="center">Hi, I'm takeshy 👋</h1>

<p align="center">
  Software engineer in Yokohama, Japan — building <b>local-first AI tooling</b><br>
  for Obsidian, the terminal, and the desktop.
</p>

<p align="center">
  <a href="https://zenn.dev/takeshy"><img alt="Zenn" src="https://img.shields.io/badge/Zenn-3EA8FF?style=for-the-badge&logo=zenn&logoColor=white"></a>
  <a href="https://x.com/takeshy"><img alt="X" src="https://img.shields.io/badge/@takeshy-000000?style=for-the-badge&logo=x&logoColor=white"></a>
</p>

---

### 🧭 What I'm into

- 🧠 **AI that stays on your machine** — LLM chat, RAG, and workflow automation that run against your own vault, your own files, your own keys.
- 🔌 **Obsidian plugins** — a family of "Hub" plugins bringing chat, MCP servers, semantic search, dashboards, and WYSIWYG editing into the vault.
- 🛠️ **Small, dependency-free Go tools** — MCP servers, log monitors, file watchers, a PDF splitter. Single binary, no runtime.
- ⌨️ **Japanese input & editor tooling** — lightweight SKK for the browser, desktop, Omarchy, and Neovim, because the keyboard is where the work happens.

---

### 🧩 Spotlight: kakeratta

<p align="center">
  <a href="https://github.com/takeshy/kakeratta"><img src="https://raw.githubusercontent.com/takeshy/kakeratta/main/frontend/public/logo.svg" alt="kakeratta" width="304" height="80"></a>
</p>

<p align="center">
  <b>You cannot search for what you forgot exists.</b><br>
  A personal AI timeline that brings it back to you.
</p>

<table>
<tr>
<td width="60%" valign="top">

**Ka-ke-ratta** — the name for tossing in a *kakera*, a fragment.
Toss in fragments of your day as text, photos, URLs or speech. **Personas**, one for each person or interest you care about, remember what matters to them and speak up when it matters.

- 🧠 **A separate memory for each persona** — no interest gets diluted by the others; people are reached by name and keyword matching, not an LLM's guess.
- 🤫 **Silence is the default** — a persona replies only when it has something worth saying. A quiet timeline means the app is working.
- 🔍 **Memory you can trace and review** — facts link back to your posts; records come back asking *keep, postpone or forget?*
- 🌱 **Personas that grow with you** — when a new topic builds up, a persona suggests spinning it off into its own.
- 🔌 **Plays well with others** — Alexa voice posts, Google Calendar / Gmail via a self-hosted bridge, external agents and tools over MCP, Bluesky sharing, push reminders, offline posting.

Built with Go and React on Google Cloud (Firestore, Pub/Sub, Cloud Tasks).

<p>
  <a href="https://kakeratta.net/lp/?lang=en"><img alt="Try it" src="https://img.shields.io/badge/▶_Try_it-kakeratta.net-FF7A59?style=for-the-badge"></a>
  <a href="https://youtu.be/7BB3MnY8uBI"><img alt="Demo" src="https://img.shields.io/badge/Demo-YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white"></a>
  <a href="https://devpost.com/software/kakeratta"><img alt="Devpost" src="https://img.shields.io/badge/Devpost-003E54?style=for-the-badge&logo=devpost&logoColor=white"></a>
</p>

→ [Repository](https://github.com/takeshy/kakeratta) · [Manual](https://kakeratta.net/manual/?lang=en) · [Design notes](https://github.com/takeshy/kakeratta/blob/main/docs/design/technical.md) · [Lessons from what the AI got wrong](https://github.com/takeshy/kakeratta/blob/main/docs/design/ai-lessons.md)

</td>
<td width="40%" valign="top" align="center">

<a href="https://youtu.be/7BB3MnY8uBI"><img src="https://raw.githubusercontent.com/takeshy/kakeratta/main/docs/captures/en/timeline.png" alt="Fragments and persona replies on the kakeratta timeline" width="300"></a>

</td>
</tr>
</table>

---

### 🌟 What I'm building right now

<table>
<tr>
<td width="50%" valign="top">

#### 🖥️ [kiokuflow-desktop](https://github.com/takeshy/kiokuflow-desktop)

![Main focus](https://img.shields.io/badge/⚡_main_focus-8E75B2?style=flat-square)

A **local-first desktop workspace** that turns your notes, documents, and workflows into context for AI.

Everything I've learned from the Obsidian plugins, rebuilt as a standalone app — your files stay yours, the AI comes to them. This is where most of my energy goes from here on.

→ Extended by [gemihub-gdrive](https://github.com/takeshy/gemihub-gdrive), [hub-ronginus](https://github.com/takeshy/hub-ronginus), [hub-accounting](https://github.com/takeshy/hub-accounting), [hub-audio-score](https://github.com/takeshy/hub-audio-score)

</td>
<td width="50%" valign="top">

#### 🌐 [kiokuflow](https://github.com/takeshy/kiokuflow)

![Web app](https://img.shields.io/badge/☁️_web_app-4285F4?style=flat-square)

Read, annotate, and ask Gemini about documents in **your own Google Drive** — with no external database and no lock-in.

PDFs, EPUBs, Markdown notes, highlights, memos, dashboards, chat, and workflows all live together in a self-hostable, offline-first web app.

→ [Try it at kiokuflow.net](https://kiokuflow.net)

</td>
</tr>
<tr>
<td colspan="2" valign="top">

#### 🎙️ [speech-popup](https://github.com/takeshy/speech-popup)

![Voice anywhere](https://img.shields.io/badge/🎤_voice_anywhere-2E8B57?style=flat-square)

A resident **voice dictation popup** for Windows, Linux, and macOS. Press a hotkey, speak, edit the transcript, then press Enter to paste it into the app you were using.

Use browser speech recognition or bring your own OpenAI-compatible, whisper.cpp, Microsoft MAI Transcribe, Gemini, or Vertex AI service. The popup supports English and Japanese, voice commands, retryable recordings, and keyboard-first editing.

</td>
</tr>
</table>

---

### 🔌 The Obsidian AI plugin family

The other half of my time goes here. **One idea, three engines** — pick the one that matches how you want your AI to run, then plug the companion plugins into it.

<table>
<tr>
<td width="33%" valign="top">

#### ✨ [Gemini Helper](https://github.com/takeshy/obsidian-gemini-helper)

![](https://img.shields.io/github/stars/takeshy/obsidian-gemini-helper?style=flat-square&label=%E2%98%85&color=E3B341)

Google Gemini, desktop **and** mobile. AI chat, workflow automation, RAG, and an LLM Wiki (OKF).

</td>
<td width="33%" valign="top">

#### 🔀 [LLM Hub](https://github.com/takeshy/obsidian-llm-hub)

![](https://img.shields.io/github/stars/takeshy/obsidian-llm-hub?style=flat-square&label=%E2%98%85&color=E3B341)

Bring your own backend: Gemini, OpenAI, OpenRouter, Grok, Ollama, or a CLI — all behind one UI.

</td>
<td width="33%" valign="top">

#### 🔒 [Local LLM Hub](https://github.com/takeshy/obsidian-local-llm-hub)

![](https://img.shields.io/github/stars/takeshy/obsidian-local-llm-hub?style=flat-square&label=%E2%98%85&color=E3B341)

Fully private, no cloud required. Vault tools, MCP servers, RAG, encryption, and edit history.

</td>
</tr>
</table>

**Companion plugins connect to whichever engine you installed** — they supply no models of their own, they borrow yours:

- 🗣️ **[Discussion Hub](https://github.com/takeshy/obsidian-discussion-hub)** — AI plugins register their models at runtime, so models from *different providers* can argue in the same structured discussion. Assign roles, run turns, let them conclude, then have a separate set of voters pick a winner.
- 📊 **[Dashboard Hub](https://github.com/takeshy/obsidian-dashboard-hub)** — AI is optional, but connect an engine and it can answer questions about selected text or reading memos, generate and edit a Base, rewrite Timeline posts, and build and run Workflows. It shares its Base directory and Timeline name with the connected plugin, so date-based questions read one day's file instead of scanning everything.

---

### 🔌 MCP servers

Small, single-binary servers that give AI agents safe access to real tools and data — the same ones my own apps run on.

<table>
<tr>
<td width="50%" valign="top">

#### 🛡️ [mcp-gatekeeper](https://github.com/takeshy/mcp-gatekeeper)

A security-focused MCP gateway that lets AI assistants **run shell commands under fine-grained policy** — argument validation, env filtering, bubblewrap/WASM sandboxing. Bridge mode exposes any stdio MCP server over HTTP with auth, rate limiting and OAuth 2.0 (PKCE).

</td>
<td width="50%" valign="top">

#### 🗺️ [geo-mcp](https://github.com/takeshy/geo-mcp)

**Place search and reverse geocoding** from self-hosted OpenStreetMap and GeoNames data — no external API calls at runtime. Powers kakeratta's location features in production on a shared 4 GiB VM.

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 📚 [ragujuary](https://github.com/takeshy/ragujuary)

CLI + MCP server for **RAG on Google Gemini** — managed Gemini File Search stores, or local multimodal embeddings (text, images, PDF, audio, video) with incremental indexing and Ollama / LM Studio support.

</td>
<td width="50%" valign="top">

#### 📅 [mcp-gcal](https://github.com/takeshy/mcp-gcal)

A standalone MCP server for **Google Calendar and Gmail** — stdio for a single user, or HTTP with per-user Google OAuth.

</td>
</tr>
</table>

---

### ⌨️ SKK, wherever I type

I also build a family of lightweight **SKK Japanese input tools** around the same familiar key bindings and conversion workflow — no system-wide IME required.

<table>
<tr>
<td width="33%" valign="top">

#### 🌐 [chrome-skk-lite](https://github.com/takeshy/chrome-skk-lite)

SKK directly inside Chrome input fields, plus a clipboard input window for places extensions cannot reach. The same engine is also available as a kiokuflow-desktop plugin.

</td>
<td width="33%" valign="top">

#### 💬 [skk-popup](https://github.com/takeshy/skk-popup)

A cross-platform popup for Linux, Windows, and macOS, including Omarchy. Call it with a hotkey, compose with SKK, then paste the result into any app.

</td>
<td width="33%" valign="top">

#### 🌙 [skk-lite.nvim](https://github.com/takeshy/skk-lite.nvim)

Pure Lua SKK for Neovim insert and command-line modes, with no Node.js or Denops runtime required while typing.

</td>
</tr>
</table>

---

<details>
<summary>🧩 Beyond the pinned repos</summary>

<br>

**Obsidian / knowledge tools** — [obsidian-wysimark](https://github.com/takeshy/obsidian-wysimark) (WYSIWYG Markdown editing that keeps files pure Markdown), [obsidian-work-log](https://github.com/takeshy/obsidian-work-log), [obsidian-gitlog-summary](https://github.com/takeshy/obsidian-gitlog-summary), [obsidian-gdrive-vault](https://github.com/takeshy/obsidian-gdrive-vault), [obsidian-gemihub](https://github.com/takeshy/obsidian-gemihub)

**kiokuflow ecosystem** — [gemihub-gdrive](https://github.com/takeshy/gemihub-gdrive) (Drive sync), [hub-ronginus](https://github.com/takeshy/hub-ronginus) (AI debate arena), [hub-accounting](https://github.com/takeshy/hub-accounting) (Beancount-compatible bookkeeping), [hub-audio-score](https://github.com/takeshy/hub-audio-score) (audio → sheet music), [llm-hub-skills](https://github.com/takeshy/llm-hub-skills)

**Go & infra** — [logmon-go](https://github.com/takeshy/logmon-go), [minipdfsplit](https://github.com/takeshy/minipdfsplit) (stdlib-only PDF page splitter — xref streams, object streams, RC4/AES-encrypted PDFs), [go-touch](https://github.com/takeshy/go-touch), [touch_and_go](https://github.com/takeshy/touch_and_go)

**Editor & web** — [nvim-gemini-helper](https://github.com/takeshy/nvim-gemini-helper) (Gemini + RAG in Neovim), [http-file.nvim](https://github.com/takeshy/http-file.nvim), [wysimark-lite](https://github.com/takeshy/wysimark-lite), [mdwys](https://github.com/takeshy/mdwys), [socket.io-reqev](https://github.com/takeshy/socket.io-reqev), [svg_canvas_chart](https://github.com/takeshy/svg_canvas_chart)

</details>

---

### 🧰 Tech I reach for

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Ruby](https://img.shields.io/badge/Ruby-CC342D?style=flat-square&logo=ruby&logoColor=white)
![Lua](https://img.shields.io/badge/Lua-2C2D72?style=flat-square&logo=lua&logoColor=white)
![Obsidian](https://img.shields.io/badge/Obsidian-7C3AED?style=flat-square&logo=obsidian&logoColor=white)
![Neovim](https://img.shields.io/badge/Neovim-57A143?style=flat-square&logo=neovim&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

### 📊 By the numbers

<p align="center">
  <img alt="Public repos" src="https://img.shields.io/badge/public_repos-65%2B-3178C6?style=for-the-badge&logo=github&logoColor=white">
  <img alt="Followers" src="https://img.shields.io/github/followers/takeshy?style=for-the-badge&logo=github&logoColor=white&label=followers&color=181717">
  <img alt="Stars" src="https://img.shields.io/badge/⭐_stars_earned-240%2B-E3B341?style=for-the-badge">
  <img alt="Since 2009" src="https://img.shields.io/badge/on_github_since-2009-57A143?style=for-the-badge">
</p>

---

<p align="center">
  ✍️ I write about AI tooling and development on <a href="https://zenn.dev/takeshy"><b>Zenn</b></a> — issues and PRs are always welcome on any of my repos.
</p>
