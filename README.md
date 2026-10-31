# ⚡ LLM Cost Calculator

**Estimate and compare LLM API costs across OpenAI, Anthropic Claude, and Google Gemini — before you write a single line of code.**

![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Pricing: Oct 2026](https://img.shields.io/badge/Pricing-October%202026-blue.svg)
![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero-orange.svg)

---

## 🎯 What Is This?

A free, open-source, single-file web tool that helps developers **estimate monthly/yearly LLM API costs** before committing to a model or provider.

**No signup. No tracking. No backend. Just math.**

### Features

- 📊 **13+ models compared** — GPT-6 Astra, Claude Opus 5.5, Gemini 4 Argon, and more
- 🎛️ **Interactive sliders** — adjust requests/day, input tokens, output tokens in real time
- ⚡ **Quick presets** — Chatbot, AI Agent, Enterprise SaaS, RAG Pipeline, High-Volume Classification
- 💰 **Auto-sorted by cheapest** — instantly see which model saves you the most
- 💡 **Cost optimization tips** — prompt caching, batching, model routing strategies
- 🌙 **Beautiful dark mode UI** — built with Tailwind CSS
- 📱 **Fully responsive** — works on mobile, tablet, and desktop

---

## 🚀 Quick Start

Zero dependencies. Zero build step. Just open the file:

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/llm-cost-calculator.git

# Open in browser
open index.html
# or on Windows:
start index.html
```

That's it. No `npm install`. No build. No server.

---

## 🖼️ Screenshot

> _Add a screenshot here after deploying_

---

## 📐 How It Works

The calculator uses a simple, transparent formula:

```
Total Input Cost  = (requests_per_day × avg_input_tokens × days) / 1,000,000 × input_price_per_MTok
Total Output Cost = (requests_per_day × avg_output_tokens × days) / 1,000,000 × output_price_per_MTok
Total Cost        = Total Input Cost + Total Output Cost
```

All pricing is sourced from **official API documentation** (OpenAI, Anthropic, Google) as of **October 2026**.

---

## 💲 Pricing Data Sources

| Provider | Source |
|----------|--------|
| OpenAI | [openai.com/api/pricing](https://openai.com/api/pricing) |
| Anthropic | [docs.anthropic.com](https://docs.anthropic.com/en/docs/about-claude/models) |
| Google Gemini | [ai.google.dev/pricing](https://ai.google.dev/pricing) |

> ⚠️ Prices change. Always verify with official docs before making budget decisions.

---

## 🛠️ Tech Stack

- **HTML** — Single file, semantic markup
- **Tailwind CSS** — Via CDN (no build step)
- **Vanilla JavaScript** — Zero frameworks, zero dependencies
- **GitHub Pages** — Free hosting

---

## 📦 Deploy for Free

### GitHub Pages (Recommended)

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to **main branch**, root folder
4. Your site is live at `https://YOUR_USERNAME.github.io/llm-cost-calculator/`

### Vercel / Netlify

Just connect the repo — both auto-detect static HTML. Zero config needed.

---

## 🤝 Contributing

PRs welcome! Some ideas:

- [ ] Add more models (Mistral, Llama, Cohere, etc.)
- [ ] Add prompt caching cost comparison toggle
- [ ] Add batch pricing comparison toggle
- [ ] Export results as CSV / PDF
- [ ] Add cost-over-time chart visualization
- [ ] Add currency conversion (USD → EUR, INR, etc.)

---

## 📄 License

MIT — do whatever you want with it.

---

## ⭐ Star This Repo

If this saved you time, drop a ⭐ — it helps other developers find it.
