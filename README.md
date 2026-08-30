<p align="center">
  <a href="https://github.com/ishandutta2007/claudebot">
    <img src="assets/banner.svg" alt="ClaudeBot Dynamic Banner" width="100%">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/ClaudeBot-AI%20Desktop%20Assistant-8B5CF6?style=for-the-badge&logo=anthropic&logoColor=white&labelColor=1E1B4B" alt="ClaudeBot - Claude AI Desktop Assistant">
  <br><br>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white" alt="Electron">
  <img src="https://img.shields.io/badge/Windows%20%7C%20macOS%20%7C%20Linux-Active-brightgreen?style=flat-square" alt="Platforms">
  <img src="https://img.shields.io/github/stars/ishandutta2007/claudebot?style=social" alt="GitHub stars">
  <img src="https://img.shields.io/github/license/ishandutta2007/claudebot?style=flat-square" alt="License">
</p>

<h1 align="center">ClaudeBot 🖥️🤖</h1>

<h3 align="center">
  The elegant, privacy-first desktop AI assistant powered by <b>Claude</b> (Anthropic)<br>
  Fast • Clean • Local-first • Works offline with local models too
</h3>

<p align="center">
  <a href="#-features">Features</a> •
  <a href="#-demo">Demo</a> •
  <a href="#-installation">Install</a> •
  <a href="#-configuration">Config</a> •
  <a href="#-roadmap">Roadmap</a> •
  <a href="#-contributing">Contribute</a>
</p>

<br>

![ClaudeBot Hero Screenshot](https://via.placeholder.com/1280x720/1E1B4B/FFFFFF?text=ClaudeBot+Modern+UI+with+Sidebar+and+Chat+%E2%80%94+Dark+Mode)  
<i><sub>Modern chat interface • Sidebar conversations • Markdown rendering • Dark & Light themes</sub></i>

<br>

## ✨ Why ClaudeBot?

ClaudeBot brings the power of **Claude 3.5 / Claude 4** (or local models) directly to your desktop — no browser tabs, no distractions, instant access.

Perfect for:

- Developers writing code with AI
- Writers & researchers doing deep thinking
- Power users who want fast, reliable AI without subscriptions in browser
- People who care about **privacy** and want local-first option

## 🔥 Key Features

<table>
  <tr>
    <th>Feature</th>
    <th>Description</th>
    <th>Status</th>
  </tr>
  <tr>
    <td>Claude API integration</td>
    <td>Official Anthropic API (Claude 3.5 Sonnet, Opus, Haiku…)</td>
    <td>✓</td>
  </tr>
  <tr>
    <td>Local LLM support</td>
    <td>Ollama, LM Studio, llama.cpp, GGUF models</td>
    <td>✓</td>
  </tr>
  <tr>
    <td>System prompt & custom personas</td>
    <td>Developer, Writer, Therapist, Tutor, Code Reviewer…</td>
    <td>✓</td>
  </tr>
  <tr>
    <td>Global hotkey summon</td>
    <td>Ctrl+Space / Cmd+Space → instant AI anywhere</td>
    <td>Coming soon</td>
  </tr>
  <tr>
    <td>Markdown + Syntax highlighting</td>
    <td>Beautiful code blocks, tables, LaTeX</td>
    <td>✓</td>
  </tr>
  <tr>
    <td>Conversation folders & search</td>
    <td>Organize chats like Notion / Obsidian</td>
    <td>✓</td>
  </tr>
  <tr>
    <td>Light / Dark / System theme</td>
    <td>Auto-follows OS appearance</td>
    <td>✓</td>
  </tr>
  <tr>
    <td>Cross-platform</td>
    <td>Windows • macOS • Linux</td>
    <td>✓</td>
  </tr>
  <tr>
    <td>Completely offline mode</td>
    <td>With local models — zero data leaves your machine</td>
    <td>✓</td>
  </tr>
  <tr>
    <td>Export / Import conversations</td>
    <td>JSON / Markdown</td>
    <td>✓</td>
  </tr>
</table>

## 🚀 Quick Start (Installation)

### Option 1: Pre-built binaries (recommended)

→ https://github.com/ishandutta2007/claudebot/releases/latest

- Windows → `.exe`
- macOS → `.dmg`
- Linux → `.AppImage` / `.deb`

### Option 2: Run from source

```bash
# 1. Clone
git clone https://github.com/ishandutta2007/claudebot.git
cd claudebot

# 2. Install dependencies
npm install

# 3. Start development mode
npm run dev

# 4. Or build yourself
npm run build
```

## ⚙️ Configuration (in 30 seconds)

1. Get your **Anthropic API key** → https://console.anthropic.com
2. Create or edit `~/.claudebot/config.json`

```json
{
  "theme": "system",
  "defaultModel": "claude-3-5-sonnet-20241022",
  "anthropicApiKey": "sk-ant-XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX",
  "ollama": {
    "enabled": true,
    "baseUrl": "http://localhost:11434"
  },
  "hotkey": "CommandOrControl+Space",
  "personas": [
    {
      "name": "Senior Python Dev",
      "prompt": "You are a senior Python engineer with 15 years experience..."
    }
  ]
}
```

## 🖼️ Screenshots

<p align="center">
  <img src="https://via.placeholder.com/800x450/111827/FFFFFF?text=Chat+Interface+%7C+Code+Highlighting" width="48%" alt="Chat view with code">
  <img src="https://via.placeholder.com/800x450/111827/FFFFFF?text=Settings+%7C+Model+Selector" width="48%" alt="Settings panel">
</p>
<p align="center">
  <img src="https://via.placeholder.com/800x450/111827/FFFFFF?text=Conversation+Library+%7C+Folders" width="48%" alt="Conversation manager">
  <img src="https://via.placeholder.com/800x450/111827/FFFFFF?text=Global+Hotkey+Summon" width="48%" alt="Summon anywhere">
</p>

## 📈 Roadmap 2025–2026

- [ ] Global hotkey & floating mini-window
- [ ] Drag & drop files / screenshots → Claude Vision
- [ ] RAG on local documents & folders
- [ ] Custom tools & function calling
- [ ] VS Code / Neovim / IntelliJ integration
- [ ] Multi-model tabs (Claude + Gemini + local side-by-side)

## ❤️ Contributing

Pull requests are welcome!

1. Fork & clone
2. Create feature branch (`git checkout -b feat/amazing-feature`)
3. Commit (`git commit -m 'Add amazing feature'`)
4. Push & open PR

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## 📄 License

MIT © 2026 Ishan Dutta

Made with ❤️ and Claude

<p align="center">
  <a href="https://github.com/ishandutta2007/claudebot/stargazers">
    <img src="https://img.shields.io/github/stars/ishandutta2007/claudebot?style=social&label=Star&maxAge=2592000" alt="Star this repo">
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/ishandutta2007/claudebot/fork">
    <img src="https://img.shields.io/github/forks/ishandutta2007/claudebot?style=social&label=Fork" alt="Fork">
  </a>
</p>

<br>

**Keywords:** Claude AI desktop app, Claude desktop assistant, Anthropic Claude client, local LLM desktop, AI assistant for PC, Claude chatbot offline, best Claude wrapper desktop, privacy focused AI assistant
