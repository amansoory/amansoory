# Arman Hassan

**Software engineering · Applied AI · Backend systems**  
Computer Science at UNC Chapel Hill, with a minor in Data Science. Graduating May 2027.

[**Portfolio →**](https://armanhassan.com) · [**LinkedIn →**](https://linkedin.com/in/arman-hassan1)

I build software that connects models, data, and usable interfaces. My recent work includes a source-grounded degree planner, a repository security scanner, and a live experiment comparing Jev with specialized 2048 algorithms.

## Selected projects

### [Jev 2048 ↗](https://jev-2048.vercel.app)
**[Source](https://github.com/amansoory/JEV2048) · [Methods and results](https://jev-2048.vercel.app/research) · [How I built it](https://armanhassan.com/projects/jev-2048)**

Play or compare the same Jev classifier with different inputs against expectimax and a pretrained n-tuple bot. Inspect candidate boards, choice probabilities, timing, and specialist agreement.

I built the seeded game controller, anonymous-candidate requests, analytics, and evaluation tools. The native C++ model runs on an **Oracle Cloud ARM64 VM**, with an authenticated Python API, Nginx, TLS, and a persistent worker. The frontend runs on **Vercel**. TDL2048+ and the adapted expectimax sources retain their MIT attribution.

`TypeScript` `Next.js` `React` `TypeSafe SDK` `C++` `Python` `Oracle Cloud` `Vercel` `Playwright`

### [Degree Planner AI ↗](https://unc-degree-rag.vercel.app)
**[Project details](https://armanhassan.com/projects/degree-planner-ai)**

A UNC degree-planning chatbot grounded in official catalog material. I built the catalog-processing and retrieval flow, program routing, and interface with source citations.

`Next.js` `AWS Bedrock` `Claude` `Titan embeddings` `Amazon S3 Vectors` `Vercel`

### [VibeSafe ↗](https://vibe-safe-pt7v.vercel.app)
**[Source](https://github.com/amansoory/VibeSafe) · [Project details](https://armanhassan.com/projects/vibesafe)**

Repository security checks that combine 51 rules across 10 categories, configuration analysis, and Claude review. Findings appear on pull requests; critical issues fail CI.

`Python` `FastAPI` `Claude API` `Docker` `GitHub Actions`

### [Industry Resilience Predictor ↗](https://industry-resilience-predictor.streamlit.app/)
**[Project details](https://armanhassan.com/projects/industry-resilience)**

An interactive regression dashboard comparing COVID-era drawdown and recovery across **90+ industries**. I worked on the time-series data pipeline, model, and dashboard.

`Python` `pandas` `scikit-learn` `Streamlit`

## Experience

| Role | What I worked on |
| :--- | :--- |
| **Machine Learning Intern · Timing** | Contact-prioritization LLM agent, retrieval over interaction history, PostgreSQL/pgvector, indexing, and Redis caching. |
| **Software Engineering Intern · Vogro** | Python automation, FastAPI and Node.js service integrations, and React performance improvements. |
| **Teaching Assistant · Introduction to Programming** | Python labs, debugging support, and office hours for **200+ students**. |

[Experience and dates →](https://armanhassan.com/#experience)

## Tools I use

| Area | Tools |
| :--- | :--- |
| Languages | Python, TypeScript / JavaScript, Java, C / C++, SQL |
| Web & APIs | React, Next.js, FastAPI, Node.js, REST APIs, Tailwind CSS |
| AI & data | TypeSafe Jev, Claude, OpenAI API, RAG, scikit-learn, pandas, pgvector |
| Infrastructure | AWS Bedrock / S3 Vectors, Oracle Cloud, PostgreSQL, Redis, Docker, Nginx, Linux, Vercel |
| Verification | Playwright, focused unit tests, deterministic simulations, saved decision traces |

Also built a Java grid-based game using MVC and the Observer pattern, and a Pygame space battle game that won **1st place at Hack110**.
