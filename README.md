<h1 align="center">🕵️ The Seventh Man</h1>

<p align="center"><strong>Six people stand behind you, finding reasons it can work.<br/>One stands opposite, finding reasons it will fail.</strong></p>

<p align="center">
  <img src="https://img.shields.io/badge/version-v0.2.0-blue?style=flat-square" alt="version">
  <img src="https://img.shields.io/badge/license-MIT-green?style=flat-square" alt="license">
  <img src="https://img.shields.io/badge/languages-6+-orange?style=flat-square" alt="languages">
  <img src="https://img.shields.io/badge/agent%20skill-SKILL.md-purple?style=flat-square" alt="skill">
</p>

<p align="center">
  <b>English</b> · <a href="README.zh-CN.md">中文</a>
</p>

---

> 💭 **Agreeing with your idea is easy.**
> Finding someone willing to spend real effort proving you wrong is not.

**The Seventh Man** is an [Agent Skill](https://github.com/agentskills/agentskills) that puts an idea through a stress test. It convenes seven people — **six on your side, one against you**, and the one against you had better bring receipts.

---

## 🕯️ Why the seventh man is precious

In most rooms, six people help you argue *how this can work*.

One person stands opposite and says: *"It won't — and here's why."*

**That person is rare today.** What you usually get is agreement, encouragement, and "sounds great". Nobody wants to be the one who kills the mood.

But **disagreement is the deepest form of taking you seriously.**

The seventh man isn't attacking you. He is running your idea through **dialectics**: assume it dies, then go find the evidence. Only after it has been tested against its opposite have you actually looked at it.

**The cold water is so you can see the hole in front of your feet.** Most losses don't come from making a wrong decision — they come from **nobody warning you that the decision had a hole**.

The method is old — **thesis, antithesis, synthesis**:

> 🟢 Six people say *"it can work"* — the **thesis**
> 🔴 The seventh says *"it will die"* — the **antithesis**
> ⚖️ After they collide, what you hold is the **synthesis**

---

## 🪑 The Seven Seats

| | Role | Side | Asks exactly one question |
|:--:|:--|:--:|:--|
| ① | 🔍 **Demand Detective** | 🟢 for | Who hurts, and how badly? |
| ② | ⚔️ **Market Veteran** | 🟢 for | Why can *you* win? |
| ③ | 🔧 **Engineering Lead** | 🟢 for | How do we build it? |
| ④ | 💰 **CFO** | 🟢 for | How does the math work? |
| ⑤ | ⚖️ **Risk Counsel** | 🟢 for | How do we contain the risk? |
| ⑥ | 🧭 **Org Coach** | 🟢 for | How do we organise the people? |
| ⑦ | 🗡️ **The Falsifier** | 🔴 **against** | **Why won't this die?** |

> The first six are advocates: their job is to find **real evidence that it can work** — not to poke holes. Poking holes belongs to the seventh, who must first restate the strongest version of the idea (no straw men) before attacking. If the attack fails, he must say so: *"the seventh man failed to break it."*

---

## 📋 What You Get

```text
🕵️  The Seventh Man · Idea Stress Test
├── The idea (one sentence)
├── Key assumptions
├── 🟢 Six advocates (six sections, 3-5 points each, evidence required)
├── 🔴 ⑦ The Falsifier
│   ├── Steelman — the strongest version, before the attack
│   ├── Lethal flaw
│   ├── False premise
│   ├── Precedent
│   ├── Counter-evidence
│   ├── Most likely death
│   └── The overrated part
└── ⚖️ Verdict
    ├── Lethal flaws
    ├── Most likely death
    └── Minimum viable test
```

Every run ends with a **minimum viable test** — the cheapest, fastest experiment that could disprove the core assumption. Not *"do more research"*, but specific enough to say **who does what, for how long, which metric to watch, and what outcome counts as failure**.

---

## 📦 Install

```bash
git clone https://github.com/chinachenkeke-source/seventh-man.git ~/.dsh/skills/seventh-man
```

No restart needed — the skill appears in your agent's catalog automatically.

> 🧩 **Works with any agent that reads `SKILL.md`** — Claude Code, GitHub Copilot CLI, Amp, OpenCode, and more. Drop this repo into the matching skills directory (e.g. `~/.claude/skills/seventh-man`).

---

## 🚀 Usage

Ask your agent:

> 🗣️ *"Run the Seventh Man on this idea: …"*

Or invoke it directly:

```text
/seventh-man I want to quit my job and open a coffee shop
```

**Trigger words:** seventh man · stress test · evaluate this idea · challenge my assumptions · is this viable

---

## 🌍 Language Support

Ask in any language and the **whole report follows** — role names, headings, tables and verdict all switch with you.

| Language | Status |
|:--|:--:|
| 🇬🇧 English | ✅ verified |
| 🇨🇳 中文 | ✅ verified |
| 🔀 mixed 中英 | ✅ verified |
| 🇪🇸 Español | ✅ verified |
| 🇯🇵 日本語 | ✅ verified |
| 🇰🇷 한국어 | ✅ verified |

> The report is written **directly in the target language**, not translated sentence by sentence. Headings never leak back into Chinese.

---

## 💡 Examples

Two complete runs, so you can see the actual output:

| | Case | Verdict |
|:--:|:--|:--|
| 🛒 | [Quitting a stable job at 40 to run community group buying](examples/case-01-community-group-buying.md) | needs verification |
| ☕ | [A programmer quitting to open a coffee shop](examples/case-02-coffee-shop.md) | needs verification |

Both cases are **fictional**, and both ended with *"needs verification"* — because the real answer to most ideas isn't "yes" or "no". It's **"you're doing the steps in the wrong order."**

---

## ⚖️ Design Principles

- 🚫 **No fence-sitting** — "overall viable, but watch out" is banned
- 🎯 **Steelman first** — the Falsifier must restate the strongest version before attacking
- 🫱 **Honesty over stance** — if the attack fails, it must say: *"the seventh man failed to break it"*
- 1️⃣ **One idea per run** — want to test another one? Start over

---

## 📄 License

MIT © [chenkeke](https://github.com/chinachenkeke-source)
