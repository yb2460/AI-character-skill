# AI Character Skill · 角色蒸馏工厂

> 🎭 使用 AI 蒸馏技术，将公众人物"炼"成可对话的 Claude Code 智能体 | Distill public figures into conversational AI agents

---

## 关于本项目 · About

你有没有想过——跟张雪峰连麦问高考志愿？和濑户环奈像朋友一样聊天？

**AI Character Skill** 做的就是这件事。通过 `dot-skill` 蒸馏框架，对公众人物的公开言论、决策记录、表达风格进行 **6维度系统研究**，提取其心智模型、决策启发式和语言指纹，生成一个能以角色原型思维方式回答问题的 AI 智能体。

不是简单的语气模仿，不是关键词触发式回复——而是从 **认知架构** 层面复刻一个人如何思考、如何判断、如何说话。7层人格架构，每一层都有证据锚点，每一处矛盾都保留不粉饰。

---

Ever wanted to ask Zhang Xuefeng (China's most famous education consultant) about your college application? Or chat with Seto Kanna like a friend?

**AI Character Skill** makes this possible. Using the `dot-skill` distillation framework, we systematically research public figures across **6 dimensions** — writings, conversations, expression DNA, decisions, external views, and timeline — then extract their mental models, decision heuristics, and linguistic fingerprints into a **7-layer persona architecture**. The result: a Claude Code agent that thinks and speaks like the original.

Not surface-level mimicry. Not keyword-triggered replies. **Cognitive architecture replication**, with evidence-anchored mental models and contradictions preserved rather than whitewashed.

---

## 已收录角色 · Featured Characters

### Claude Code 角色 | Claude Code Skills

| 角色 Character | 类型 Type | 触发命令 Trigger |
|------|------|---------|
| [张雪峰](./zhangxuefeng/SKILL.md) | 教育专家 | `/celebrity-zhangxuefeng` |
| [濑户环奈](./seto-kanna/SKILL.md) | 艺人/偶像 | `/seto-kanna` |
| [Elon Musk](./elon-musk/SKILL.md) | 企业家/创新者 | `/celebrity-elon-musk` |
| [Steve Jobs](./steve-jobs/SKILL.md) | 产品大师 | `/celebrity-steve-jobs` |
| [童锦程](./tong-jincheng/SKILL.md) | 深情祖师爷/人际关系 | `/tong-jincheng` |
| [毛选/新青年](./xinqingnian/SKILL.md) | 毛泽东选集方法论 | `/xinqingnian` |
| [吴亦凡](./kris-wu/SKILL.md) | 公众形象/品牌管理 | `/celebrity-kris-wu` |

### 📱 手机 App 角色 | Mobile App Characters

> 打开即聊: **[yb2460.github.io/AI-character-skill](https://yb2460.github.io/AI-character-skill/)** — 添加到主屏幕即安装

| 角色 | 类型 |
|------|------|
| 💰 Warren Buffett | 价值投资之父 |
| 🧠 Charlie Munger | 多元思维模型大师 |
| 🔮 Cathie Wood | 颠覆式创新投资 |
| 🎯 Druckenmiller | 宏观对冲大师 |
| 🦈 Bill Ackman | 激进投资者 |
| 🔍 Michael Burry | 逆向投资者（大空头） |

> 🏦 投资大师角色基于 **[ai-hedge-fund](./ai-hedge-fund)** 蒸馏 — 原项目 [virattt/ai-hedge-fund](https://github.com/virattt/ai-hedge-fund) (59k⭐)

---

## 角色蒸馏方法 · Distillation Method

```
原材料采集 → 6维度研究 → 人格分析 → 7层角色构建 → Skill 生成
Source Collection → 6-Dim Research → Persona Analysis → 7-Layer Build → Skill Output

7 层架构 · 7-Layer Architecture:
Layer 0: 核心思维规则 Core Thinking Rules
Layer 1: 身份激活 Identity & Activation
Layer 2: 表达 DNA Expression DNA
Layer 3: 心智模型 Mental Models (3-7)
Layer 4: 决策启发式 Decision Heuristics
Layer 5: 反模式与诚实边界 Anti-patterns & Honest Boundaries
Layer 6: 智识谱系 Intellectual Genealogy
Layer 7: Agentic Protocol (自主行动协议)
```

---

## 安装使用 · Installation

```bash
# Clone the repo
git clone https://github.com/yb2460/AI-character-skill.git

# Copy characters to Claude Code skills directory
cp -r AI-character-skill/zhangxuefeng ~/.claude/skills/celebrity-zhangxuefeng/
cp -r AI-character-skill/seto-kanna ~/.claude/skills/seto-kanna/

# Or copy everything at once
cp -r AI-character-skill/* ~/.claude/skills/
```

Then in Claude Code:

```
/celebrity-zhangxuefeng   → Chat with Zhang Xuefeng
/seto-kanna               → Chat with Seto Kanna
```

---

## 免责声明 · Disclaimer

⚠️ 所有角色均为基于公开资料的 AI 模拟，不代表原型人物真实观点。仅供学习研究，不得用于商业用途。

All characters are AI simulations based on publicly available materials. They do not represent the actual views of the individuals portrayed. For educational and research purposes only. Not for commercial use.

---

## 贡献 · Contributing

欢迎贡献新角色！Fork → 用 `dot-skill` 蒸馏 → 提 PR。

Want to add a character? Fork → distill with `dot-skill` → open a PR.

---

## License

MIT
