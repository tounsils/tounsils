# Ilyes Tounsi

**Full-Stack Software Engineer & AI/ML Integrator.** MCP servers, agent architecture, LLM evaluation.

San Diego, CA · [tounsils.github.io](https://tounsils.github.io/) · [tn76.com](https://www.tn76.com) · [LinkedIn](https://www.linkedin.com/in/mohameditounsi) · tounsils@gmail.com

---

Twenty years shipping production systems end to end: architecture, backend, cloud, frontend, data pipelines. The last three of those layering LLM applications, agent orchestration and evaluation pipelines on top.

What I care about is the part most AI products skip: making the thing provable. Typed tool contracts instead of prompts, answers grounded in real data instead of generated, and an evaluation corpus wired as a release gate so a failure blocks the ship rather than starting a discussion.

## ask-me-mcp

A public reference implementation of that pattern, and the fastest way to see how I build.

**[github.com/tounsils/ask-me-mcp](https://github.com/tounsils/ask-me-mcp)** · MIT · listed in the [official MCP Registry](https://registry.modelcontextprotocol.io/) as `io.github.tounsils/ask-me-mcp`

Six typed tools, JSON-schema strict. External grounding, so the model never invents. Confidence and sources on every response. A 15-case evaluation corpus that gates releases. OAuth 2.1 with anonymous dynamic client registration and PKCE. Two transports: stdio for local, Streamable HTTP for the deployed endpoint.

It answers questions about my work, patterns and availability. Install it and interrogate it rather than taking my word for anything:

```
https://ask-me-mcp-xi.vercel.app/api/mcp
```

## Currently

- **Senior engineering at NXT Robotics.** Operator console and agent layer turning device telemetry into decisions for physical-security and field-equipment fleets.
- **VP of Engineering (advisory) at AIMIA.** Multi-agent assessment platform: specialist agents plus a supervisor synthesizer, real-time voice, multilingual output, encrypted PII with blind-index lookup.
- **Founder of [digitalqrcard.com](https://www.digitalqrcard.com).** Node, Express, MongoDB, Vite + React.
- **[tn76.com](https://www.tn76.com)**, my consulting entity, and where the self-serve work lives: an SEO product for home-service businesses, a catalog of small web apps, and fixed-fee measurement engagements.
- Taking a small number of **fractional CTO and fixed-scope engagements** alongside those → [scope and terms](https://tounsils.github.io/fractional/)

## Stack

**Languages.** TypeScript, Python, Go, JavaScript, PHP, Bash
**AI / LLM.** MCP servers, multi-agent orchestration, RAG, evaluation corpora and certification gates, real-time voice, AWS Bedrock, Vertex AI
**Frontend.** React, Next.js, Vite, TanStack, Tailwind
**Backend.** Node.js, Express, Go, Laravel, FastAPI, REST
**Cloud / DevOps.** AWS (Lambda, ECS, Aurora, Cognito, SAM), GCP Cloud Run, Vercel, Docker, CI/CD
**Data.** MongoDB, PostgreSQL, MySQL, SQLite
**Testing.** pytest, Jest, deterministic harnesses, eval runners

## Selected work

| Project | What it is | Stack |
|---|---|---|
| [`claude-code-skills`](https://github.com/tounsils/claude-code-skills) | Ten engineering skills for Claude Code, Cursor and Copilot: diff review, restructuring, PRs, test gaps, debugging, security, CI triage | Markdown, Node |
| [`ask-me-mcp`](https://github.com/tounsils/ask-me-mcp) | Reference MCP server: typed tools, grounding, eval-gated releases, OAuth 2.1 | TypeScript, MCP SDK, Zod, Vercel |
| [`i-CRM`](https://github.com/tounsils/i-CRM) | Self-hostable CRM: leads, proposals, estimates, invoices, payments, PDF documents. One static binary and one SQLite file, no runtime to install | Go, SQLite |
| [`timecards`](https://github.com/tounsils/timecards) | Local-first desktop time tracker for concurrent projects | Python, Windows binaries |
| [`technical-assessment-deploy`](https://github.com/tounsils/technical-assessment-deploy) | Deployable hiring-assessment platform | TypeScript, Next.js |
| [`tn76-radiotv`](https://github.com/tounsils/tn76-radiotv) | Streaming media web app | TypeScript, React |

## Reach me

**tounsils@gmail.com** · [LinkedIn](https://www.linkedin.com/in/mohameditounsi) · [résumé](https://tounsils.github.io/resume.html)
