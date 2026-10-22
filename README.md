# Shreya Lanka

Backend and AI engineer. I build Python and TypeScript APIs on PostgreSQL, LangGraph agents, and ML services, with tests and CI on all of them. B.Tech Cyber Security '27, Hyderabad. My security background shapes how I build: audit logs, input validation, and safe defaults.

## Projects

### [AI Complaint Management Copilot](https://github.com/shreyaaaalankaaa/complaint-copilot)
**Python · FastAPI · LangGraph · Groq · PostgreSQL · React**

A 12-node LangGraph agent that turns pharmaceutical complaint emails and PDFs into structured records. It handles triage, field extraction, completeness and duplicate checks, risk classification, and draft root-cause and CAPA recommendations. A rule-engine fallback keeps the full workflow running without an API key. Every write goes to an append-only audit log with field-level AI/human provenance.

### [PhishGuard](https://github.com/shreyaaaalankaaa/phishguard)
**Python · Flask · scikit-learn · Docker · GitHub Actions**

A phishing-risk API that scores URLs on 33 lexical and structural features and returns a probability, a 0–100 risk score, and the top indicators. It never visits submitted URLs or runs DNS, WHOIS, or reputation lookups, so predictions stay reproducible and isolated from malicious hosts. 0.95 ROC-AUC on a 12,500-URL holdout.

### [LocalOS](https://github.com/shreyaaaalankaaa/localos-ai-assistant)
**Electron · React · TypeScript · FastAPI · Ollama**

A local-first desktop assistant that runs models through Ollama and routes requests to 21 tools, with no data leaving the machine. Every tool call is sandboxed with allowlists, 29 blocked path and command patterns, expiring confirmations for risky actions, and an audit log.

### [LeadDesk Mini](https://github.com/shreyaaaalankaaa/leaddesk-mini)
**TypeScript · Express · PostgreSQL · React**

A lead intake site and admin dashboard with search, filters, pagination, and status history. Auth uses JWT in HTTP-only cookies, bcrypt, rate limiting, and Zod validation on client and server. Deployed on Vercel and Render.

## Skills

**Languages:** Python, TypeScript, JavaScript, SQL  
**Backend:** FastAPI, Flask, Node.js, Express, PostgreSQL, SQLAlchemy, REST APIs, JWT auth, Zod  
**AI / ML:** LangGraph, LangChain, Groq, Ollama, scikit-learn, pandas, NumPy  
**Frontend:** React, Tailwind CSS, Electron  
**DevOps & Testing:** Docker, GitHub Actions, pytest, Vitest, Git, Linux, Vercel, Render

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
