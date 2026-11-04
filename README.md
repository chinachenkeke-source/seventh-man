# The Seventh Man

**v0.1.0** · MIT · works with any agent that supports `SKILL.md`

English | [中文](README.zh-CN.md)

> An idea's biggest enemy isn't the people who disagree with it. It's that **nobody ever disagreed with it properly.**

**The Seventh Man** is an [Agent Skill](https://github.com/agentskills/agentskills) that puts your idea through a stress test. It convenes seven people:

- **Six experts** examine feasibility from six angles — demand, market, engineering, finance, risk, and organization
- **The seventh** does nothing but try to **destroy it**: lethal flaws, false premises, failed precedents, the most likely way it dies

There is only one rule: **survive the seventh man.**

## The seven seats

| Seat | Role | Asks exactly one question |
|---|---|---|
| ① | Demand Detective | Does anyone actually hurt, and how do they cope today? |
| ② | Market Veteran | Why would *you* be the one who wins? |
| ③ | Engineering Lead | Can it be built at all? |
| ④ | CFO | Does the math close? |
| ⑤ | Risk Counsel | What could blow up? |
| ⑥ | Org Coach | Who does the work — and can they sustain it? |
| **⑦** | **The Falsifier** | **Why won't this die?** |

## What you get

```
# The Seventh Man · Idea Stress Test

## The idea (one sentence)
## Key assumptions
## Six analyses (six sections, 3-5 points each)
## ⑦ The Falsifier
   Steelman / Lethal flaw / False premise / Precedent /
   Counter-evidence / Most likely death / The overrated part
## Verdict
   Lethal flaws · Most likely death · Proceed or not · Minimum viable test
```

Every run ends with a **minimum viable test**: the cheapest, fastest experiment that could disprove the core assumption. Not "do more research" — specific enough to state who does what, for how long, which metric to watch, and what outcome counts as failure.

## Install

One line:

```bash
git clone https://github.com/chinachenkeke-source/seventh-man.git ~/.dsh/skills/seventh-man
```

No restart needed — the skill appears in your agent's catalog automatically.

**Compatibility:** any agent that reads `SKILL.md`, including Claude Code, GitHub Copilot CLI, Amp, and OpenCode. Drop this repo into the matching skills directory (e.g. `~/.claude/skills/seventh-man`).

> **Language:** the skill body is written in Chinese, but the analysis is always delivered in the language you ask in — English question, English report, Spanish question, Spanish report.

## Usage

Ask your agent:

> Run the Seventh Man on this idea: …

Or invoke it directly:

```
/seventh-man I want to quit my job and open a coffee shop
```

**Trigger words:** seventh man, stress test, evaluate this idea, challenge my assumptions, is this viable

## Language support

Ask in any language and the whole report follows — role names, headings, tables, and the verdict switch with you. Verified in six configurations:

| Language | Status |
|---|---|
| English | ✅ verified |
| 中文 | ✅ verified |
| 中英 mixed | ✅ verified |
| Español | ✅ verified |
| 日本語 | ✅ verified |
| 한국어 | ✅ verified |

Headings never leak back into Chinese, and the report is written directly in the target language rather than translated sentence by sentence.

## Examples

Two complete runs, so you can see the actual output:

- [Case 01 · Quitting a stable job at 40 to run community group buying](examples/case-01-community-group-buying.md)
- [Case 02 · A programmer quitting to open a coffee shop](examples/case-02-coffee-shop.md)

Both cases are **fictional**, and both ended with "needs verification" — because the real answer to most ideas isn't "yes" or "no", it's "you're doing the steps in the wrong order".

## Design principles

- **No fence-sitting** — "overall viable, but watch out" is banned
- **Steelman first** — the Falsifier must restate the strongest version of the idea before attacking it
- **Honesty over stance** — if the attack fails, say so: "the seventh man failed to break it"
- **One idea per run** — want to test another one? Start over

## License

MIT © [chenkeke](https://github.com/chinachenkeke-source)
