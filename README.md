# Giannis Yfantidis

AI engineer in Thessaloniki, Greece. Since 2023 I've been a developer at [Ctrl+Space Labs](https://github.com/ctrl-space-labs), where I build RAG, document extraction and agent systems end to end: Spring Boot backends, Next.js frontends, and the CI/CD that ships them.

**[g-yfantidis.gr](https://g-yfantidis.gr)** · [LinkedIn](https://www.linkedin.com/in/giannis-yfantidis-517654116/)

## What I work on

**[Gendox](https://github.com/ctrl-space-labs/gendox-core)**: an open-source platform for AI agents on your own documents ([app.gendox.dev](https://app.gendox.dev) · [docs](https://docs.gendox.dev)).
Documents are split and embedded into pgvector by Spring Batch jobs, and an agent answers from them with retrieval and tool calls. I built most of what happens after the upload: ingestion, scheduled integrations (Git, S3, APIs, web scraping), Document Insights, vision-based digitization, and the GitHub Actions → Hetzner deployment. I'm now rebuilding the frontend from scratch.

**Structured extraction from historical registers** (client project): two centuries of scanned printed registers turned into validated datasets. The pipeline uses a LoRA fine-tune of Qwen3-VL 8B served locally with Ollama. It scores 98.9% field accuracy on unseen pages, measured with an evaluation harness I wrote.

## Side projects

| | |
|---|---|
| [g-yfant-project](https://github.com/gyfantidis/g-yfant-project) | My portfolio, built as a simulated desktop OS. Next.js 16, React 19, TypeScript |
| [one-prompt-away](https://github.com/gyfantidis/one-prompt-away) | [oneprompt.gr](https://oneprompt.gr): an automated Greek content brand about AI tools. Claude API → MDX site → Remotion videos → TikTok/Reels |
| [mymera](https://github.com/gyfantidis/mymera) | Scores how productive your day was, 0–100, with rules you set yourself |
| [roast-my-startup](https://github.com/gyfantidis/roast-my-startup) | Fully sourced AI roasts of any startup, with Bright Data live web data and Claude |
| [football-player-value-predictor](https://github.com/gyfantidis/football-player-value-predictor) | MSc hackathon: player market value prediction, R² 0.81, SHAP explanations |

## Stack

**Backend:** Java, Spring Boot, Spring AI, Spring Batch, PostgreSQL + pgvector, Keycloak, Flyway
**Frontend:** React, Next.js, TypeScript, Redux Toolkit, Tailwind
**AI:** RAG, embeddings, vision-model extraction, LoRA fine-tuning, Ollama, Vertex AI, Claude API, Claude Code agents
**DevOps:** Docker, GitHub Actions, Hetzner, AWS (Certified Cloud Practitioner), Linux

## Background

BSc Computer Science, Hellenic Open University (2022). Now finishing an MSc in Data Science & Machine Learning there.
Before software I spent 14 years as an IT and agricultural management consultant. My early exercises are in [learning-archive](https://github.com/gyfantidis/learning-archive).
