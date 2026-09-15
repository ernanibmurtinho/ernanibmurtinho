<div align="center">

# 👋 Hey, I'm Ernani

### Making any API agent-usable — first-call-correct, no integration code

[Gecko](https://geckovision.tech) • [gecko-surf](https://github.com/GeckoVision/gecko-surf) • [X](https://x.com/ernanibritto) • [LinkedIn](https://www.linkedin.com/in/ernanibritto/?locale=en_US)

</div>

---

## 🚀 What I'm building

**[Gecko](https://geckovision.tech)** — the **API comprehension layer for agents**. Point an agent at any API — even one behind human-shaped docs and a paywall — and it finds the right call, makes it correctly the first time, and runs. No client to write, no guessing whether the agent is calling it right.

> *Docs and endpoints are built for humans. Gecko translates an API's surface into question-shaped, first-call-correct agent tools — and handles the auth handshake the docs don't explain.*

The engine — **[`gecko-surf`](https://github.com/GeckoVision/gecko-surf)** (open-source, on PyPI) — turns any OpenAPI into first-call-correct MCP tools:

```bash
curl -fsSL https://get.geckovision.tech | bash
gecko <openapi-url>          # → comprehension summary + a one-click "add to Claude/Cursor"
```

---

## 🎓 And teaching it

I'm running **Dev3Pack AI Engineering** right now — a three-week cohort, fifteen
live sessions, a self-paced Python fast lane and a capstone, 14 Sep to 2 Oct 2026.

It is graded the same way I argue about the day job: **every scored exercise runs
offline** against a deterministic fake model, so no key, no network and no bill
stands between anybody and finishing. A submission is a claim **plus the notebook
that produced it** — the tool refuses to hand in a notebook nothing was run in.

Building a course in public is the cheapest honesty test I know: every claim gets
run by thirty people on thirty different machines, the same week you make it.

*Enrolment is closed for this cohort. Ask me about the next one.*

## 💡 Why this matters

A coding agent can one-shot a popular API. It can't one-shot the **Nth *painful* one** — long-tail, messy, poorly-documented, often paywalled. It picks the wrong endpoint, misplaces the credential, sends a UI amount where atomic units are required, forgets the idempotency key. Each miss is a failed call, a retry, a burned credit. Gecko replaces guess-and-retry with first-call-correct comprehension — and stays correct as the API drifts.

---

## 🧠 What I ship

**`gecko-surf` — the comprehension engine.** Ingest an OpenAPI surface → question-shaped, first-call-correct agent tools (auth hidden, units / placement / idempotency resolved), served over MCP. A `$0` **recorded mode** simulates the call offline before a cent moves.

**[`ayuda-venezuela-bot`](https://github.com/ernanibmurtinho/ayuda-venezuela-bot)** — a Spanish-first Telegram bot giving Venezuelans clear emergency information, an agent over the SOS Venezuela API. Comprehension pointed at something that isn't a demo.

**The three verbs.** APIs get **PAID** (rails), skills get **DISTRIBUTED** (marketplaces), **APIs get USED** (Gecko — comprehension). We compose on x402 / MCP / pay.sh — not a payment rail, not a marketplace.

---

## 🛠️ Tech

```python
stack = {
    "engine":    ["Python 3.11+", "uv", "MCP (Streamable-HTTP)", "stdlib-first", "ruff", "mypy"],
    "chain":     ["Solana", "Anchor", "Pinocchio", "IDL comprehension", "surfpool forks"],
    "delivery":  ["PyPI: gecko-surf", "one-click MCP for Claude / Cursor / VS Code", "Vercel", "AWS ECS"],
    "teaching":  ["Jupyter", "deterministic offline grading", "GitHub Actions as the gradebook"],
    "model":     ["open-core — open engine, private correctness corpus"],
    "compose":   ["x402", "pay.sh", "OpenAPI 3.x"],
}
```

**How I work:** every wire integration ships a free offline simulation first, so it can be falsified without spending anything. Live smoke is the last check, never the debugger. A number that wasn't measured doesn't go in the README.

---

## 🎯 Current focus

- [ ] **Dev3Pack cohort through 2 Oct** — fifteen sessions, a week at a time
- [ ] First 10 outside-network teams running `gecko-surf` on their Nth painful API weekly
- [ ] The **correctness corpus** — every call teaches how to call API X right
- [ ] Surfpool / Solana-AI-Kit — comprehend the chain's tools *and* the APIs around them

---

## 🌱 Open source

Patches I sent to projects other people built and maintain:

- **Orquestra**, by [@berkayoztunc](https://github.com/berkayoztunc) — his project, IDLs into APIs and MCP servers. I sent two fixes: [one so the signer refuses bytes that are not the ones that were checked](https://github.com/berkayoztunc/orquestra-signer-mcp/pull/1) (verification is worth nothing if what gets signed can differ from what was verified), and [one so a transaction reports its own compute units rather than an inner CPI's](https://github.com/berkayoztunc/orquestra/pull/9).
- **DeerFlow**, by [ByteDance](https://github.com/bytedance/deer-flow) (76k★) — I contributed [the Portuguese (pt-BR) README](https://github.com/bytedance/deer-flow/pull/127), so Brazilian devs can pick it up in their own language.

Mine, and open:

- **[gecko-ai-coach](https://github.com/Gecko-Academy/gecko-ai-coach)** — a grounded course coach that ships with its own hit rate, and a contribution bar: a pull request has to carry its before-and-after number.

---

## 🤝 Looking for

| Who | Why |
|-----|-----|
| **Teams shipping multi-API agents** | Bring your messiest, most painful API — let's make it first-call-correct |
| **Agent-tooling builders** | Compose Gecko's comprehension into your kit |
| **API providers with human-shaped docs** | See your surface become agent-usable, unilaterally |
| **Engineers who want the next cohort** | Dev3Pack runs again after 2 Oct — say hello before it opens |

---

## 💬 Let's talk

Building agents that have to call real, painful APIs? That's the whole job.

**DM me on [X](https://x.com/ernanibritto)** or **[LinkedIn](https://www.linkedin.com/in/ernanibritto/?locale=en_US)**

<div align="center">

---

*"The spec is free. The correct first call is not."*

</div>
