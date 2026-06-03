# AI Engineering Blog Series

A deep-dive blog series for backend engineers transitioning into AI — from production agent runtimes to LLM eval harnesses, cost optimization, and multi-agent orchestration.

🌐 **Live site:** https://dhanush-ctrl-ai.github.io/ai-engineering-blog

## The Running Use Case

Your engineering org has a **50,000-page internal wiki**. An AI agent can search it, create Jira tickets, send Slack alerts, and update Confluence — autonomously. It processes 50,000 agent runs per day across 3,000 engineers. Every chapter solves one real failure mode in building that system.

## Chapters

| #  | Title                                                              | Status         |
|----|--------------------------------------------------------------------|----------------|
| 01 | Building a Production AI Agent with Failure Recovery               | ✅ Published    |
| 02 | LLM Eval Harnesses in CI/CD                                        | 🔜 Coming soon |
| 03 | The Hidden Costs of LLM Calls in Production                        | 🔜 Coming soon |
| 04 | Multi-Agent Orchestration: Designing for Fault Tolerance           | 🔜 Coming soon |
| 05 | RAG at Scale: From a Single PDF to 100M Documents                  | 🔜 Coming soon |
| 06 | Observability for AI Systems: Tracing What You Can't See           | 🔜 Coming soon |

## Structure

```
docs/
├── index.html                    ← Landing page (GitHub Pages root)
├── _config.yml                   ← Jekyll config
└── chapters/
    └── chapter-01-building-production-ai-agent-failure-recovery.html
```

## Tech Stack Covered

- 🐍 Python (Celery, Redis, Postgres)
- 🤖 OpenAI / Claude / local LLMs
- 🔗 LangChain / LlamaIndex
- ☸️ Kubernetes + KEDA (event-driven autoscaling)
- 🔭 Langfuse / OpenTelemetry
- 📬 SQS / RabbitMQ (async queues)
- 🔒 Circuit breakers (pybreaker)

## About

Backend engineering depth applied to AI systems. Each chapter includes:
- Day One MVP — simplest working implementation
- Hyper-Growth path — scaling to 100M+ operations
- Trade-offs table — explicit Pros vs Cons
- Production code — not toy examples
- Common Gotchas — what breaks in the real world

By [dhanush-ctrl-ai](https://github.com/dhanush-ctrl-ai) · Bengaluru, India
