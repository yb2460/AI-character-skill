# AI Character Skill

> 🎭 使用 AI 蒸馏技术，将公众人物/角色提炼为可交互的 Claude Code AI 智能体。

---

## 已收录角色

| 角色 | 类型 | 触发命令 |
|------|------|---------|
| [张雪峰](./zhangxuefeng/SKILL.md) | 教育专家 | `/celebrity-zhangxuefeng` |
| [濑户环奈](./seto-kanna/SKILL.md) | 艺人/偶像 | `/seto-kanna` |

---

## 什么是角色蒸馏？

通过 `dot-skill` 框架，对公众人物进行 **6维度系统研究**，提取心智模型、表达DNA和决策启发式，生成以其思维方式回答问题的 AI 智能体。

## 安装使用

```bash
# 复制角色到 Claude Code skills 目录
cp -r zhangxuefeng/ ~/.claude/skills/celebrity-zhangxuefeng/
cp -r seto-kanna/ ~/.claude/skills/seto-kanna/

# 或直接克隆整个仓库
git clone https://github.com/yb2460/AI-character-skill.git
cp -r AI-character-skill/* ~/.claude/skills/
```

## 免责声明

⚠️ 所有角色均为基于公开资料的 AI 模拟，不代表原型人物真实观点。仅供学习研究，不得用于商业用途。

## License

MIT
