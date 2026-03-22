# 🔗 LinkedTranslate

> **Google Translate. But for LinkedIn.**

**[🌐 Live Demo → linked-translate.vercel.app](https://linked-translate.vercel.app)**

Turn any mundane thing you did into a glazed, over-the-top LinkedIn post — powered by Groq AI.

---

## What it does

You type something embarrassingly normal. LinkedTranslate rewrites it like you just disrupted an entire industry.

| Input | Output vibe |
|---|---|
| "I swam today" | *"This morning, I chose discomfort. Every stroke was a negotiation with resistance..."* |
| "I ate cereal" | *"I leveraged a high-carb asset to fuel my morning execution strategy..."* |
| "I took a nap" | *"I intentionally invested in cognitive recovery — the most underrated growth hack..."* |

---

## Translation Modes

| Mode | What it does |
|---|---|
| 💼 **LinkedIn** | Classic LinkedIn glaze — the original mode |
| 🔄 **Reverse** | Paste a LinkedIn post, get back what actually happened in brutal plain English |
| 🌍 **Arabic** | Glazed Arabic LinkedIn post — formal MSA mixed with English buzzwords, RTL output |
| 😤 **Passive Aggressive** | Sounds gracious and professional. Seething underneath. |
| 💼 **Industry** | LinkedIn glaze with industry-specific dialect (Tech / Finance / Marketing / Healthcare / Academia) |
| 📧 **CEO Email** | Turns bad news into a vague, caring all-hands email that says absolutely nothing |

---

## Features

- ⚡ **3 intensity levels** — Professional → Thought Leader → Full LinkedIn 🚀
- 💡 **Life Lesson** — ends every post with a profound takeaway
- 😂 **Emojis** — sprinkle them liberally
- 📝 **Essay mode** — classic scroll-bait, one sentence per line
- \# **Hashtags** — auto-generated LinkedIn-core hashtags
- 🔐 **API key stored locally** — never leaves your browser
- 📋 **One-click copy** — paste directly to LinkedIn

---

## Setup

**Option 1 — Just use it online:**
👉 [linked-translate.vercel.app](https://linked-translate.vercel.app)

**Option 2 — Run locally (no install, no build step):**

1. Clone this repo
2. Open `index.html` in your browser
3. Get a free API key at [console.groq.com](https://console.groq.com)
4. Click **⚙️ API Key**, paste your key, save
5. Start glazing

---

## Tech

| Layer | Choice |
|---|---|
| Frontend | Vanilla HTML + CSS + JavaScript |
| AI | [Groq API](https://console.groq.com) |
| Model | `llama-3.3-70b-versatile` |
| Key storage | `localStorage` (browser only) |
| Dependencies | None |

---

## Local development

```bash
git clone https://github.com/ahmed-145/LinkedTranslate.git
cd LinkedTranslate
# Just open index.html in your browser — that's it
open index.html
```

---

## License

MIT — do whatever you want with it.

---

*LinkedTranslate — because someone had to.*
