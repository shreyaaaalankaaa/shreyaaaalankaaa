# Shreya Lanka

Cyber Security undergraduate (B.Tech '27, Hyderabad) who builds software across AI, machine learning, security and full-stack web. I like shipping complete, working projects, with tests, CI and live demos, and my security background shapes how I build: input validation, audit logs and safe defaults.

## Featured projects

### [AI Complaint Management Copilot](https://github.com/shreyaaaalankaaa/complaint-copilot) · [Live demo](https://complaint-copilot-app.vercel.app)
**Python · FastAPI · LangGraph · Groq · PostgreSQL · React**

A 12-node LangGraph agent that turns pharmaceutical complaint emails and PDFs into structured records. It handles triage, field extraction, completeness and duplicate checks, risk classification, and draft root-cause and CAPA recommendations. A rule-engine fallback keeps the full workflow running without an API key. Every write goes to an append-only audit log with field-level AI/human provenance.

### [PhishGuard](https://github.com/shreyaaaalankaaa/PhishGuard) · [Live demo](https://phishguard-fjyt.onrender.com)
**Python · Flask · scikit-learn · Docker · GitHub Actions**

A phishing-risk API that scores URLs on 35 lexical and structural features and returns a probability, a 0–100 risk score, and the top indicators. It never visits submitted URLs or runs DNS, WHOIS, or reputation lookups, so predictions stay reproducible and isolated from malicious hosts. 0.95 ROC-AUC on an 18,750-URL holdout, and it flags look-alike domains such as `paypa1` and `g00gle`.

### [LocalOS (JARVIS)](https://github.com/shreyaaaalankaaa/localos-ai-assistant)
**Electron · React · TypeScript · FastAPI · Ollama**

A local-first desktop assistant that runs models through Ollama and routes requests to 21 tools, with no data leaving the machine. Every tool call is sandboxed with allowlists, 29 blocked path and command patterns, expiring confirmations for risky actions, and an audit log. The local API requires a per-install session token, so other websites open in the browser cannot call it.

### [LeadDesk Mini](https://github.com/shreyaaaalankaaa/leaddesk-mini) · [Live demo](https://leaddesk-mini-client-amber.vercel.app)
**TypeScript · Express · PostgreSQL · React**

A lead intake site and admin dashboard with search, filters, pagination, and status history. Auth uses JWT in HTTP-only cookies, bcrypt, rate limiting, and Zod validation on client and server. Deployed on Vercel and Render.

## More projects

- **[Network Threat Detection](https://github.com/shreyaaaalankaaa/CyberSecurity-threat-detection)** · [Live demo](https://cybersecurity-threat-detection-8ytmyidxcahn39akygpdvq.streamlit.app) — Intrusion detection with scikit-learn: model comparison, FastAPI inference and a Streamlit dashboard.
- **[Forecasting Dashboard](https://github.com/shreyaaaalankaaa/forecasting-dashboard)** · [Live demo](https://forecasting-dashboard-2g5f4lseacs8kxnosypemh.streamlit.app) — Compares regression and tree-based forecasters against a naive baseline on a chronological split.
- **[Automated Video Dubbing](https://github.com/shreyaaaalankaaa/automated-video-dubbing-system)** — Dubs YouTube videos into English with faster-whisper, edge-tts and FFmpeg, with resumable runs and quality reports.
- **[ShopHub](https://github.com/shreyaaaalankaaa/Product-site)** · [Live demo](https://shreyaaaalankaaa.github.io/Product-site/) — Vanilla JavaScript storefront with search, cart, wishlist and offline PWA support.

## Skills

**Languages:** Python, TypeScript, JavaScript, SQL  
**Backend:** FastAPI, Flask, Node.js, Express, PostgreSQL, SQLAlchemy, REST APIs, JWT auth, Zod  
**AI / ML:** LangGraph, LangChain, Groq, Ollama, scikit-learn, pandas, NumPy  
**Frontend:** React, Tailwind CSS, Electron  
**DevOps & Testing:** Docker, GitHub Actions, pytest, Vitest, Git, Linux, Vercel, Render, Streamlit

## Contact

[shreyalankaaa@gmail.com](mailto:shreyalankaaa@gmail.com) · [LinkedIn](https://www.linkedin.com/in/shreya-lanka-057a0b28a)

<!--
**shreyaaaalankaaa/shreyaaaalankaaa** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
