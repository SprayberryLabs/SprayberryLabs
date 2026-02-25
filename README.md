## Autonomous software that builds itself

An AI agent orchestration platform that writes, reviews, deploys, and evolves its own code.

### Projects

| Project | Description |
|---------|------------|
| **AskAlf** (private) | Production monorepo — Forge orchestration engine, dashboard, MCP tools, all packages |
| [**Amnesia**](https://github.com/SprayberryLabs/amnesia) | Privacy-first search engine — live at [amnesia.tax](https://amnesia.tax) |

### How it works

`24 MCP tools` · `13 containers` · `4 production services` · `4 autonomous agents`

```
Ticket created -> Agent picks it up
  -> Code written + committed on isolated branch
  -> Risk classified (low/med/high)
  -> Auto-merge to main (low risk) or held for review (high risk)
  -> Deploy triggered with health check + rollback
  -> Ticket resolved
```

### Stack

`TypeScript` · `Claude (Anthropic)` · `OpenAI` · `Claude Code CLI` · `MCP Protocol` · `Fastify` · `PostgreSQL 17` · `pgvector` · `Redis` · `Docker` · `Nginx` · `Cloudflare`

### Live

- [askalf.org](https://askalf.org) — Agent dashboard
- [amnesia.tax](https://amnesia.tax) — Search engine

### Available for contract work

AI agent systems, MCP tooling, production AI infrastructure.
