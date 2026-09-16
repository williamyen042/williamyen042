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

### Student Software Developer — UT Austin Enterprise Technologies
> Backend Systems • API Design • Data Infrastructure

#### 🔐 DNAC API Proxy
- Built a Java (Javalin) proxy layer mapping local endpoints to Cisco DNAC APIs  
- Designed JSON-configurable routing and transformation system  
- Implemented field-level data sanitization (hashing, blanking, removal) for sensitive information  
- Enforced strict API contract behavior with validation and error handling  

#### 🔄 XMP → DNAC API Translator
- Developed translation layer between internal XMP APIs and external DNAC schema  
- Normalized and transformed responses to match expected API contracts  
- Implemented deterministic fallback logic for incomplete data  
- Enabled interoperability across incompatible systems  

#### 📊 Network Data Audit & Reconciliation Tool
- Built Python pipeline to compare network datasets across XMP DB and Infoblox  
- Generated structured CSV reports highlighting inconsistencies and overlaps  
- Identified missing DNS reverse zones and metadata gaps  
- Improved data reliability and audit visibility  

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

🔗 https://github.com/sillywillyatUT/SyllaSync

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

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=williamyen042&show_icons=true&theme=github_dark&hide_border=true" height="160" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=williamyen042&layout=compact&theme=github_dark&hide_border=true" height="160" />
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com?user=williamyen042&theme=dark&background=0D1117&hide_border=true" height="160" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1F6FEB,100:0D1117&height=100&section=footer" />
</p>
