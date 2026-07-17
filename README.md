<div align="center">

# Ananya Srivastava

### AI & ML Engineer in the making — Multi-Agent Systems · Edge AI · Applied Security

**B.Tech CSE (AI & ML) · Chandigarh University · 2025–2029**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ananyasrivastavaa8)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ananyaSrivastavaa9)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/u/ananyasrivastavaa/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ananyasrivastavaa9@gmail.com)

</div>

---

## About Me

I build production-style AI systems — retrieval pipelines, multi-agent orchestration, and edge AI safety tools that stay grounded and fault-tolerant under real constraints. Right now I'm shipping **ASTOR**, a retrieval-first coding agent, and sharpening DSA fundamentals in C++.

<div align="center">

🎓 B.Tech CSE (AI & ML), Chandigarh University *(2025–2029)* &nbsp;·&nbsp; 📍 Uttar Pradesh, India &nbsp;·&nbsp; 🎯 Open to SWE & AI/ML Internships

</div>

---

## Achievements

- 🏆 **CodeStrike 2026** — Ranked **#57 globally** with a perfect **100/100** score, competitive programming championship hosted on Unstop by the Bytebattle Global Community
- 🥇 **Microsoft Agents League 2026** — Completed: built and shipped a production-style 5-agent reasoning pipeline (Reasoning Agents Track)
- 🥈 **AI & ML Club Weekly Coding Challenge (Week 1)** — 2nd Runner-Up out of all participants, inaugural edition by Chandigarh University AI/ML Club × byteXL *(Jul 2026)*
- 🤝 **HackWithUP 2025** — Event coordinator & participant, 30-hour Agentic AI Hackathon

---

## Tech Stack

<div align="center">

#### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)

#### AI, ML & Cloud

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![OpenAI](https://img.shields.io/badge/GPT--4o-412991?style=for-the-badge&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-FF7C00?style=for-the-badge&logo=gradio&logoColor=white)

#### Tools & Infra

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B6B?style=for-the-badge&logo=databricks&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

</div>

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🧠 [ASTOR — Retrieval-First AI Codebase Agent](https://github.com/ananyaSrivastavaa9/ASTOR-AI-Codebase-Agent)
**[Live Demo ↗](https://ananyasrivastavaa9-astor-ai-codebase-agent.hf.space/)**

A ReAct-style coding agent that answers questions about a codebase with exact file/line citations instead of hallucinated guesses.

- Built a **hybrid retrieval pipeline** (ChromaDB semantic search + BM25 keyword search, merged and deduped), hitting **95% retrieval accuracy** on a 20-question benchmark against the Flask codebase
- Used **Tree-sitter** to chunk code at function/class boundaries instead of naive line-splitting — the single biggest driver of retrieval quality in testing
- Designed a **search → read → verify → answer** agent loop with Gemini tool-calling
- Added reliability controls: 8-step limits, retry logic, per-tool timeouts, and a benchmark suite scoring retrieval and generation separately

`Python` `Gemini API` `ChromaDB` `Tree-sitter` `Gradio`

</td>
<td width="50%" valign="top">

### 🤖 [Enterprise Learning Agents](https://github.com/ananyaSrivastavaa9/enterprise-learning-agents)
**Microsoft Agents League 2026 · Reasoning Agents Track**

A grounded multi-agent system generating personalized enterprise certification roadmaps with full policy traceability.

- Built a **5-agent pipeline** (Supervisor, Planner, Policy, Study, Memory) that cut manual curriculum-mapping effort significantly
- Grounded every agent output in real enterprise JSON policy via **Microsoft Foundry IQ**, eliminating hallucinations on source-dependent queries
- Engineered fault isolation: API timeouts, bounded token budgets, retry logic, and session-safe caching across all pipeline stages for high-concurrency stability

`Python` `GPT-4o` `Azure Foundry` `Streamlit`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛡️ [AI Crisis Detection System](https://github.com/ananyaSrivastavaa9/silent_sentinel)
**Edge AI Passive Safety Platform**

A passive, on-device safety monitor that detects danger without requiring user action.

- Designed a **3-pillar concurrent architecture**: CNN acoustic stress analysis on spectrograms, LSTM fall/gait detection on IMU telemetry, and a Dead Man's Switch FSM
- Built data pipelines on **UrbanSound8K** and **HAR** datasets, optimized for low-latency on-device inference
- **Privacy-first** — all inference stays on-device with zero cloud dependency

`Python` `TensorFlow` `CNN` `LSTM` `Streamlit`

</td>
<td width="50%" valign="top">

### 🌐 [AI Translator Pro](https://github.com/ananyaSrivastavaa9/Translator-Pro)
**[Live Demo ↗](https://ananyasrivastavaa9.github.io/Translator-Pro/)**

A real-time multi-modal translation dashboard across 14 languages, right in the browser.

- Orchestrated **3 async third-party APIs** — Azure Translator, Web Speech API, Tesseract.js OCR — into one unified ingestion pipeline
- Built a **local caching layer** for translation history, cutting redundant API calls and improving latency on repeat queries
- Auto language detection, language swap, TTS output, floating assistant UI

`JavaScript` `Azure Translator API` `Web Speech API` `Tesseract.js`

</td>
</tr>
</table>

---

## DSA & Problem Solving

<div align="center">

[![LeetCode Stats](https://leetcard.jacoblin.cool/ananyasrivastavaa?theme=dark&font=Fira%20Code&ext=contest)](https://leetcode.com/u/ananyasrivastavaa/)

</div>

- Solving problems regularly in **C++** — arrays, strings, recursion, linked lists, trees, sorting
- Current focus: **Two Pointers · Sliding Window · Recursion**
- Practice repos: [DSA-Cpp](https://github.com/ananyaSrivastavaa9/DSA-Cpp) · [Python-Practice](https://github.com/ananyaSrivastavaa9/Python-Practice) · [C-Programming](https://github.com/ananyaSrivastavaa9/C-Programming)

---

## GitHub Analytics

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=ananyaSrivastavaa9&theme=tokyonight&hide_border=true" height="170" />

![Followers](https://img.shields.io/github/followers/ananyaSrivastavaa9?style=for-the-badge&color=blueviolet&label=Followers)

</div>

---

## Certifications

- **Microsoft Certified: Azure AI Fundamentals (AI-900)** — Microsoft
- **Microsoft Certified: Azure Fundamentals (AZ-900)** — Microsoft
- **Threat Landscape 3.0** — Fortinet
- **Enterprise Design Thinking Practitioner** — IBM SkillsBuild
- **Generative AI Studio** — Google Cloud / Simplilearn
- **Professional Networking & Critical Thinking** — HP LIFE

---

<div align="center">

### Open to Software Engineering & AI/ML Internship Opportunities

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ananyasrivastavaa8)
[![Email](https://img.shields.io/badge/Send_an_Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ananyasrivastavaa9@gmail.com)

</div>
