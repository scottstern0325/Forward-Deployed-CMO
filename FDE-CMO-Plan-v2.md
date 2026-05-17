# The Forward-Deployed CMO — 90-Day Build Plan (v2)
### Scott Stern · Build-in-Public · BlackLine-Additive

> v2 supersedes v1. The framing question from v1 ("wedge or exit ramp?") is **resolved: it is the wedge.** The plan now optimizes for one outcome — a future-ready CMO with a documented, public business case.

---

## 0. The resolved thesis

You are not deciding whether to do this. You've decided. This plan executes one thesis:

**The market is moving toward executives who can both build the agentic system and scale the teams that run it. You are constructing that profile deliberately, in public, while leading at BlackLine — and packaging it as a business case for your next chapter.**

The capability work and the brand work are the same work. Every artifact is simultaneously a skill learned and a proof point published.

**Assumptions (recalibrate freely):** ~5–7 hrs/week, scalable; Claude Desktop primary; this is additive to BlackLine and never routes through it.

---

## 1. The capability stack (what "done" looks like at Day 90)

| Layer | Status | The 90-day job |
|---|---|---|
| **Domain** — enterprise SaaS marketing depth | ✅ Owned. The moat. | Leverage it — it's why you beat an actual engineer at this. |
| **Build** — MCP, production skills/agents, lightweight code, SQL + marketing data, evals, orchestration | 🟡 Scaffolded | The core work of the next 90 days |
| **Delivery** — embed → scope a first deployable win → build → harden → transfer → measure | 🔴 The FDE craft | Phase 3 + every build |
| **Business case** — the documented argument for Scott as future-ready CMO | 🔴 The endgame | Sharpened every Friday; shipped Day 90 |

**Definition of done (Day 90):**
1. **4–5 deployable marketing artifacts**, each solving a real enterprise workflow, each with a before/after impact line.
2. **A codified delivery method** — your `fde-delivery-playbook` skill.
3. **A public POV thread** establishing you as a voice on agentic marketing operations / the future-ready CMO.
4. **A business case** sharp enough to put in front of leadership.

---

## 2. Environment + MCP connect checklist (free tooling only)

**Core spine — Week 0:** Filesystem MCP (scoped to `~/fde-marketing/`), GitHub MCP (private repo), Memory MCP, Sequential Thinking MCP, SQLite MCP (+ one free marketing dataset), Fetch MCP. Dev base: VS Code, Python+`uv`, Node, Git.

**Attach per phase:** Notion MCP (Wk1), Slack MCP (Wk5), Google Drive/Gmail/Calendar MCP (Wk5), Puppeteer/Playwright MCP (Wk6), Promptfoo (Wk7), n8n (Wk8), Supergrow MCP — already connected (Wk9).

> Exact `claude_desktop_config.json` blocks: ask me to generate per-server with current syntax when you wire each one. Pull canonical commands from `modelcontextprotocol.io` and each server's repo.

---

## 3. The 90-day schedule

Each week: theme · actions · **what ships** · tooling. ~5–7 hrs. Friday = review + sharpen the business case.

### Week 0 — Today (Sun, May 17)
Stand up `~/fde-marketing/` + private GitHub repo. Wire the Core Spine MCPs. Load one free marketing dataset into SQLite. Read & commit `00_CHARTER.md`. **Ships:** working environment + committed charter.

### Phase 1 — Foundations & first builds (Wks 1–4 · May 18 – Jun 14)
- **Wk 1:** SQL fluency + first agentic data read → narrative answer. **Ships:** "Marketing-Data Q&A" v0.
- **Wk 2:** Skill architecture leveled up — refactor one existing skill, document why it's now production-grade. **Ships:** one hardened skill + the seed of your delivery method.
- **Wk 3:** API/code literacy by necessity — wire one marketing API read end-to-end through an agent. **Ships:** API-backed agent.
- **Wk 4:** **Artifact #1** assembled (competitive-intel or analyst-coverage agent) + before/after impact line. **Ships:** Portfolio Artifact #1. → **Day-30 checkpoint.**

