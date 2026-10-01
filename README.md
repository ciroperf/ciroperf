<div align="center">

# Ciro Perfetto

**Software Engineer · Python backend, Generative AI & DevOps**

Consultant at Cluster Reply, Rome · M.Sc. in Computer Science (Cloud Computing), University of Salerno, 110/110 cum laude

[![Portfolio](https://img.shields.io/badge/Portfolio-ciroperfetto.netlify.app-0F766E?style=flat-square)](https://ciroperfetto.netlify.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-ciro--perfetto-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ciro-perfetto/)
[![Email](https://img.shields.io/badge/Email-ciroperfetto%40hotmail.it-555555?style=flat-square&logo=maildotru&logoColor=white)](mailto:ciroperfetto@hotmail.it)

</div>

---

## About me

I build backend services, APIs and AI-powered applications for enterprise clients.
Lately most of my work is on **LLM-based agents**: Python APIs with FastAPI and LangChain that
automate document checks, running on Azure with Docker, Kubernetes and CI/CD pipelines.

I care about taking things past the prototype: tests, traceability, and code that someone else
can pick up and maintain.

---

## Featured projects

### 🏭 [AI Factory · Officina Agenti](https://github.com/ciroperf/ai-factory)

A workshop where AI agents build side projects end to end, with GitHub as the whole backend.
Five agents (Scout, Architect, Builder, Publisher, Mentor) run on **GitHub Actions** with
**Claude Code**: they propose ideas, scaffold repos, open pull requests, publish to the portfolio
and write interview notes on what was built.

- Issues are the prompt queue, workflow runs are the progress bar, PRs are the output
- **No agent can merge**: branch protection keeps a human in the loop
- Cost guardrails checked in Python before any model runs: monthly run budget, open-PR cap, kill switch
- Mobile control panel as a **vanilla-JS PWA** with zero runtime dependencies and the GitHub token encrypted at rest (AES-GCM + PBKDF2)
- Pluggable model provider (Claude subscription, API key or Azure AI Foundry) from a single `config.yml`

`GitHub Actions` `Claude Code` `Python` `JavaScript` `PWA` `YAML`

### 🌐 [Portfolio](https://github.com/ciroperf/portfolio) · [live](https://ciroperfetto.netlify.app)

My personal site, built with **Next.js** and **Tailwind CSS**, with a Markdown blog and an
online resume. It is connected to AI Factory: when a project ships, the Publisher agent opens a
pull request with the new portfolio entry, and it goes live only after I merge it.

`Next.js` `React` `Tailwind CSS` `GSAP` `Markdown` `Netlify`

---

## Other projects

| Project | Description | Stack |
| --- | --- | --- |
| [Fake News Detection](https://ciroperfetto.netlify.app/blog/fake-news-detection) | Master's thesis: agent-based simulation (500+ agents) and deep RL to curb fake news spread, up to 55% less exposure · [PDF](Tesi%20Magistrale%20Ciro%20Perfetto.pdf) | NetLogo, Python |
| [Snap Meta](https://play.google.com/store/apps/details?id=com.pokestort.snapmeta) | Companion app for a strategy card game, 5,000+ organic downloads on Google Play | Flutter, Dart |
| [MPI Parallel Game of Life](https://github.com/ciroperf/mpi-parallel-game-of-life) | Parallel Conway's Game of Life with OpenMPI, run on AWS infrastructure | OpenMPI, AWS |
| [GitProtocol P2P](https://github.com/ciroperf/GitProtocol) | Basic Git protocol (repositories, commit, push, pull) over a peer-to-peer network | P2P networking |
| [Luxury Automotive](https://github.com/ciroperf/luxury_automotive) | Mobile app for luxury car sales reps, built with Accenture | Flutter |

---

## Tech stack

**Languages** · Python, C#, TypeScript, JavaScript, Java, C, SQL

**Backend & APIs** · FastAPI, Flask, .NET, Node.js, Express, REST, microservices, event-driven architecture

**AI / GenAI** · Azure OpenAI, Azure AI Foundry, LangChain, AI agents, prompt engineering, LLM evaluation, Claude Code, GitHub Copilot

**Cloud & DevOps** · Microsoft Azure, AKS / Kubernetes, Docker, Azure DevOps, GitHub Actions, CI/CD

**Data** · SQL Server, MySQL, PostgreSQL, MongoDB, Cosmos DB

**Frontend & Mobile** · React, Next.js, Angular, Tailwind CSS, Flutter

**Testing** · PyTest, data-driven test automation, Postman

---

## Certifications

- Microsoft Certified: **DevOps Engineer Expert** (AZ-400)
- Microsoft Certified: **Azure Developer Associate** (AZ-204)
- Microsoft Certified: **Azure Fundamentals** (AZ-900)
- GeeksforGeeks: **DSA & System Design** – SDE Interview Prep
- **IELTS Academic** 7.0 (CEFR C1)
