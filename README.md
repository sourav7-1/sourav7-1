<h1 align="left">Hi, I'm Sourav Kundu Samya 👋</h1>

<p align="left">
  <b>CSE Student @ Daffodil International University · Backend Developer · AI/ML Enthusiast</b>
</p>

<p align="left">
  <a href="https://github.com/sourav7-1"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/sourav-kundu-samya-387496367/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:souravku0416@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <img src="https://komarev.com/ghpvc/?username=sourav7-1&label=Profile%20Views&color=0e75b6&style=for-the-badge" alt="Profile Views"/>
</p>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&vCenter=true&width=650&lines=Backend+%26+API+Development;AI%2FML+%26+Computer+Vision;GeoAI+%26+Remote+Sensing;Database+Engineering;Distributed+AI+Infrastructure" />

---

## 🧑‍💻 About Me

I'm a Computer Science & Engineering student at **Daffodil International University** who enjoys building complete, practical systems — not just models or UIs in isolation, but the backend, database, and AI layers working together.

My work sits at the intersection of **backend engineering, database design, AI/ML, computer vision, and geospatial data**. I've built role-based web platforms, satellite imagery pipelines, local AI video analysis tools, and a distributed GPU compute cluster.

**How I work:** `Concept → Architecture → Implementation → Testing → Deployment`

| | |
|---|---|
| 🔭 **Core focus** | Backend & API development · Database engineering · AI/ML · Computer vision · GeoAI |
| 🌱 **Currently exploring** | Containerized AI workloads · Distributed systems · Scalable API architecture |
| 🎯 **Long-term goal** | Build reliable, AI-powered software that solves real-world problems |
| 🤝 **Open to** | Internships · Research projects · Open-source collaboration |

---

## 🚀 Featured Projects

### 🏥 HealthIO — AI-Powered Healthcare Management Platform
<!-- TODO: add repo link + screenshot -->

A role-based healthcare platform that connects **patients, doctors, and doctor assistants** in one system. It digitizes the full appointment lifecycle and gives each role its own workflow, so doctors can focus on patients while assistants handle scheduling and coordination.

**Key features**
- **Three-role architecture** — dedicated workflows and dashboards for patients, doctors, and doctor assistants, enforced by role-based access control
- **Appointment management** — patients book appointments; assistants manage, reschedule, and confirm them on a doctor's behalf
- **Doctor-specific patient workflow** — each doctor sees and manages only their own patients and appointments
- **Patient–doctor communication** — direct communication channel within the platform
- **Healthcare information management** — structured storage of patient and appointment data in PostgreSQL
- **AI-assisted features** integrated into the healthcare workflow
- **Responsive interface** built with React, communicating with a FastAPI REST backend

**Tech stack:** `Python` `FastAPI` `React` `PostgreSQL` `REST API`

---

