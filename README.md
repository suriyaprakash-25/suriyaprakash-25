<!-- ═══════════════════════════════ HERO ═══════════════════════════════ -->
<p align="center">
  <img src="./profile/header.svg" width="100%" alt="Suriyaprakash R M: AI · Software · Cloud · Products" />
</p>

<div align="center">

<!-- 📸 PHOTO: save a square photo as profile/avatar.png (ideally pre-cropped to a circle
     with a transparent background), then change the src below to ./profile/avatar.png -->
<img src="./profile/avatar.svg" width="168" alt="Suriyaprakash R M" />

### Hi, I'm Suriyaprakash 👋

**AI & software engineer · B.Tech Artificial Intelligence & Data Science**

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&duration=2800&pause=900&color=38BDF8&center=true&vCenter=true&width=720&lines=I+build+AI+systems+that+ship+to+real+users.;ML+%C2%B7+LLM+agents+%C2%B7+full-stack+%C2%B7+cloud.;Curiosity+%E2%86%92+Experiment+%E2%86%92+Build+%E2%86%92+Break+%E2%86%92+Learn+%E2%86%92+Ship" alt="I build AI systems that ship to real users." />

<p>
  <a href="https://www.suriyaprakashrm.dev/"><img src="https://img.shields.io/badge/Portfolio-suriyaprakashrm.dev-0B1120?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/suriyaprakash-r-m-64133a327/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:suriyaprakashrm25@gmail.com"><img src="https://img.shields.io/badge/Email-Say_hi-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://huggingface.co/Suriya-25"><img src="https://img.shields.io/badge/Hugging_Face-Spaces-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face" /></a>
</p>

<a href="https://github.com/suriyaprakash-25?tab=followers"><img src="https://img.shields.io/github/followers/suriyaprakash-25?label=Followers&style=social" alt="GitHub followers" /></a>
&nbsp;
<img src="https://komarev.com/ghpvc/?username=suriyaprakash-25&label=Profile%20views&color=38bdf8&style=flat" alt="Profile views" />

</div>

<!-- ═══════════════════════════════ ABOUT ═══════════════════════════════ -->

## About me

I build at the intersection of **AI, software engineering, data and product**. My approach: pick a real problem, prototype quickly, break it on purpose, find out why it broke, and ship something people can use.

