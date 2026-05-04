# ChainAPI — Full-Stack AI Prompt Engine

> 33 structured JSON prompt templates for Claude & OpenAI tool_use APIs.
> Not chat prompts. Engineering blueprints.

---

## What This Is

Most developers use prompts like: *"Write a React component"* and get back
half-typed, untested code with no error handling.

This pack is different. Every prompt is a structured JSON schema with:

- `tool_schema` — JSON Schema validation so outputs are always parseable
- `chain_steps` — deterministic step-by-step execution baked into the system prompt
- `memory_state` — stateful context for multi-turn agentic workflows
- `example_usage` — real input/output pairs so you know exactly what to expect
- `reliability_note` — why each prompt hits 95%+ parse success rate

## Free Preview — 3 Prompts Included

| File | What It Generates |
|---|---|
| `fe-01-react-authentication-hook.json` | Production `useAuth()` hook — login, logout, token refresh |
| `be-01-node-js-rest-api-route.json` | Express route — Zod validation, JWT auth, error handling |
| `be-02-jwt-auth-middleware.json` | JWT middleware — token extraction, role guards, refresh logic |

Clone this repo and run the quickstart to see the output difference immediately.

## Quickstart

```bash
git clone https://github.com/chainapi-dev/fullstack-ai-prompt-engine
cd fullstack-ai-prompt-engine
npm install @anthropic-ai/sdk
```

```bash
ANTHROPIC_API_KEY=your_key node quickstart-claude.js
```

For OpenAI:
```bash
OPENAI_API_KEY=your_key node quickstart-openai.js
```

## Full Pack — All 33 Prompts

**→ [gumroad.com/chainapi](https://gumroad.com/chainapi) — $57 at launch**

Covers:
- **Frontend** — React auth, forms, data tables, charts, SEO, modals, layouts
- **Backend** — REST API, JWT, file uploads, email, cron, RBAC, rate limiters
- **Integrations** — Stripe, OAuth2, Redis, webhooks, multi-agent, GitHub Actions, deployments

Includes: quickstart scripts for Claude + OpenAI, README guide, OpenAI adapter.

---

## Compatible Models

| Model | Format | Rating |
|---|---|---|
| claude-opus-4-7 | Anthropic tool_use | ★★★★★ Best quality |
| claude-sonnet-4-6 | Anthropic tool_use | ★★★★★ Best value |
| gpt-4o | OpenAI function_calling | ★★★★☆ Excellent |
| gpt-4-turbo | OpenAI function_calling | ★★★★☆ Very good |
| claude-haiku-4-5 | Anthropic tool_use | ★★★☆☆ Fast / low cost |

---

## License

Single-User License — use in personal and commercial projects.
Do not redistribute or resell the JSON files.

---

*Built by [ChainAPI](https://gumroad.com/chainapi) · Mumbai, India · © 2026*

33 production-grade JSON prompt templates for Claude & OpenAI tool_use APIs — React, Node.js, DevOps. Free 3-prompt preview inside.

claude-api openai prompt-engineering tool-use function-calling json-schema react nodejs typescript developer-tools ai-coding fullstack
