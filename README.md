<h1 align="center">🕵️ The Seventh Man</h1>

<p align="center"><strong>Six experts stress-test your idea.<br/>A seventh is hired to kill it.</strong></p>

<p align="center">
  <img src="https://img.shields.io/badge/version-v0.1.2-blue?style=flat-square" alt="version">
  <img src="https://img.shields.io/badge/license-MIT-green?style=flat-square" alt="license">
  <img src="https://img.shields.io/badge/languages-6+-orange?style=flat-square" alt="languages">
  <img src="https://img.shields.io/badge/agent%20skill-SKILL.md-purple?style=flat-square" alt="skill">
</p>

<p align="center">
  <b>English</b> · <a href="README.zh-CN.md">中文</a>
</p>

---

> 💭 An idea's biggest enemy isn't the people who disagree with it.
> It's that **nobody ever disagreed with it properly.**

**The Seventh Man** is an [Agent Skill](https://github.com/agentskills/agentskills) that puts an idea through a stress test. It convenes seven people — and only one of them is on your side.

---

## 🪑 The Seven Seats

| | Role | Asks exactly one question |
|:--:|:--|:--|
| ① | 🔍 **Demand Detective** | Does anyone actually hurt — and how do they cope today? |
| ② | ⚔️ **Market Veteran** | Why would *you* be the one who wins? |
| ③ | 🔧 **Engineering Lead** | Can it be built at all? |
| ④ | 💰 **CFO** | Does the math close? |
| ⑤ | ⚖️ **Risk Counsel** | What could blow up? |
| ⑥ | 🧭 **Org Coach** | Who does the work — and can they sustain it? |
| ⑦ | 🗡️ **The Falsifier** | **Why won't this die?** |

---

## 📋 What You Get

```text
🕵️  The Seventh Man · Idea Stress Test
├── The idea (one sentence)
├── Key assumptions
├── Six analyses (six sections, 3-5 points each)
├── ⑦ The Falsifier
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
| 🔀 中英 mixed | ✅ verified |
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
