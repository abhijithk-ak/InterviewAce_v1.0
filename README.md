# InterviewAce v1.0 🎯

**AI-Enhanced Mock Interview Platform with Intelligent Multi-Domain Evaluation**

InterviewAce combines algorithmic precision with AI to deliver personalized,
role-specific interview practice across 13+ technical domains — with a hybrid
NLP + ML scoring engine, live analytics, and a research dashboard for
academic use.

![Next.js](https://img.shields.io/badge/Next.js-16.1.6-black)
![TypeScript](https://img.shields.io/badge/TypeScript-5.9-blue)
![MongoDB](https://img.shields.io/badge/MongoDB-7.1-green)
![License](https://img.shields.io/badge/license-MIT-blue)

🔗 **Live demo:** [interviewacev1.vercel.app](https://interviewacev1.vercel.app/)

---

## What it does

- **13+ role-specific interview tracks** — Frontend, Backend, Flutter, Data
  Engineering, ML, QA, DevOps, System Design, Technical Support, and more
- **Hybrid evaluation engine** — deterministic keyword scoring (700+
  domain terms) blended with semantic similarity (MiniLM transformer) for a
  research-grade correctness check, including misconception detection
- **Live interview session** — chat-style UI, optional webcam recording,
  text-to-speech questions, real-time 5-dimension scoring
- **Dashboards** — personal analytics, a Learning Hub with tailored
  resources, and an admin-only IEEE-ready research dashboard for
  statistical analysis across scoring methods
- **GitHub OAuth**, MongoDB-backed sessions/settings, and a question bank
  of 100+ curated questions

## Tech stack

Next.js 16 (App Router) · TypeScript · MongoDB + Mongoose · NextAuth ·
Tailwind CSS · OpenRouter (LLM) · @xenova/transformers (MiniLM embeddings) ·
Recharts

## Quick start

```bash
git clone https://github.com/abhijithk-ak/InterviewAce_v2.0.git
cd InterviewAce_v2.0
pnpm install
cp .env.example .env.local   # add your GitHub OAuth, MongoDB, OpenRouter keys
pnpm dev
```

Open [localhost:3000](http://localhost:3000). See `.env.example` for the full
list of required environment variables (GitHub OAuth app, MongoDB Atlas
connection string, OpenRouter API key).

## Documentation

Deeper technical material lives in [`/docs`](./docs):

- [Evaluation Engine](./docs/EVALUATION_ENGINE.md) — scoring algorithm, keyword libraries, hybrid formula
- [Architecture](./ARCHITECTURE.md) — directory structure and component breakdown
- [Research Dashboard](./RESEARCH_DASHBOARD_V2.1.md) — IEEE-ready analytics, statistical methodology
- [API Reference](./docs/API.md)
- [Deployment Guide](./docs/DEPLOYMENT.md)

Development-history docs (phase logs, migration notes, implementation
summaries) are kept in `/docs/history` for anyone digging into the project's
evolution.

## Roadmap

- [ ] Voice interview mode (speech-to-text)
- [ ] Multi-model ensemble scoring
- [ ] Mobile app
- [ ] Public API for third-party integrations

Full roadmap in [`/docs/ROADMAP.md`](./docs/ROADMAP.md).

## License

MIT — see [LICENSE](./LICENSE).

## Author

[@abhijithk-ak](https://github.com/abhijithk-ak) · [Issues](https://github.com/abhijithk-ak/InterviewAce_v2.0/issues) · [Discussions](https://github.com/abhijithk-ak/InterviewAce_v2.0/discussions)
