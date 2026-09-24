<img src="https://capsule-render.vercel.app/api?type=waving&color=0:E4472B,50:FF6A4A,100:F2A516&height=200&section=header&text=Pranjal%20Verma&fontSize=48&fontColor=ffffff&fontAlignY=38&desc=Agentic%20AI%20%C2%B7%20Production%20RAG%20%C2%B7%20Systems%20Engineer&descSize=16&descAlignY=58&descColor=ffe5d9&animation=twinkling" width="100%" />

<p align="center">
  <a href="https://pranjal-portfolio-n0hd.onrender.com"><img src="https://img.shields.io/badge/Portfolio-0D1117?style=for-the-badge&logo=render&logoColor=FF6A4A" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/pranjal-verma-351546246/"><img src="https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=FF6A4A" alt="LinkedIn" /></a>
  <a href="mailto:pranjal17112004verma@gmail.com"><img src="https://img.shields.io/badge/Email-0D1117?style=for-the-badge&logo=gmail&logoColor=FF6A4A" alt="Email" /></a>
  <a href="https://github.com/PranjalPV"><img src="https://img.shields.io/badge/GitHub-0D1117?style=for-the-badge&logo=github&logoColor=FF6A4A" alt="GitHub" /></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=PranjalPV&style=for-the-badge&color=FF6A4A&labelColor=0D1117&label=PROFILE+VIEWS" alt="Profile Views" />
</p>

---

## `> whoami`

```ts
const pranjal = {
  role:        "Agentic AI & Systems Engineer",
  education:   "B.Tech CSE @ Amity University Lucknow (2023–2027) · CGPA 8.63",
  scholarship: "50% Merit Scholarship",
  focus:       ["Multi-Agent Orchestration", "Production Hybrid RAG", "Event-Driven Backends"],
  currently:   "Building autonomous literature intelligence & adaptive clinical engines",
  leadership:  ["Student Placement Coordinator", "FOSS United Lucknow Volunteer"],
  speedcubing: "3x3 PB: 29s (chasing sub-25) ⚡",
  philosophy:  "Scramble → Solve: Every chaotic problem reduces to systematic algorithms."
};
```

---

## 🛠️ Tech Stack

<p>
  <b>AI & Frameworks:</b>
  <img src="https://img.shields.io/badge/CrewAI-161B22?style=flat-square&logo=crewai&logoColor=FF6A4A" />
  <img src="https://img.shields.io/badge/LangGraph-161B22?style=flat-square&logo=langchain&logoColor=FF6A4A" />
  <img src="https://img.shields.io/badge/ChromaDB-161B22?style=flat-square&logo=databricks&logoColor=FF6A4A" />
  <img src="https://img.shields.io/badge/Hybrid_RAG_(BM25_+_Dense)-161B22?style=flat-square&logo=target&logoColor=FF6A4A" />
  <img src="https://img.shields.io/badge/Sentence--Transformers-161B22?style=flat-square&logo=huggingface&logoColor=FFD21E" />
  <img src="https://img.shields.io/badge/Ollama-161B22?style=flat-square&logo=ollama&logoColor=white" />
</p>
<p>
  <b>Languages:</b>
  <img src="https://img.shields.io/badge/Python-161B22?style=flat-square&logo=python&logoColor=3776AB" />
  <img src="https://img.shields.io/badge/C++-161B22?style=flat-square&logo=cplusplus&logoColor=00599C" />
  <img src="https://img.shields.io/badge/Java-161B22?style=flat-square&logo=openjdk&logoColor=ED8B00) />
  <img src="https://img.shields.io/badge/JavaScript-161B22?style=flat-square&logo=javascript&logoColor=F7DF1E" />
  <img src="https://img.shields.io/badge/TypeScript-161B22?style=flat-square&logo=typescript&logoColor=3178C6" />
  <img src="https://img.shields.io/badge/SQL-161B22?style=flat-square&logo=postgresql&logoColor=4169E1" />
</p>
<p>
  <b>Backend & Web:</b>
  <img src="https://img.shields.io/badge/FastAPI-161B22?style=flat-square&logo=fastapi&logoColor=009688" />
  <img src="https://img.shields.io/badge/WebSockets-161B22?style=flat-square&logo=socket.io&logoColor=FF6A4A" />
  <img src="https://img.shields.io/badge/React-161B22?style=flat-square&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Three.js-161B22?style=flat-square&logo=three.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Pydantic-161B22?style=flat-square&logo=pydantic&logoColor=E92063" />
  <img src="https://img.shields.io/badge/Docker-161B22?style=flat-square&logo=docker&logoColor=2496ED" />
  <img src="https://img.shields.io/badge/Linux-161B22?style=flat-square&logo=linux&logoColor=FCC624" />
</p>

---

## 🚀 Featured Projects

