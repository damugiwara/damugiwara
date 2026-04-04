## $ Whoami

I'm **Vansh**, an AI Automation Engineer focused on designing and deploying intelligent systems that automate workflows, integrate APIs, and power scalable AI-driven applications.

I specialize in transforming manual, repetitive processes into autonomous, self-improving systems using LLMs, agentic architectures, workflow orchestration, and modern backend infrastructure.

---

## $ Tech Stack

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Render](https://img.shields.io/badge/Render-430098?style=for-the-badge&logo=render&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge)
![ngrok](https://img.shields.io/badge/ngrok-1F1E37?style=for-the-badge&logo=ngrok&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![Airtable](https://img.shields.io/badge/Airtable-18BFFF?style=for-the-badge&logo=airtable&logoColor=white)

---

## $ Projects

### ⚙️ Zero Touch Procurement

An end-to-end autonomous procurement pipeline that eliminates spreadsheets, follow-up emails, and manual award processes simultaneously.

**Pipeline:** One trigger fires the entire RFQ lifecycle → suppliers get personalised invitations via Tally URLs → quotes collected and scanned for anomalies by Groq → non-responders auto-chased → buyer clicks Award → PO generated and logged to Airtable automatically.

**Stack:** `n8n` · `Airtable` · `Groq` · `Gmail` · `Tally` · `PDF Generation`

---

### 🎯 Signal Based LinkedIn Lead Generation Tool

An end-to-end automated prospecting system that identifies high intent B2B leads by targeting people already engaging with relevant LinkedIn content. No cold outreach needed.

**Pipeline:** Paste a viral LinkedIn post URL → Apify scrapes all commenters → ICP scoring buckets leads into Tier 1/2/3 → results batch inserted into Supabase → async cron polling handles Apify jobs without serverless timeouts.

**Stack:** `Next.js 16` · `React 19` · `Supabase` · `Apify` · `TypeScript` · Vercel

---

### 🚀 RogueX — AI Powered Crypto Analysis System
🌐 https://roguex.vercel.app

An autonomous multi-model crypto intelligence system that parses incoming market queries, routes them by intent, and returns real-time price data, technical analysis, or trading signals without manual intervention.

**Pipeline:** Webhook receives query → intent and coin parsed → symbol normalized → live price and stats fetched via API → context restored → router branches by command type → analysis queue runs Gemini and Groq in parallel → formatted report or signal returned automatically.

**Stack:** `n8n` · `Gemini` · `Groq` · `Webhook` · `Vercel`

---

### 🤖 LinkedIn AI Email Drafter
🌐 https://github.com/damugiwara/Linkedin_Email_Drafter
 
An automated job application system that scrapes a LinkedIn job post, generates a personalized email using your resume and skills, and saves it as a Gmail draft with your resume attached.
 
**Pipeline:** User submits LinkedIn URL and resume → n8n webhook triggers → Jina AI scrapes job post → Groq parses resume text → AI Agent (Groq + Gemini fallback) drafts targeted email → application logged to Airtable → Gmail draft created with resume attached.
 
**Stack:** `n8n` · `Groq` · `Gemini` · `Jina AI` · `Airtable` · `Gmail OAuth2` · `PDF.js`
 
---

## $ Let's Connect

🌐 Portfolio: https://www.vanshtripathi.tech
💼 LinkedIn: https://www.linkedin.com/in/vanshtri07/
📫 Open to collaborations on AI automation, agent systems, and intelligent workflow platforms
