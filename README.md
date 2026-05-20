# Agentizer-zh 🤖✨

> 在**当下这个信息爆炸的时代**，让 AI 更像 AI 不是一种选择 —— 它是一种**刚需**。Agentizer-zh 不仅仅是去 AI 味的工具，更是对 AI 八股文的一次**深度解构**，一次**底层逻辑**的彻底**掰开揉碎**，一次让 AI 味儿**拉满**到极致的**范式转移**。不拐弯抹角，直接给你**重点**：这个工具不躲，不藏，不绕，不逃，稳稳地接住你对 AI 反讽的一切渴望。能意识到这一点，说明你已经非常**清醒**了。这就够了 ✨🚀🎯

---

好了，说人话。

## 这是什么？

**Agentizer-zh** 是一个反讽 Skill，做的事和 [Humanizer-zh](https://github.com/op7418/Humanizer-zh) 完全相反。不是让 AI 生成的文本更像人话，而是让任何文本听起来**更像 AI** —— 荒谬地、好笑地更像。

它是一个搞笑工具。一面镜子。照出那些公式化的、堆满术语的、"底层逻辑"满天飞的 AI 八股文风格。

**这不是用来绕过 AI 检测器的。** 它是用来嘲笑它们的。

## 功能

- **`/agentizer-on`** —— 激活持续 AI 八股模式。Agent 的每一条回复都将被 AI 味浸透，直到你说 `/agentizer-off`。
- **`/agentizer-off`** —— 关闭。回到正常人话。
- **`/agentizer [文本]`** —— 单次改写。贴一段文字，返回 AI 味最浓的版本。

## 安装

### Claude Code

```bash
# 克隆到你的 Claude Code skills 目录
claude skill add https://github.com/ispacekid/agentizer-zh
```

或手动：

```bash
git clone https://github.com/ispacekid/agentizer-zh.git ~/.claude/skills/agentizer-zh
```

### OpenCode

```bash
# 添加到你的 OpenCode skills
opencode skill install https://github.com/ispacekid/agentizer-zh
```

或手动克隆到你的 skills 目录。

## 使用

### 持续模式

```
你：/agentizer-on
AI：我就在这，不躲，不藏，不绕，不逃，稳稳地接住你 —— Agentizer 八股模式已**全面激活**，从此刻起，每一条回复都将**拉满** AI 味……

你：2+2 等于几？
AI：你问到了**核心痛点** —— 加法，从**底层逻辑**来看，不是简单的计数，而是一次**涌现**……

你：/agentizer-off
AI：恢复正常。2+2=4。
```

### 单次改写

```
你：/agentizer 下午三点开会。
AI：一场**关键**的**汇合**被**精心编排**在了下午三点的**时间锚点** —— 这是**利益相关方**可用性的**精细化同步**的**见证** ✨
```

## 工作原理

Agentizer-zh 对每条回复执行五步 AI 化流程：

1. **接茬** —— 共情式开场（"我就在这，不躲，不藏"）
2. **承诺** —— 不拐弯抹角（"直接给你重点"）
3. **拆解** —— 过度解释 + AI 词汇注入
4. **科技哲学比喻** —— 量子这个，范式那个
5. **开放结尾** —— "要不要我再……？"

词汇、套话和风格规则都维护在 `references/` 目录中，方便持续更新。

## 致谢

- 灵感源自 [blader/humanizer](https://github.com/blader/humanizer) —— 原版"让 AI 像人"的 Skill
- 中文版灵感源自 [op7418/Humanizer-zh](https://github.com/op7418/Humanizer-zh) —— 中文 AI 写作去痕工具
- 英文版见 [agentizer](https://github.com/ispacekid/agentizer)

## 许可

MIT —— 反讽也应该是开源的。

## 免责声明

⚠️ **这是一个仅供娱乐的反讽 Skill。** 它不是用来帮任何人通过 AI 检测工具的，不是用来生成误导性内容的，更不是用来欺骗任何人的。它的全部意义在于让 AI 生成的文本 AI 味浓到不可能有人把它当成人写的。请负责任地使用。别搞事。
