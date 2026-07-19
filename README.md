<div align="center">

# Athavan Thambimuthu

**Building [lanvar.ai](https://lanvar.ai) — a one-person AI lab in Montréal.**

I ship agent systems that do real work, then write down how they're built.

<a href="https://www.linkedin.com/in/athavan-thambimuthu">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="https://lanvar.ai">
  <img src="https://img.shields.io/badge/lanvar.ai-111111?style=for-the-badge&logo=astro&logoColor=white" alt="lanvar.ai" />
</a>
<a href="mailto:athavanth5@gmail.com">
  <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>

</div>

---

## What I work on

Most of my time goes to **AI agent systems** — the unglamorous parts especially: plan approval gates, parallel execution, mid-run clarification, evals, and the state management that keeps a long-running agent honest. The rule I keep coming back to is that deterministic code should do everything checkable, and the model should only spend tokens on judgment.

The rest is full-stack product work — TypeScript on the front, Python on the back — usually in service of getting one of those agent systems in front of a real user.

## Selected work

| Project | What makes it interesting |
| --- | --- |
| **[Scenery](https://github.com/Arty2001/scenery-gemini3-hackathon)** · [live demo](https://scenery-gemini3.fly.dev) | Point it at a React repo and it generates narrated product demo videos from your actual components. A refinement agent scores every scene 0–100 and re-patches anything under 90 until it passes. Built for the Gemini 3 Hackathon. |
| **[Agentic SaaS Starter](https://github.com/Arty2001/agentic-saas-starter)** | Turns a SaaS you already have into an agent platform — a LangGraph + FastAPI layer with plan approvals, parallel execution, mid-run clarifications, evals, and a dev console. |
| **[Echo](https://github.com/Arty2001/echopdfreact)** | An accessibility-first PDF reader that rebuilds pdf.js text layers word by word, so it can read aloud with karaoke highlighting that survives voices dropping or repeating words. |
| **[Arty's Claude Newsletter](https://github.com/Arty2001/artys-claude-newsletter)** | A newsletter that writes itself. The real experiment is repo layout as prompt architecture — taste, rubric, feedback, and template each live in their own file so the boundaries do the thinking. |
| **[Net-Worth Projector](https://github.com/Arty2001/CONUHACKS_2024)** | ConUHacks 2024, SunLife challenge. A Python engine does real Quebec marginal-bracket math and models inflation outrunning wage growth, so the projection erodes honestly instead of flattering you. |
| **[Microbiome Classifier](https://github.com/Arty2001/PHYLA_CHALLENGE_2)** | Multi-class disease prediction from 1,094 gut-bacteria abundance features, where a 6:1 class imbalance is the actual boss fight. SMOTE-balanced deep classifier benchmarked against classical baselines. |

## Built with other people

| Project | My part |
| --- | --- |
| **[NURO](https://github.com/reheant/NURO)** · [demo video](https://www.youtube.com/watch?v=Xg-xnQyxqBo) | A wearable assistant for dementia patients — reminders, geo-fenced location tracking, and an AI voice that answers "who did I meet today?" from its own recordings. Raspberry Pi and mic on the hardware side; live speaker diarization through an FFMPEG pipeline, a Solace event broker, and vector search behind it. Hackathon winner. I built the caregiver-facing frontend. |
| **[PictoDocReader](https://github.com/mattcab2002/PictoDocReader)** | Ctrl-F, but for images inside a document. Five search strategies benchmarked against each other by time complexity — corner matching, linear, diagonal, random-sample, and a 2D Knuth–Morris–Pratt variant — behind a Dash interface. **Best Hack for Education, McHacks 2022.** I wrote the image-to-pixel-matrix conversion the searches run on, and the match outline rendering. |

## Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)

## Elsewhere

- **[lanvar.ai](https://lanvar.ai)** — the lab, and the full project shelf with writeups
- **[LinkedIn](https://www.linkedin.com/in/athavan-thambimuthu)** — for work conversations
- Eleven hackathons, six wins, including a McGill Engine pitch competition and two PharmaHacks podiums

<div align="center">
<sub>Every repo above has a README that explains the engineering, not just the setup steps.</sub>
</div>
