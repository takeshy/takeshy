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

### 🌟 What I'm building right now

<table>
<tr>
<td width="50%" valign="top">

#### 🖥️ [gemihub-desktop](https://github.com/takeshy/gemihub-desktop)

![Main focus](https://img.shields.io/badge/⚡_main_focus-8E75B2?style=flat-square)

A **local-first desktop workspace** that turns your notes, documents, and workflows into context for AI.

Everything I've learned from the Obsidian plugins, rebuilt as a standalone app — your files stay yours, the AI comes to them. This is where most of my energy goes from here on.

→ Extended by [gemihub-gdrive](https://github.com/takeshy/gemihub-gdrive), [hub-ronginus](https://github.com/takeshy/hub-ronginus), [hub-accounting](https://github.com/takeshy/hub-accounting), [hub-audio-score](https://github.com/takeshy/hub-audio-score)

</td>
<td width="50%" valign="top">

#### 🌐 [GemiHub](https://github.com/takeshy/gemihub)

![Web app](https://img.shields.io/badge/☁️_web_app-4285F4?style=flat-square)

Read, annotate, and ask Gemini about documents in **your own Google Drive** — with no external database and no lock-in.

PDFs, EPUBs, Markdown notes, highlights, memos, dashboards, chat, and workflows all live together in a self-hostable, offline-first web app.

→ [Try it at gemihub.net](https://gemihub.net)

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

### ⌨️ SKK, wherever I type

I also build a family of lightweight **SKK Japanese input tools** around the same familiar key bindings and conversion workflow — no system-wide IME required.

<table>
<tr>
<td width="33%" valign="top">

#### 🌐 [chrome-skk-lite](https://github.com/takeshy/chrome-skk-lite)

SKK directly inside Chrome input fields, plus a clipboard input window for places extensions cannot reach. The same engine is also available as a GemiHub Desktop plugin.

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

**GemiHub ecosystem** — [gemihub-gdrive](https://github.com/takeshy/gemihub-gdrive) (Drive sync), [hub-ronginus](https://github.com/takeshy/hub-ronginus) (AI debate arena), [hub-accounting](https://github.com/takeshy/hub-accounting) (Beancount-compatible bookkeeping), [hub-audio-score](https://github.com/takeshy/hub-audio-score) (audio → sheet music), [llm-hub-skills](https://github.com/takeshy/llm-hub-skills)

**Go & infra** — [mcp-gatekeeper](https://github.com/takeshy/mcp-gatekeeper) (sandboxed MCP server with policy control), [ragujuary](https://github.com/takeshy/ragujuary) (RAG on Gemini File Search), [logmon-go](https://github.com/takeshy/logmon-go), [minipdfsplit](https://github.com/takeshy/minipdfsplit) (stdlib-only PDF page splitter — xref streams, object streams, RC4/AES-encrypted PDFs), [mcp-gcal](https://github.com/takeshy/mcp-gcal), [go-touch](https://github.com/takeshy/go-touch), [touch_and_go](https://github.com/takeshy/touch_and_go)

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
