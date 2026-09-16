<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,100:1F6FEB&height=200&section=header&text=William%20Yen&fontSize=52&fontColor=FFFFFF&animation=fadeIn&fontAlignY=36&desc=LLM%20Agents%20%E2%80%A2%20Evaluation%20%E2%80%A2%20Applied%20Computer%20Vision&descSize=18&descAlignY=58" alt="William Yen" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1200&color=58A6FF&center=true&vCenter=true&width=620&lines=Incoming+SWE+Intern+%40+PwC+TIDE;Prev+SDE+Intern+%40+IBM+Z+AIOps;Routing+accuracy+33%25+%E2%86%92+97%25+on+a+19-tool+agent;Building+PassForm+%E2%80%94+CV+volleyball+coach" alt="Typing summary" />
</p>

---

## 🌐 Connect With Me

<p align="center">
  <a href="https://linkedin.com/in/wy042">
    <img src="https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin" />
  </a>
  <a href="https://instagram.com/williamyen_">
    <img src="https://img.shields.io/badge/Instagram-0D1117?style=for-the-badge&logo=instagram" />
  </a>
  <a href="mailto:williamyen042@gmail.com">
    <img src="https://img.shields.io/badge/Email-0D1117?style=for-the-badge&logo=gmail" />
  </a>
</p>

---

## 👨‍💻 About Me

I build LLM agent systems and the evaluation infrastructure that keeps them honest — multi-agent orchestration, hybrid retrieval, and LLM-as-judge test harnesses — plus applied computer vision on the side.

My work centers on turning LLM capabilities into production systems with measurable behavior: routing accuracy, latency, and regression gates, not demos.

---

## 🏢 Experience

### Incoming Software Engineer Intern — PwC TIDE (Fall 2026)
> Agentic AI • LLM Systems • Tax Technology

- Joining the Tax Innovation & Delivery Experience team to build AI tools that modernize tax workflows

---

### Software Developer Intern — IBM Z AIOps (Summer 2026)
> Agentic AI • LLM Evaluation • Backend Performance

- Cut dependency-traversal latency 25–45% and API calls up to 47% by profiling a performance bottleneck to an
N+1 query pattern in a graph traversal and rewriting it with two-phase batch fetching
- Built and maintained developer tooling — a 73-case Promptfoo test harness with an LLM-as-judge grader —
cutting each validation cycle from 2 min to 5–10 s and gating every deployment
- Shipped the ServiceNow agent for IBM's internal Z-mainframe LLM assistant end to end, orchestrating 19 Python
tools across services via LangGraph/LangChain with hybrid lexical + embedding semantic search (ChromaDB)
- Raised the agent's routing accuracy from 33% to 97% (71/73 cases) by root-causing a systematic failure mode and
rewriting the prompt routing table across 14 workflows

---

### Student Technician (Software Engineer) — UT Austin Enterprise Technologies (Sep 2025 – Present)
> Backend Systems • API Design • Network Data Infrastructure — all tools below run in production

#### 🔐 DNAC API Proxy + XMP → DNAC Translator
- Config-driven Java (Javalin) proxy emulating Cisco Catalyst Center's API, sanitizing Wi-Fi client PII and translating internal XMP data onto the DNAC schema  

#### 📦 Cisco Inventory Sync (`storeShowInvHistory`)
- Python parser syncing Cisco `show inventory` output to MySQL, with ping-status filtering and archive-table upserts  

#### 💲 Cisco Price History Tracker
- Nightly cron job loading Cisco price lists into MySQL, skipping non-newer effective dates with 3-year retention  

#### 📊 Subnet Audit & Reconciliation
- Python script reconciling TSC Tools and Infoblox subnets into a CSV report of overlaps, missing reverse DNS zones, and 180-day IP utilization  

---

## 🚀 Current Status

- 🔭 Currently building: **PassForm** — volleyball passing form analyzer (see below)
- 🌱 Currently learning: **distributed systems, production ML infrastructure**
- 🤝 Looking to collaborate on: **AI agents, eval tooling, and applied CV systems**

---

## 🧠 Featured Projects

### 🏐 PassForm *(in progress)*
> Computer-vision coach for volleyball passing form

- Tracks a passer with OpenCV + MediaPipe + YOLO-pose and measures joint angles at the moment of ball contact  
- Separate pass-quality model scores the outcome (0–3) — 77% accuracy on ~250 hand-labeled reps  
- Fuses outcome score with measured form, so a lucky good pass off poor technique still gets form feedback  
- Debugged a fine-tuned YOLOv8 ball detector that had learned the gym's ceiling lights (transplant test: 118/118 → 12/118) and replaced it with stock COCO YOLOv8  
- Current bottleneck is dataset size — actively recording and labeling more reps  

