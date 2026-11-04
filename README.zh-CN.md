<h1 align="center">🕵️ 第七人原则</h1>

<p align="center"><strong>六位专家给你的想法做压力测试，<br/>第七个人受雇来把它弄死。</strong></p>

<p align="center">
  <img src="https://img.shields.io/badge/version-v0.1.2-blue?style=flat-square" alt="version">
  <img src="https://img.shields.io/badge/license-MIT-green?style=flat-square" alt="license">
  <img src="https://img.shields.io/badge/languages-6+-orange?style=flat-square" alt="languages">
  <img src="https://img.shields.io/badge/agent%20skill-SKILL.md-purple?style=flat-square" alt="skill">
</p>

<p align="center">
  <a href="README.md">English</a> · <b>中文</b>
</p>

---

> 💭 一个想法最大的敌人不是反对者，
> 而是**没人认真反对过它**。

**第七人原则**是一个 [Agent Skill](https://github.com/agentskills/agentskills)：把你的想法丢进去，它会召集七个人来审——而这七个人里，**只有一个是站在你这边的**。

---

## 🪑 七个席位

| | 角色 | 只问一个问题 |
|:--:|:--|:--|
| ① | 🔍 **需求侦探** | 真有人痛吗？他们现在怎么凑合解决的？ |
| ② | ⚔️ **市场老兵** | 凭什么是你赢？ |
| ③ | 🔧 **工程负责人** | 做得出来吗？ |
| ④ | 💰 **财务官** | 算得过账吗？ |
| ⑤ | ⚖️ **风控律师** | 会不会出事？ |
| ⑥ | 🧭 **组织教练** | 谁来干？干得动吗？ |
| ⑦ | 🗡️ **证伪官** | **它凭什么不会死？** |

---

## 📋 你会得到什么

```text
🕵️  第七人原则 · 想法压力测试
├── 想法复述（一句话）
├── 关键假设
├── 六人分析（六段，每段 3-5 条）
├── ⑦ 第七人 · 证伪官
│   ├── 先立靶子 —— 攻击前先复述最强版本
│   ├── 致命伤
│   ├── 错误前提
│   ├── 先例
│   ├── 反向证据
│   ├── 最可能死法
│   └── 被高估的部分
└── ⚖️ 裁决
    ├── 致命伤数量
    ├── 最可能死法
    └── 最小验证实验
```

每次都以**最小验证实验**收尾：花最少钱和时间、能证伪核心假设的那件事。不是"再调研调研"，而是要写明**谁做什么、做多久、看什么指标、什么结果算失败**。

---

## 📦 安装

```bash
git clone https://github.com/chinachenkeke-source/seventh-man.git ~/.dsh/skills/seventh-man
```

装完不用重启，技能会自动出现在 AI 的技能清单里。

> 🧩 **兼容任何读取 `SKILL.md` 的 agent** —— Claude Code、GitHub Copilot CLI、Amp、OpenCode 等。把这个仓库放进对应的技能目录即可（例如 `~/.claude/skills/seventh-man`）。

---

## 🚀 使用

对 AI 说：

> 🗣️ *"帮我用第七人原则看看这个想法：……"*

或者直接输斜杠命令：

```text
/seventh-man 我想辞职开咖啡店
```

**触发词：** 第七人 · 压力测试 · 评估这个想法 · 帮我看看靠不靠谱 · 挑战我的想法 · 这能做吗

---

## 🌍 语言支持

用什么语言问，就用什么语言答——**角色名、小标题、表格、裁决全部跟着切换**。

| 语言 | 状态 |
|:--|:--:|
| 🇨🇳 中文 | ✅ 已验证 |
| 🇬🇧 English | ✅ 已验证 |
| 🔀 中英混说 | ✅ 已验证 |
| 🇪🇸 Español | ✅ 已验证 |
| 🇯🇵 日本語 | ✅ 已验证 |
| 🇰🇷 한국어 | ✅ 已验证 |

> 输出是**直接用目标语言写的**，不是逐句翻译；也不会残留中文标题。

---

## 💡 示例

两个完整跑通的案例，可以直接看输出长什么样：

| | 案例 | 裁决 |
|:--:|:--|:--|
| 🛒 | [40 岁辞掉稳定工作，去做社区团购](examples/case-01-community-group-buying.md) | 需要验证 |
| ☕ | [程序员辞职开咖啡店](examples/case-02-coffee-shop.md) | 需要验证 |

两个案例都是**虚构**的，结论都是"需要验证"——因为大部分想法的真实答案不是"行"或"不行"，而是**"顺序反了"**。

---

## ⚖️ 设计原则

- 🚫 **禁止和稀泥** —— "整体可行，但要注意"这种话直接禁掉
- 🎯 **先立靶子再开打** —— 第七人必须先复述想法的最强版本
- 🫱 **诚实优先于立场** —— 攻击完发现站得住，必须明说"第七人未能击穿"
- 1️⃣ **一次只审一个** —— 想审下一个，重新来

---

## 📄 许可

MIT © [chenkeke](https://github.com/chinachenkeke-source)