### Phase 2 — Deployable patterns + evals (Wks 5–8 · Jun 15 – Jul 12)
- **Wk 5:** The transfer half — rebuild #1 so a non-technical marketer can trigger and trust it; add Slack handoff. **Ships:** #1 v2 + handoff note.
- **Wk 6:** **Artifact #2** — content-ops pipeline (brief→draft→review→repurpose) through your brand/copywriter skills. **Ships:** Artifact #2.
- **Wk 7:** Evals — stand up Promptfoo, write pass/fail bars for #1 and #2. **Ships:** eval suite. *(This is the credential that says builder, not tinkerer.)*
- **Wk 8:** **Artifact #3** — chained multi-step workflow + n8n non-technical trigger layer. **Ships:** Artifact #3. → **Day-60 checkpoint.**

### Phase 3 — Delivery craft + public proof (Wks 9–12 · Jul 13 – Aug 9)
- **Wk 9:** Codify the method → `fde-delivery-playbook` skill. **Ships:** the playbook skill (your most valuable artifact). Open the POV thread via `linkedin-executive` + Supergrow.
- **Wk 10:** **Artifact #4** built explicitly *against your own playbook*; document where it held/broke. **Ships:** Artifact #4 + playbook revision.
- **Wk 11:** Package as proof — 4 artifacts → sanitized case studies; repo README → portfolio; **business case to near-final.**
- **Wk 12:** Go public at volume + finalize the business case. **Ships:** the thread + the business case. → **Day-90 checkpoint.**

---

## 4. The build portfolio

1. Competitive / analyst intelligence agent
2. Content-ops pipeline (rides `b2b-saas-copywriter` + `scott-stern-brand`)
3. Multi-step GTM workflow with a non-technical trigger layer
4. A 4th built against your own playbook (proves the method generalizes)
5. The `fde-delivery-playbook` skill itself

Each = a case study **and** a reusable skill **and** a business-case proof point.

---

## 5. Weekly operating cadence

- **Deep work block (2–3 hrs):** the week's ship. Calendared, non-negotiable.
- **Ship + learn block (1–2 hrs):** only what the build needs. No tutorial spirals.
- **Friday review (15 min):** Did something ship? + sharpen one section of `BUSINESS-CASE.md`. Log it in `log/WEEKLY-LOG.md`.

---

## 6. Kill switches & checkpoints

**Kill switches — change course if any fire:**
- Two consecutive weeks, nothing shipped → tutorial spiral. Halve scope, ship a worse version.
- Day 30, no artifact a real marketer would use → building for engineers. Re-anchor on the domain — it's your only edge over an actual FDE.
- Day 60, can't explain a build to a non-technical peer in 3 min → lost the transfer half. "Deployed" is the point.
- Day 90, the POV thread gets silence → capability is still real and worth having; the *framing* is wrong. Keep the skill, change the label.

**Checkpoints (the question changed — it's no longer "should I do this"):**
- **Day 30:** One deployable artifact exists. *Is the business case starting to write itself from real proof, or am I still asserting it?*
- **Day 60:** Three artifacts + an eval bar. *Is this sharp enough that a peer who saw it would describe me as a future-ready CMO without me prompting them?*
- **Day 90:** Portfolio + playbook + public POV + business case. *Who specifically needs to see this, and what is the ask?*

---

## 7. The question to sit with

You've resolved that this is the wedge. Good. The harder question is downstream:

**When the business case is done and the proof is public — do you have the nerve to actually put it in front of the people who decide your next chapter, or does it quietly become a very impressive folder you never send? Name the three people who need to see this by Day 90. Write their names in `BUSINESS-CASE.md` now, before the proof exists. A business case with no audience is a hobby with good production values.**

Don't answer it now. Answer it in writing, in the business case, by end of Week 1.
