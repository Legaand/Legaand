<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/banner-light.svg">
  <img alt="Legend Yang — Software Engineer, Mathematics of Computation @ UCLA" src="assets/banner-dark.svg">
</picture>

<p>
  <a href="https://legaand.github.io/Legend-Personal-Website/"><img alt="Website" src="https://img.shields.io/badge/Website-0D1117?style=flat-square&logo=googlechrome&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/legendyang/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="mailto:yanglegend84@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white"></a>
</p>

## About

I'm a Mathematics of Computation student at UCLA (Class of 2028, GPA 3.95/4.0) who builds backend and AI systems that have to hold up under real traffic.

Most of my work sits where distributed infrastructure meets applied machine learning: Kafka-based ingestion pipelines scaled across dozens of parsers, hybrid retrieval systems combining structured filtering with embedding search, and constraint solvers that turn messy institutional data into decisions people actually act on. I care about the unglamorous parts — failure isolation, retry semantics, latency and cost budgets — because those are what separate a demo from something that runs.

Currently a Software Engineer Intern on AI Applications at **Liba Space**, working onsite on an auto-job-apply pipeline and the platform around it. Previously a student researcher at the **National University of Singapore** on AI agents for financial prediction, with published work in LLM fine-tuning and AI-assisted disaster response.

Originally from Singapore, now in Los Angeles. Open to internships and research work.

## Experience

| | Role | Focus |
|---|---|---|
| **Jun – Sept 2026** | Software Engineer Intern, AI Applications — **Liba Space** | Distributed job-ingestion on Kafka microservices scaled to 33 parsers across 18 ATS platforms; dual-lane fetch architecture (httpx/curl_cffi vs. Playwright); pipeline observability in MySQL on EC2 driving application success to ~80%; in-house A/B test lifting signups ~35% |
| **Jun – Aug 2025** | Student Researcher — **National University of Singapore** | AI agents for stock price prediction and decision-making; built and deployed a platform for benchmarking agents against code implementations. Supervised by Assoc. Prof. Liang Zhenkai |
| **Aug – Dec 2024** | Engineer Intern — **Futurum Academy**, Singapore | Mentored two competitive VEX V5 robotics teams; coached mechanical design, autonomous path planning and CAD |
| **May – Sept 2023** | Director, Singapore Chapter — **San Antonio Math Include** | Launched the org's first Singapore chapter; recruited 7 tutors serving 30+ students across 7 STEM disciplines, partnering 5 schools and 3 organizations |

## Projects

| Project | Description | Stack |
|---|---|---|
| [**Research Interest Matching**](https://github.com/Legaand/faculty-project_nextjs) | Faculty-matching platform with semantic search across 300+ professor profiles, collapsing hours of page-by-page review into one query. Local sentence-transformer embeddings in a FAISS index moved inference in-process to cut latency and cost. RAG chatbot with multi-query expansion, an agentic tool-calling loop and running-summary memory, streamed in real time | `Next.js` `FastAPI` `FAISS` `LangGraph` `MySQL` |
| [**Double Major Optimization**](https://github.com/Legaand/Project-UCLA) | Degree planning as a constraint-satisfaction problem — a recursive solver resolving AND/OR requirement trees and prerequisite chains to compute minimum course sets and cross-major overlap. Multistage pipeline turned 200+ program pages into a normalized database of 8,000+ courses. Used by classmates for real planning | `Python` `Gemini API` `FastAPI` `Next.js` `CSP` |
| **OHMS** | Full-stack AI music composition platform built at the Google DeepMind × UCLA Hackathon — **Honorable Mention among 200+ teams**. Real-time gesture-to-audio control via MediaPipe dual-hand tracking feeding a Strudel live-coding engine, with Lyria and Gemini Flash generating music from language, voice and gesture | `MediaPipe` `Lyria` `Gemini` `Strudel` `Supabase` |
| [**Jobright ATS Distill**](https://github.com/Legaand/Jobright-ATS-Distill) | Distilling résumé ↔ posting relevance scoring down to something small and fast | `Python` `PyTorch` |
| [**mindset-fastapi**](https://github.com/Legaand/mindset-fastapi) | FastAPI service backing the mindset work | `FastAPI` `Python` |
| [**Personal Website**](https://github.com/Legaand/Legend-Personal-Website) | Hand-built portfolio — custom momentum scroll, no framework runtime, progressive enhancement throughout | `Next.js` `Vercel` |

## Publications

- Tang, Y., Li, Z., Yu, J., & **Yang, L.** (2025). *A Simple Approach of Chinese Poetry Generation Using Pre-trained LLMs.* 106–112. [doi:10.1145/3726101.3726121](https://doi.org/10.1145/3726101.3726121)
- **Yang, L.** (2024). *Resilience enhancement for interdependent power systems by AI-assisted disaster response.* Applied and Computational Engineering, 95, 216–229. [doi:10.54254/2755-2721/95/20241640](https://doi.org/10.54254/2755-2721/95/20241640)

## Tech Stack

| | |
|---|---|
| **Languages** | `Python` `TypeScript` `Java` `C++` `SQL` `Swift` |
| **Backend & Infra** | `FastAPI` `Kafka` `MySQL` `AWS EC2` `Playwright` `Supabase` `Linux` `Docker` |
| **AI & Data** | `LangChain` `LangGraph` `FAISS` `RAG pipelines` `sentence-transformers` `PyTorch` `Gemini API` `Pandas` `BeautifulSoup` |
| **Frontend** | `Next.js` `React` `Vue 3` |
| **Tooling** | `Git` `GitHub Actions` `Vercel` `Render` |

## Stats

<p>
  <img height="150" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=Legaand&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&title_color=58A6FF&icon_color=58A6FF&text_color=B6C2CF&bg_color=00000000">
  <img height="150" alt="Most used languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Legaand&layout=compact&hide_border=true&langs_count=8&title_color=58A6FF&text_color=B6C2CF&bg_color=00000000">
</p>

---

<sub>[Website](https://legaand.github.io/Legend-Personal-Website/) · [LinkedIn](https://www.linkedin.com/in/legendyang/) · [Email](mailto:yanglegend84@gmail.com)</sub>