🔗 https://github.com/williamyen042/passform

---

### 💬 Slack Searcher — Grounded Slack Q&A over MCP
> 5th of 93 teams at IBM's company-wide hackathon • public rebuild

- MCP server + Next.js chat UI that answers only from retrieved Slack messages, citing a permalink for every claim  
- Incremental cron indexer into a SQLite chunk/vector store — unchanged messages cost zero embedding calls  
- Dense, BM25 (Slack-aware tokenizer that keeps `ERR_500`, `us-east-1` intact), or hybrid retrieval fused with RRF  
- 139 offline tests, including a real JSON-RPC protocol conformance suite  
- Public channels only by design; query-time permission filtering is the documented prerequisite for private channels  

🔗 https://github.com/williamyen042/slack_searcher

---

### 🔎 RAG From Scratch
> Building a retrieval-augmented generation pipeline from first principles

- Custom document ingestion, chunking, and embedding pipeline  
- Retrieval + reranking strategies to improve answer quality  
- Focus on evaluation, observability, and system performance  

🔗 https://github.com/williamyen042/rag-from-scratch

---

### 📅 SyllaSync
> AI-powered syllabus → calendar automation (~100 users)

- Upload a syllabus PDF; an LLM extracts assignments, exams, and deadlines for user review  
- Exports to Google Calendar (OAuth) or .ics  
- Next.js 14 + TypeScript + Supabase (Postgres/auth/storage) on Netlify Functions; Groq primary with Gemini fallback on rate limits  

🔗 https://github.com/williamyen042/SyllaSync

---

### ⚙️ Meeting Notes → Jira Automation
> Automating post-meeting workflows with LLMs

- Converts unstructured meeting notes into structured Jira tickets  
- Serverless architecture using AWS Lambda  
- Focus on real-world productivity automation  

---

## 🛠 Tech Stack

### Languages
![Python](https://img.shields.io/badge/Python-0D1117?style=for-the-badge&logo=python)
![TypeScript](https://img.shields.io/badge/TypeScript-0D1117?style=for-the-badge&logo=typescript)
![Java](https://img.shields.io/badge/Java-0D1117?style=for-the-badge&logo=openjdk)
![SQL](https://img.shields.io/badge/SQL-0D1117?style=for-the-badge&logo=mysql)

### LLM / Agents
![LangGraph](https://img.shields.io/badge/LangGraph-0D1117?style=for-the-badge&logo=langchain)
![LangChain](https://img.shields.io/badge/LangChain-0D1117?style=for-the-badge&logo=langchain)
![ChromaDB](https://img.shields.io/badge/ChromaDB-0D1117?style=for-the-badge)
![Promptfoo](https://img.shields.io/badge/Promptfoo-0D1117?style=for-the-badge)
![MCP](https://img.shields.io/badge/MCP-0D1117?style=for-the-badge)

### Computer Vision / ML
![PyTorch](https://img.shields.io/badge/PyTorch-0D1117?style=for-the-badge&logo=pytorch)
![OpenCV](https://img.shields.io/badge/OpenCV-0D1117?style=for-the-badge&logo=opencv)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0D1117?style=for-the-badge)
![YOLOv8](https://img.shields.io/badge/YOLOv8-0D1117?style=for-the-badge)

### Web / Backend
![React](https://img.shields.io/badge/React-0D1117?style=for-the-badge&logo=react)
![Next.js](https://img.shields.io/badge/Next.js-0D1117?style=for-the-badge&logo=nextdotjs)
![Tailwind](https://img.shields.io/badge/Tailwind-0D1117?style=for-the-badge&logo=tailwindcss)
![Javalin](https://img.shields.io/badge/Javalin-0D1117?style=for-the-badge)
![MySQL](https://img.shields.io/badge/MySQL-0D1117?style=for-the-badge&logo=mysql)
![Supabase](https://img.shields.io/badge/Supabase-0D1117?style=for-the-badge&logo=supabase)

### Tools & Cloud
![AWS](https://img.shields.io/badge/AWS-0D1117?style=for-the-badge&logo=amazonaws)
![Netlify](https://img.shields.io/badge/Netlify-0D1117?style=for-the-badge&logo=netlify)
![Docker](https://img.shields.io/badge/Docker-0D1117?style=for-the-badge&logo=docker)
![Git](https://img.shields.io/badge/Git-0D1117?style=for-the-badge&logo=git)

---

## 📊 GitHub Metrics

<p align="center">
  <img src="./metrics.svg" alt="GitHub metrics" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1F6FEB,100:0D1117&height=100&section=footer" />
</p>