### [Agentic AI Academic Researcher 2.0](https://github.com/PranjalPV/agentic-ai-researcher)
*Autonomous 4-agent literature engine that discovers, ingests, and synthesizes preprint research with grounded citations.*

- **Multi-Agent Orchestration:** 4 specialized CrewAI agents (Scout, Ingestion Engineer, Reviewer, Strategist) for end-to-end literature intelligence.
- **Hybrid RAG with RRF:** Fuses dense vector embeddings (`all-MiniLM-L6-v2`) with sparse lexical tokens (`BM25Okapi`) via Reciprocal Rank Fusion ($k=60$) to eliminate technical acronym collisions.
- **Benchmarked:** Evaluated on academic queries achieving **1.000 MRR, 1.000 Hit Rate @ 3**, and **13ms latency**.
- **Stack:** `CrewAI` · `ChromaDB` · `FastAPI` · `PyMuPDF` · `Streamlit` · `Docker`

🔗 [**Live App**](https://agentic-ai-researcher-zhez8oldbyi7tzpqtx5eru.streamlit.app/) · [**GitHub Repository**](https://github.com/PranjalPV/agentic-ai-researcher)

---

### [Adaptive Hospital Triage & Queue Priority System](https://github.com/PranjalPV/triage-project)
*Event-driven clinical queue management system dynamically prioritizing patients based on severity, wait times, and hospital congestion.*

- **Adaptive Prioritization:** Uses logistic weighting $\text{Priority}_i = W_s \cdot S_i + W_w \cdot W_i$ driven by live Clinical Pressure (CPI) and Congestion (CI) indices to prevent waiting room deterioration.
- **RAG Diagnosis:** 2,422 symptom-disease embeddings (`all-mpnet-base-v2`) with sub-millisecond cosine search coupled with Gemini LLM ESI categorization.
- **Real-Time Pipeline:** Event-driven queue recalculation pushed via WebSockets upon patient arrival, vitals alteration, or 5-minute timers.
- **Stack:** `FastAPI` · `WebSockets` · `Gemini API` · `React` · `Python` · `Pydantic`

🔗 [**GitHub Repository**](https://github.com/PranjalPV/triage-project)

---

### [Agentic Job Recommender & Resume Assistant](https://github.com/PranjalPV/agentic-job-ai)
*Multi-agent recruitment assistant extracting competencies from resumes, matching job posts, and generating learning roadmaps.*

- **6-Node LangGraph Pipeline:** Coordinates resume parsing, job discovery, vector similarity matching, skill-gap analysis, cover letter drafting, and roadmap generation.
- **Actionable Gap Analysis:** Pinpoints missing technical competencies per role and dynamically structures a phased upskilling curriculum.
- **Stack:** `LangGraph` · `LangChain` · `FastAPI` · `React` · `Python`

🔗 [**Live App**](https://agentic-job-ai-ui.onrender.com/) · [**GitHub Repository**](https://github.com/PranjalPV/agentic-job-ai)

---

### [Interactive 3D Portfolio ("Scramble → Solve")](https://github.com/PranjalPV/pranjal-portfolio)
*Personal portfolio featuring an interactive kinematic 3D Rubik's Cube simulation and agent execution replay engine.*

- **Kinematic 3D Cube:** 26 individual cubies rendered in Three.js with layer dragging and keyboard notation controls (`R U R' U'`).
- **Zero-API-Cost Replay Engine:** Deterministic JSON trace runners for multi-agent workflows, ensuring instant page loads without quota limits.
- **Performance:** Sub-60KB initial JS payload, adhering to 95+ Lighthouse standards.
- **Stack:** `Three.js` · `HTML5 Canvas` · `JavaScript` · `CSS3`

🔗 [**Live App**](https://pranjal-portfolio-n0hd.onrender.com) · [**GitHub Repository**](https://github.com/PranjalPV/pranjal-portfolio)

---

## 📈 Activity & Metrics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=PranjalPV&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=FF6A4A&icon_color=FF6A4A&text_color=c9d1d9" height="150" alt="GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=PranjalPV&theme=tokyonight&hide_border=true&background=0D1117&ring=FF6A4A&fire=FF6A4A&currStreakLabel=FF6A4A" height="150" alt="GitHub Streak" />
</p>

---

## 🎓 Education & Roles

**B.Tech, Computer Science & Engineering** · Amity University Lucknow · `2023 – 2027`
> **CGPA: 8.63** · **50% Merit Scholarship**

- **Student Placement Coordinator:** Coordinating placement activities and student preparedness across the department.
- **FOSS United Lucknow Volunteer:** Contributing to open-source events, developer meetups, and technical workshops.

---

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:F2A516,50:FF6A4A,100:E4472B&height=100&section=footer&reversal=true" width="100%" />

<p align="center">
  <i>"Scramble → Solve: Breaking high-entropy problems into deterministic algorithms."</i><br>
  <b>Open to Agentic AI, GenAI & Software Engineering Opportunities</b>
</p>
