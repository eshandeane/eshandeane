# Hey, I'm Eshan 

Senior Product Manager · Builder · 14 years in tech · 8 years in product

I spec AI features, write the prompts, run the evals, and ship the code. I own the full cycle from prompt design through evals to deployed feature.

I do the work. Then I build the system that replaces it.

Onboarded 29 distributors manually, identified the bottlenecks, then built the AI-enhanced platform that cut time-to-revenue by 40%.

---

## By the numbers

| Metric | Result |
|---|---|
| Distributors onboarded hands-on | 29 |
| MRR across 34 live accounts | $72.7K/month |
| Distributor retention | 94% |
| Time-to-revenue reduction | 40% (189 → 113 days) |
| New revenue enabled across 4 regional rollouts | $5.32M |
| AI features in production, covered by evals | 5 |
| PM overhead eliminated weekly | 5-7 hrs (8-agent PM OS) |

---

## What I'm building @ Cut+Dry

**Onboarding Platform** — Rebuilt distributor onboarding from a fragmented manual process into a system-driven workflow

- 189 → 113 days to revenue (40% faster)
- Intake cycle: 100 → 8.5 days (11x improvement)
- $72.7K/month MRR · 94% retention across 34 accounts

**5 AI Features in Production**

- RAG-powered workspace Q&A indexed against account specs and meeting transcripts (Ask FDE)
- AI-generated specs across account categories
- Automated Jira ticket generation
- Meeting-to-account workspace matching
- AI-drafted weekly account update summaries — the one feature I built end-to-end: spec, prompt design, orchestration, evals, UI, and deployed code
- Built LLM-as-Judge eval pipeline — caught 53% hallucination rate in the RAG feature before wider rollout
- All outputs include accept/edit/dismiss controls to maintain user authority

**Track — Last-Mile Delivery** (0-to-1)

- Validated demand via Routific integration before building
- Shipped driver app (iOS + Android), monitoring portal, and ETA notifications
- Live across 4 distributors covering 8,000+ restaurant customers

---

## PM AI Agents

### Delivery Pipeline

| Agent | Role |
|---|---|
| **Homer** | Orchestrator — runs on a launchd schedule 3×/day. Scans Jira Roadmap + Design tickets, judges signal across Circleback/Slack/Gmail, then triggers Lisa or Bart. Never transitions tickets — the comment thread is the audit trail. |
| **Lisa** | Autonomous research agent — asks 3 questions, loads your user persona, then runs full research: JTBD framing, workaround analysis, codebase exploration, impact sizing with driver trees, risk assessment, and 3 solution tiers with a recommendation. ~30 min vs. days. |
| **Marge** | PRD drafting agent — drafts the PRD, then pressure-tests it through a 7-perspective review panel (engineering, design, exec, legal, UXR, skeptic, customer voice). Resolves must-fix issues across up to 2 revision cycles before shipping. |
| **Bart** | Agent loop for UI and frontend design — up to 15 iterations of build → review → fix in a dedicated git worktree. Reviews score 5 dimensions (visual, interaction, consistency, accessibility, responsive) against the frontend-design and userinterface-wiki skills, with a browser action required per dimension. Exits when all scores pass. |
| **Ralph** | Autonomous implementation agent. Receives validated context from Lisa, Marge, Bart, and Prince. Implements features end-to-end with user story tracking. |
| **Prince** | Reads acceptance criteria, spins up Docker test DB, runs Playwright browser tests, auto-fixes issues, captures screenshots, generates structured test reports. Zero-touch QA. |

### PM Operating System (8 scheduled agents via macOS launchd)

| Agent | Schedule | Function |
|---|---|---|
| **Gameplan** | Sunday 8pm | Weekly priorities from roadmap signals |
| **Buzz** | Monday 8am | User sentiment synthesis — Slack, Gmail, meetings, support |
| **Checkpoint** | Monday 8:30am | Roadmap status with per-account risk scoring |
| **Briefing** | Monday 9am | Daily morning digest |
| **Lookout** | Monday 10am | Competitor and ecosystem intelligence scan |
| **Warmup** | 30 min before meetings | Pre-meeting context brief from decision log |
| **Recap** | Weekdays 6pm | Post-meeting decisions, actions → Google Tasks and decision log |
| **Spotlight** | Mon/Fri 4pm | Merged PRs with Playwright screenshots as visual changelog to Slack |

---

## How I work

- Do the work manually to understand where and why it breaks
- Build the system that scales it
- Automate the system itself, with PM judgment at the review gate

---

## Stack

**Product:** B2B SaaS · onboarding platforms · AI features · payments · marketplaces · logistics · ERP integrations · 0-to-1 launches

**AI/Technical:** LLM integration · agent workflows · RAG architecture · prompt design · LLM-as-Judge evals · Claude Code · MCP · Langfuse · PostHog

**Code:** `Next.js` `TypeScript` `PostgreSQL` `Prisma` `Trigger.dev` `Langflow`

---

## Teaching

**"Beyond Vibe Coding"** — 4-hour hands-on workshop for CS students at University of Moratuwa (Sri Lanka's #1 ranked CS program)

Core thesis: shift from vibe coding (prompt → accept → move on) to agentic coding — building the framework that makes agents useful and shipping repeatable.

Most students shipped real features by session end.

---

## Contact

📧 eshandeane@gmail.com · [LinkedIn](https://www.linkedin.com/in/eshan-deane/) · [Portfolio](https://eshandeane.com)

Open to AI PM and Senior PM roles in Southeast Asia.