### 🍔 Smart Street Food Safety — Inspection & Risk Analysis System
[![Repo](https://img.shields.io/badge/View_Repository-181717?style=flat-square&logo=github)](https://github.com/sourav7-1/Food-Safety-System)

A database-driven platform for monitoring **street food hygiene**. It manages vendors, stalls, inspections, complaints, and corrective actions, and turns inspection data into hygiene grades and vendor risk levels to help prioritize enforcement.

**Key features**
- **Multi-role system** — separate access for administrators, inspectors, vendors, and customers
- **Inspection workflow** — inspection → hygiene scoring → grading → corrective action → reinspection scheduling
- **Risk analysis** — vendor risk levels calculated using SQL functions and analytical queries
- **Complaint management** — customers can file complaints that feed into inspection priorities
- **Location features** — map-based stall display and nearby-stall search for customers
- **Analytics dashboard** — charts summarizing inspections, grades, and risk distribution

**Tech stack:** `Python` `Flask` `MySQL` `SQLAlchemy` `JavaScript` `Chart.js` `Leaflet`

---

### 🌍 TerraWatch — Sentinel Remote Sensing & GeoAI
<!-- TODO: add repo link + screenshot -->

![Hackathon](https://img.shields.io/badge/Built_for-DIU_AI_Hackathon-blueviolet?style=flat-square)

A satellite remote sensing system that collects and processes **Sentinel-1 (radar) and Sentinel-2 (optical) imagery** for any region a user selects — such as a forest — and generates a **report on the area's environmental condition**, along with ML-ready geospatial datasets.

**Key features**
- **Interactive ROI selection** — draw a region of interest directly on a map
- **Automated area reports** — summarizes vegetation and environmental condition of the selected region (e.g. forest health)
- **Sentinel-1 GRD processing** — radar imagery usable regardless of cloud cover
- **Sentinel-2 processing** with automatic cloud filtering
- **Google Earth Engine integration** for large-scale imagery access and processing
- **Multi-band GeoTIFF export** at 10 m spatial resolution
- **Spectral indices** — NDVI, EVI, and NBR for vegetation health and burn analysis
- **Map-based visualization** of processed layers with Leaflet and OpenStreetMap

**Tech stack:** `Python` `Flask` `Google Earth Engine` `Sentinel-1` `Sentinel-2` `GeoTIFF` `Leaflet` `OpenStreetMap`

---

### 👁️ VisionScribe AI — Privacy-First Video Analysis & Transcription
<!-- TODO: add repo link + demo GIF -->

An AI video analysis system that detects **human face presence** and generates **timestamped speech transcripts** — designed to run fully locally so no video or audio leaves the user's machine.

**Key features**
- **Face presence detection** using SCRFD / InsightFace — detects *whether* a face is present, with no identity recognition
- **Video processing pipeline** with OpenCV for frame-level analysis
- **Audio extraction and transcription** using Faster-Whisper
- **Timestamped transcripts** aligned with the video timeline
- **Bengali and multilingual** speech support
- **Local, private processing** — no cloud dependency

**Tech stack:** `Python` `FastAPI` `OpenCV` `Faster-Whisper` `InsightFace` `SCRFD`

---

### ⚡ Distributed AI Infrastructure &nbsp;![Status](https://img.shields.io/badge/status-in%20progress-yellow?style=flat-square)
<!-- TODO: add repo link -->

A platform that pools **CPU and GPU resources from multiple machines** into a single private AI compute environment, so AI workloads can be scheduled across idle hardware instead of one machine.

**Architecture**
- **Central controller** that receives jobs and assigns them to worker nodes
- **Node agents** on each machine that report resources and execute jobs

**Key features**
- **Priority-based scheduling** and workload management across nodes
- **GPU and cluster health monitoring** in real time
- **Docker-based execution** for isolated, reproducible workloads
- **Tailscale private networking** to connect machines securely across networks
- **Wake-on-LAN** to power nodes on only when needed
- **React monitoring dashboard** with PostgreSQL-backed resource tracking

**Tech stack:** `Python` `FastAPI` `React` `Docker` `PostgreSQL` `Tailscale`

---

### 📂 Other Projects

| Project | Area | Description |
|---|---|---|
| 🎓 Student360 AI | AI / Education | AI-assisted student information and analytics platform |
| 💰 ZEN Bank Tracker | Web / Backend | Personal finance and transaction tracking system |
| 🍽️ Food Ordering System | Web / Programming | Food ordering application built for system design practice |
| 🤖 Human Following Robot | Robotics | Robot that detects and follows a person |
| 🔐 Digital Combination Lock | Digital Logic | Logic-circuit based security lock system |
| 🎯 Python Study Motivation | Computer Vision | Python/OpenCV computer vision experiment |
| 🎙️ AI Voice Assistant | AI / Automation | Python-based voice assistant |

---

## 🛠️ Technical Skills

**Languages**
<p><img src="https://skillicons.dev/icons?i=python,javascript,php,c,java"/></p>

**Backend & Frontend**
<p><img src="https://skillicons.dev/icons?i=fastapi,flask,laravel,react,nodejs,html,css"/></p>

**Databases**
<p><img src="https://skillicons.dev/icons?i=postgresql,mysql,sqlite"/></p>
`SQL` `Database Design` `Query Optimization` `SQLAlchemy`

**AI / ML / Computer Vision**
<p><img src="https://skillicons.dev/icons?i=pytorch,tensorflow,opencv"/></p>
`Scikit-learn` `Faster-Whisper` `InsightFace` `SCRFD`

**GeoAI & Remote Sensing**

`Google Earth Engine` `Sentinel-1` `Sentinel-2` `GeoTIFF` `NDVI / EVI / NBR` `Leaflet`

**Tools & Infrastructure**
<p><img src="https://skillicons.dev/icons?i=docker,git,github,linux"/></p>
`Tailscale` `MySQL Workbench` `REST API Design`

---

## 🏆 Achievements & Certifications

| | Achievement | Details |
|---|---|---|
| 🏅 | **Finalist — DIU AI Project Competition 2026** | Reached the final round <!-- TODO: add project name --> |
| 💡 | **Participant — DIU AI Hackathon** | Built **TerraWatch**, a Sentinel satellite remote sensing system that collects imagery for any region (e.g. forests) and generates an analytical report <!-- TODO: add year --> |
| 🎖️ | **Certificate of Achievement — Web Development with Laravel** | 7-day training by the **National Cyber Security Agency (NCSA), Bangladesh**, with the Dept. of CSE, Daffodil International University · Managed by SICL & TechOptions · **Score: 93** · Certificate ID `7464` |
| 📜 | **AI+ Prompt Engineer Level 1™** | AI CERTs™ · June 2025 · Credential ID `576065c59096` |

---

## 🎓 Education

**B.Sc. in Computer Science & Engineering** — Daffodil International University

Relevant coursework: Data Structures & Algorithms · Database Management Systems · Distributed Systems · Operating Systems · Computer Networks · Compiler Design · Theory of Computation

---

## 📊 GitHub Stats

<!-- Public instance is often rate-limited; deploy your own github-readme-stats on Vercel and replace these URLs -->
<p>
  <img src="https://github-readme-stats.vercel.app/api?username=sourav7-1&show_icons=true&hide_border=true" height="160"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sourav7-1&layout=compact&hide_border=true" height="160"/>
</p>
<p><img src="https://streak-stats.demolab.com?user=sourav7-1&hide_border=true" /></p>

---

<p align="center"><i>Build · Learn · Experiment · Improve — turning ideas into working systems.</i></p>
