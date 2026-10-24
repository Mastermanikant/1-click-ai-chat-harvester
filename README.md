# ⚡ 1-Click AI Chat Harvester

> **The Zero-Bloat Research Suite:** Turn AI conversations into clean, Notion-ready Markdown, Obsidian notes with YAML frontmatter, and formatted archives in 1 click.

[![Version](https://img.shields.io/badge/Version-v1.6.1-blue.svg?style=flat-square)](https://github.com/Mastermanikant/1-click-ai-chat-harvester/releases)
[![Chrome Web Store](https://img.shields.io/badge/Chrome_Web_Store-Approved_%26_Live-green.svg?style=flat-square)](https://chromewebstore.google.com/detail/1-click-ai-chat-harvester/ijlcbkgpgnejogbclkjkpmpojbgnndde)
[![Firefox AMO](https://img.shields.io/badge/Firefox_AMO-Approved_%26_Live-green.svg?style=flat-square)](https://addons.mozilla.org/en-US/firefox/addon/1-click-ai-chat-harvester/)
[![Edge Add-ons](https://img.shields.io/badge/Edge_Add--ons-Live-blue.svg?style=flat-square)](https://microsoftedge.microsoft.com/addons/detail/1click-ai-chat-harveste/innbdpajdhcmdklaklhgfcpjkakmkihe)
[![Privacy](https://img.shields.io/badge/Privacy-100%25_Client--Side-brightgreen.svg?style=flat-square)](#-zero-telemetry-privacy-guarantee)
[![GitHub Pages](https://img.shields.io/badge/Live_Showcase-GitHub_Pages-purple.svg?style=flat-square)](https://mastermanikant.github.io/1-click-ai-chat-harvester/)

---

## 🎯 What is 1-Click AI Chat Harvester?

Modern researchers, developers, students, and creators spend hours having deep, structured dialogues with frontier AI models (ChatGPT, Claude, Gemini, DeepSeek). But saving or organizing those threads is broken:
- Copy-pasting creates messy indentation, broken tables, and missing code fences.
- Cloud export tools inject unwanted promo watermarks ("Exported via XYZ"), require expensive recurring SaaS subscriptions, or secretly route your private chat data through their servers.
- Heavy browser extensions drain your laptop battery and consume 80MB+ of background RAM even when you are not using them.

**1-Click AI Chat Harvester** solves this permanently. It is a lightweight, zero-bloat browser extension that lives in your browser, runs **100% on-demand**, and gives you mathematically clean Markdown ready for **Notion, Obsidian, GitHub, and local vaults**.

---

## 🚀 Live Stores & Download Links

| Browser / Store | Status | Link |
| :--- | :--- | :--- |
| **Google Chrome (Web Store)** | 🟢 **Approved & Live (v1.6.1)** | [Install from Chrome Web Store](https://chromewebstore.google.com/detail/1-click-ai-chat-harvester/ijlcbkgpgnejogbclkjkpmpojbgnndde) |
| **Mozilla Firefox (AMO)** | 🟢 **Approved & Live (v1.6.1)** | [Install from Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/1-click-ai-chat-harvester/) |
| **Microsoft Edge (Add-ons)** | 🟢 **Live** | [Install from Microsoft Edge Add-ons](https://microsoftedge.microsoft.com/addons/detail/1click-ai-chat-harveste/innbdpajdhcmdklaklhgfcpjkakmkihe) |
| **Direct Pro License** | ⚡ **FrankBase Store** | [store.frankbase.com](https://store.frankbase.com) |

---

## ✨ Core Superpowers

### 1. 42px Floating Turn Picker (`Alt + T`)
Do not export an entire 50-turn thread when you only need one brilliant response. Press `Alt + T` to summon the sleek 42px floating turn picker:
- Select a single turn (e.g., Turn 4)
- Select a contiguous range (e.g., Turns 2 to 6)
- Export all assistant turns or the entire dialogue in 1 click.

### 2. 100% Notion-Ready Markdown
Notion requires strict adherence to block boundaries. Our markdown compiler has been verified with a dedicated automated test suite across all 7 core block types:
- **Headings (H1-H4):** Guaranteed empty-line boundaries before and after.
- **Syntax-Highlighted Code:** Triple-backtick fences with clean language identifiers (`python`, `typescript`, `sql`, `json`).
- **Data Tables:** Well-formed GFM tables with separator rows (`|---|---|`).
- **LaTeX Math Equations:** Block display math (`$$ ... $$`) and inline math (`$ ... $`) rendered with KaTeX/Notion compatibility.
- **Nested Lists & Quotes:** Clean indentation without collapsed hierarchy.

### 3. Obsidian Ready YAML Frontmatter
Automatically prepend structured YAML metadata to every exported file:
```yaml
---
title: "DeepSeek R1 Architecture Breakdown"
platform: "DeepSeek"
harvested_on: "2026-10-23T23:05:00+05:30"
source: "https://chat.deepseek.com/..."
tags: [ai-research, export]
---
```

### 4. Zero-Bloat Performance (0KB Idle RAM Overhead)
Unlike heavy extensions that keep persistent background scripts running 24/7, 1-Click AI Chat Harvester uses modern **Manifest V3 Event-Driven Service Workers**. When you are not actively harvesting a chat, its idle RAM usage is **strictly 0KB**.

### 5. Multi-Engine Universal Compatibility
Seamlessly extracts conversations from all major frontier AI interfaces:
- **OpenAI:** ChatGPT (GPT-4o, o1, o3-mini)
- **Anthropic:** Claude (Claude 3.5 Sonnet, Claude 3 Opus, Haiku)
- **Google:** Gemini Pro, Gemini Flash, Gemini Advanced
- **DeepSeek:** DeepSeek V3, DeepSeek R1 Reasoning
- **Perplexity:** Perplexity AI (including citation links and sources)
- **Microsoft:** Copilot / Bing Chat
- **xAI:** Grok (x.com/i/grok)
- **Universal Articles:** CleanView reader mode for non-AI web articles.

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action | Scope |
| :--- | :--- | :--- |
| `Alt + T` | Open / Toggle Floating Turn Picker | AI Chat Tabs |
| `Alt + C` | Instant Copy Clean Markdown to Clipboard | Anywhere |
| `Alt + D` | 1-Click Download `.md` File | Anywhere |
| `Esc` | Close Turn Picker / License Panel | Anywhere |

*(All keyboard shortcuts can be customized via `chrome://extensions/shortcuts` or `about:addons`)*

---

## 🔒 Zero-Telemetry Privacy Guarantee

Your thoughts, research prompts, and confidential client data belong exclusively to you.

- **Zero Cloud Servers:** We operate zero chat collection servers.
- **100% Client-Side:** Every parsing, conversion, and packaging step happens in your browser's local memory.
- **Zero Watermarks:** We never inject ads, affiliate tracking links, or spam disclaimers into your research files.
- **Stateless Operation:** Disconnect your internet connection, and the markdown converter will continue to function flawlessly.

---

## 💎 Pricing & Commercial Licensing

1-Click AI Chat Harvester includes a **30-Day Free Trial** with full access to all features. 

For continuous research productivity, permanent lifetime licenses are available through the official [FrankBase Store](https://store.frankbase.com):

- **Solo Lifetime License ($5 / ₹499):** Permanent lifetime access for 1 physical machine (unlimited browser profiles).
- **Researcher 3-PC Pack ($10 / ₹999):** For your desktop, laptop, and office workstation with priority VIP support.

All transactions are securely handled via **Dodo Payments** with instant hardware-locked key delivery.

---

## 🤝 Community, Issues & Feedback

We welcome bug reports, feature suggestions, and community discussions:

- 🐛 **Found a bug?** Check if a recent AI UI update broke a selector by opening an [Issue](https://github.com/Mastermanikant/1-click-ai-chat-harvester/issues).
- 💡 **Have a feature idea?** Join our [GitHub Discussions](https://github.com/Mastermanikant/1-click-ai-chat-harvester/discussions).
- 📧 **Enterprise & Custom Integrations:** Contact founder directly at `connect@mastermanikant.com`.

---

## 🏛️ Architect & Ecosystem

- **Systems Architect & Founder:** **Master Manikant Yadav**
- **Personal Portfolio:** [mastermanikant.com](https://mastermanikant.com)
- **Ecosystem Digital Store:** [store.frankbase.com](https://store.frankbase.com)
- **Cryptographic Security Hub:** [frankpass.com](https://frankpass.com)

---

## 📜 Legal Safe Harbor & Non-Affiliation

1-Click AI Chat Harvester is an independent productivity extension created by Master Manikant Yadav. It is not affiliated with, sponsored by, or endorsed by OpenAI, Google, Anthropic, DeepSeek, Microsoft, Perplexity, or xAI. All product names, logos, and brands are property of their respective owners.
