# Cliento · Sales Advisor

> The AI Sales Advisor for B2B Account Executives — built on 30+ years of real-world deal experience.

**Live:** [cliento-sales-advisor.vercel.app](https://cliento-sales-advisor.vercel.app)

---

## What It Does

Cliento Sales Advisor is Andy — an AI sales advisor that helps B2B account executives navigate complex deals in real time. Ask about a stuck deal, a prospect who went quiet, price objections, or how to reach the decision maker.

**Core features:**
- Sales Advisor — conversational AI for any deal situation
- Role Play — practice objection handling and discovery calls
- Deal Coaching — structured frameworks for stuck deals
- Script Builder — generate outreach and follow-up scripts
- Deal Pipeline — track deals by stage with probability scoring
- SPIN Discovery, Price Objection, Stuck Deal Rescue, Call Prep, Stakeholder Map, KYC Checklist

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Single-page HTML/CSS/JS |
| AI Model | DeepSeek (`deepseek-chat`) |
| API Proxy | Vercel Serverless Function |
| Hosting | Vercel |

---

## Project Structure

```
Cliento-sales-advisor/
├── public/
│   └── index.html        # Full frontend (single-file app)
├── api/
│   └── chat.js           # Vercel serverless function (DeepSeek proxy)
├── vercel.json           # Vercel deployment config
├── package.json
└── README.md
```

---

## Deploy Your Own

### 1. Clone the repo
```bash
git clone https://github.com/andybai2000/Cliento-sales-advisor.git
cd Cliento-sales-advisor
```

### 2. Get a DeepSeek API key
Sign up at [platform.deepseek.com](https://platform.deepseek.com) and create an API key.

### 3. Deploy to Vercel
```bash
npm i -g vercel
vercel --prod
```

When prompted, add the environment variable:
```
DEEPSEEK_KEY = sk-your-deepseek-key-here
```

Or set it in Vercel Dashboard → Settings → Environment Variables.

### 4. Done
Your advisor is live at your Vercel URL.

---

## Environment Variables

| Variable | Description |
|----------|-------------|
| `DEEPSEEK_KEY` | Your DeepSeek API key (`sk-...`) |

---

## Created By

**Andy Bai** — B2B sales veteran with 30+ years of experience closing complex deals across industrial automation, precision manufacturing, robotics, enterprise software, and professional services.

---

*Cliento · Sales Advisor — Close more. Faster.*