- 🔭 **Building:** [AgentShelf](https://github.com/suriyaprakash-25/AgentShelf), an MCP storefront that AI shopping agents can search and buy from, and [BoreSakshi](https://github.com/suriyaprakash-25/BoreSakshi), which predicts borewell success for farmers
- 🧠 **Focus:** ML engineering, LLM agents (MCP, LangGraph), explainable AI, full-stack systems
- 🌱 **Learning:** distributed systems, system design at scale, MLOps
- 🏆 **Recent:** PayPal Mentorship Program · InnoHack (VIT) finalist · three 2nd-place wins in 2025
- 💬 **Ask me about:** shipping ML to production, Python/FastAPI backends, React frontends
- 📫 **Reach me:** [suriyaprakashrm25@gmail.com](mailto:suriyaprakashrm25@gmail.com). I'm open to internships, collaborations and interesting problems

<!-- ═══════════════════════════════ WORK ═══════════════════════════════ -->

## Featured work

<table>
<tr>
<td width="50%" valign="top">

### 🛍️ [AgentShelf](https://github.com/suriyaprakash-25/AgentShelf)
**Made by you. Found by AI.**

Turns WhatsApp product photos and voice notes from independent sellers into an **AI-discoverable MCP storefront**, with server-verified quotes and human-approved PayPal checkout.

- MCP server exposing catalog search, quotes, checkout and order status
- Vision-drafted listings that the seller confirms, plus schema.org storefronts
- PayPal Orders v2 integration with webhook verification

`FastAPI` `PostgreSQL` `MCP` `PayPal` `React`

</td>
<td width="50%" valign="top">

### 💧 [BoreSakshi](https://github.com/suriyaprakash-25/BoreSakshi)
**Know before you drill.**

A verified-outcome network and AI prediction engine that tells rural households **where a borewell is likely to succeed, how deep to drill and what yield to expect**, before they spend lakhs.

- Success, depth and yield models with calibration and **conformal uncertainty**
- Geospatial feature extraction and human-approved model deployment
- Separate farmer, rig-operator and admin interfaces

`Node` `MongoDB` `FastAPI` `scikit-learn` `Leaflet`

[**Live demo →**](https://boresakshi.vercel.app)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🩺 [SepsisSense](https://github.com/suriyaprakash-25/SepsisSense)
**Early sepsis detection for ICU patients.**

An end-to-end ML pipeline on the **PhysioNet 2019** dataset that predicts sepsis onset and explains every prediction.

- Clinical feature engineering: rolling vitals, Shock Index, qSOFA and lab trends
- GPU-trained XGBoost/LightGBM with patient-level temporal splits
- **SHAP** per-patient explanations in a Streamlit dashboard

`Python` `XGBoost` `SHAP` `Streamlit`

</td>
<td width="50%" valign="top">

### 🎯 [Redrob Ranker](https://github.com/suriyaprakash-25/redrob-ranker)
**Hackathon candidate-ranking engine.**

A multi-stage pipeline that ranks the top 100 candidates out of **100,000 in about 64 seconds on a CPU, with zero LLM calls**.

- Honeypot detection, structured JD-fit scoring, TF-IDF/SVD semantic match
- Trust and availability modifiers, deterministic reasoning
- LLM re-ranking was tested and rejected: it would take 2.8–55 hours against a 300-second budget

`Python` `scikit-learn` `NLP` `Hugging Face`

[**Live demo →**](https://huggingface.co/spaces/Suriya-25/redrob-ranker)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛡️ [AutoShield Edge AI](https://github.com/suriyaprakash-25/AutoShield-Edge-AI)
**CAN-bus intrusion detection for vehicles.**

A gateway-oriented automotive cybersecurity proof of concept that combines rules and ML specialists to catch attacks on in-vehicle networks.

- Detects DoS, fuzzing, RPM spoofing and gear spoofing
- Per-ID rate policy, CAN-ID allowlist and logistic-regression specialists
- Live dashboard with an animated vehicle digital twin

`Python` `ML` `Embedded/Edge` `Cybersecurity`

</td>
<td width="50%" valign="top">

### 📊 [AskMetrics](https://github.com/suriyaprakash-25/AskMetrics)
**Ask your database in plain English.**

Natural-language analytics over a commerce database, powered by a **local LLM (Qwen3 8B via Ollama)** with strict safety guarantees.

- Schema-aware prompting with business-semantic hints
- AST-checked SQL validation that allows a single read-only statement
- Bounded, time-limited execution against a sandboxed database

`FastAPI` `React` `TypeScript` `Ollama` `SQL`

</td>
</tr>
</table>

<details>
<summary><b>More projects →</b></summary>
<br>

| Project | What it is | Stack | Links |
|---|---|---|---|
| **DrivePortz (Digital Twin)** | Full-stack digital twin of real-world vehicles | JavaScript · Node · React | [Code](https://github.com/suriyaprakash-25/Digital-Twin) · [Live](https://www.driveportz.com/) |
| **MedFlow Guardian** | Patient-controlled medical records with time-limited, auditable access sharing between hospitals | FastAPI · PostgreSQL · React · FHIR | [Code](https://github.com/suriyaprakash-25/medflow-guardian) |
| **CounterGuard** | Multi-agent counterfeit and grey-market investigation that scores marketplace listings for risk | FastAPI · LangGraph · Scraping | [Code](https://github.com/suriyaprakash-25/counterguard-ai) |
| **STATUTEK** | Compliance and legal-tech startup platform | React · Tailwind · Framer Motion | [Code](https://github.com/suriyaprakash-25/STATUTEK) · [Live](https://statutek.vercel.app/) |
| **CrowdFundX** | Crowdfunding web platform | JavaScript | [Code](https://github.com/suriyaprakash-25/CrowdFundX) · [Live](https://crowd-fund-x-psi.vercel.app/) |
| **KnowledgeNest** | Knowledge-sharing platform | JavaScript | [Code](https://github.com/suriyaprakash-25/knowledgenest) · [Live](https://knowledgenest-nine.vercel.app) |

</details>

<!-- ═══════════════════════════════ STACK ═══════════════════════════════ -->

## Tech stack

<table>
<tr><td><b>Languages</b></td><td><img src="https://skillicons.dev/icons?i=py,cpp,java,js,ts&theme=dark" alt="Python, C++, Java, JavaScript, TypeScript" /></td></tr>
<tr><td><b>AI / ML</b></td><td><img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn&theme=dark" alt="PyTorch, TensorFlow, scikit-learn" /> <br><sub>XGBoost · LightGBM · SHAP · Keras · Pandas · NumPy · LangGraph · MCP · Ollama</sub></td></tr>
<tr><td><b>Backend</b></td><td><img src="https://skillicons.dev/icons?i=fastapi,nodejs,express&theme=dark" alt="FastAPI, Node.js, Express" /></td></tr>
<tr><td><b>Frontend</b></td><td><img src="https://skillicons.dev/icons?i=react,nextjs,vite,tailwind&theme=dark" alt="React, Next.js, Vite, Tailwind" /></td></tr>
<tr><td><b>Data</b></td><td><img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,sqlite,supabase&theme=dark" alt="PostgreSQL, MySQL, MongoDB, SQLite, Supabase" /></td></tr>
<tr><td><b>Cloud / DevOps</b></td><td><img src="https://skillicons.dev/icons?i=docker,githubactions,vercel,git,linux&theme=dark" alt="Docker, GitHub Actions, Vercel, Git, Linux" /></td></tr>
</table>

<!-- ═══════════════════════════════ ACHIEVEMENTS ═══════════════════════════════ -->

## Achievements

| | |
|---|---|
| 🏢 **PayPal Mentorship Program** | Selected for industry mentorship in real-world software engineering |
| ✈️ **Fly to Singapore 12.0 qualifier (RYLA 54.0)** | Selected on entrepreneurship, business planning and leadership |
| 🏁 **Finalist, InnoHack (VIT University)** | National-level hackathon |
| 🥈 **2nd Prize, Creatathon 2025** | |
| 🥈 **2nd Prize, Freshathon 2025** | |
| 🥈 **2nd Prize, Web Design Showdown 2025** | |

<!-- ═══════════════════════════════ GITHUB ═══════════════════════════════ -->

## GitHub activity

<div align="center">

<img src="./profile/github-stats.svg" height="170" alt="GitHub stats" />
<img src="./profile/top-langs.svg" height="170" alt="Top languages" />

<img src="https://activity-graph.vercel.app/graph?username=suriyaprakash-25&theme=github-compact&hide_border=true&area=true" width="100%" alt="Contribution activity graph" />

</div>

<!-- ═══════════════════════════════ CONTACT ═══════════════════════════════ -->

<div align="center">

## Let's build something

I'm always up for an interesting problem, a collaboration or a conversation about AI and products.

<a href="mailto:suriyaprakashrm25@gmail.com"><img src="https://img.shields.io/badge/Email_me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://www.linkedin.com/in/suriyaprakash-r-m-64133a327/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://www.suriyaprakashrm.dev/"><img src="https://img.shields.io/badge/Portfolio-0B1120?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>

<sub><code>Curiosity → Experiment → Build → Break → Learn → Ship</code></sub>

</div>
