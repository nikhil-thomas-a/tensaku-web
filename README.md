# Tensaku 添削

> Free AI writing toolkit — 13 tools for anyone who writes in English.

**🌐 Live:** [nikhil-thomas-a.github.io/tensaku-web](https://nikhil-thomas-a.github.io/tensaku-web/)

No account needed. Nothing stored server-side. Powered by Groq's free tier.

---

## Tools

| Tool | What it does |
|------|-------------|
| **Grammar Check** | Finds grammar, spelling, and style issues — rule-based via LanguageTool, no AI hallucination |
| **Enhance** | Improves structure, clarity, and flow |
| **Paraphrase** | Rewrites in fresh words while keeping your meaning |
| **Elaborate** | Expands short notes into full professional prose |
| **Summarise** | Condenses text to the essential points |
| **Bulletify** | Converts prose into clean bullet points |
| **AI Humanise** | Makes AI-generated text sound natural and human |
| **Translate** | Translates into another language |
| **Slackify** | Rewrites for Slack — casual, scannable, with emoji |
| **Teamsify** | Rewrites for Teams — professional with emoji |
| **Formalise** | Elevates writing to formal business register |
| **Simplify** | Rewrites in plain, simple English |
| **Citation** | Generates a formatted academic citation |

Most tools include a **tone selector** (Confident, Friendly, Concise, Academic) and a **creativity slider** to dial in how much the output deviates from your input.

---

## How it works

- **Grammar Check** uses the [LanguageTool public API](https://languagetool.org/) — deterministic, no LLM needed
- All other tools call the [Groq API](https://console.groq.com) with fast open-source models (Llama 3, Mixtral)
- Zero build step — a single `index.html` file, no framework, no bundler

---

## Running locally

```bash
git clone https://github.com/nikhil-thomas-a/tensaku-web.git
cd tensaku-web
```

Open `index.html` in your browser. Grammar Check works without a key. For AI tools, paste your Groq API key into the settings panel — it stays in `localStorage` and never leaves your browser.

Get a free Groq key at [console.groq.com](https://console.groq.com) — no credit card required.

---

## Tech

Single-file HTML/CSS/JS app. No framework, no build step, no backend. Deployed to GitHub Pages.

---

## Connect

Built by **Nikhil Thomas A** — Delivery PM & Fractional Head of Data

🔗 [Portfolio](https://nikhil-thomas-a.github.io/portfolio/) · [LinkedIn](https://www.linkedin.com/in/nikhil-thomas-a-58538117a/) · [GitHub](https://github.com/nikhil-thomas-a)
