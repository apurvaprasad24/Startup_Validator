# VALIDATE·AI — Startup Idea Validator

> Built as a portfolio project for the **Google Startup School: Prompt to Prototype** certificate (Scalar, 2025)

A clean, editorial-style web app that analyses your startup idea using Gemini AI and returns a structured analyst report in seconds.

---

## What it does

Paste a startup idea → get an instant report with:

- **Viability, Market & Execution scores** (1–10)
- **Target audience** segments
- **Top competitors** with descriptions
- **Key risks** to watch out for
- **Go-to-market strategy** steps
- **Unique angle & defensibility** analysis
- **Analyst verdict** — honest, direct feedback

---

## Tech Stack

| Layer | Tech |
|---|---|
| Frontend | Vanilla HTML + CSS + JavaScript |
| AI | Gemini 2.0 Flash (Google AI Studio) |
| Fonts | Space Grotesk + Space Mono (Google Fonts) |
| Hosting | Vercel / Netlify (zero config) |

Zero dependencies. No npm. No build step. Just open `index.html`.

---

## Getting Started

### 1. Get a free Gemini API key
1. Go to [aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)
2. Sign in with your Google account
3. Click **"Get API Key"** → **"Create API key"**
4. Copy the key

Free tier: **1,500 requests/day** — no credit card required.

### 2. Run locally
```bash
# Just open in browser — no server needed
open index.html
```
Or drag `index.html` into any browser window.

### 3. Deploy to Vercel (free, 1 minute)
1. Push this folder to a GitHub repo
2. Go to [vercel.com](https://vercel.com) → **Add New Project**
3. Import your GitHub repo → click **Deploy**
4. Get a live URL like `validate-ai.vercel.app`

---

## Project Structure

```
startup-validator/
├── index.html    ← Full app (HTML + CSS + JS, single file)
└── README.md     ← This file
```

---

## About

This project demonstrates all four modules from the Google Startup School certificate:

| Module | Demonstrated by |
|---|---|
| Idea & Validation | TAM/SAM/SOM scoring, problem-fit analysis output |
| Mastering AI Studio | Gemini API integration, prompt engineering |
| MVP Development | Working deployed web app |
| Showcase | Live URL, GitHub portfolio, CV-ready project |
