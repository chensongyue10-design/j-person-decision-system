<div align="center">

# J 人执行教练 · 决策与执行 Skill

### 让 P 人拥有 J 人的执行力

把模糊目标还原成具体动作，找到当前最关键的瓶颈，
让每次对话都导向下一步真实行动。

![Platform](https://img.shields.io/badge/platform-Codex-111827)
![Type](https://img.shields.io/badge/type-Skill-7C3AED)
![Status](https://img.shields.io/badge/status-ready-22C55E)
![License](https://img.shields.io/badge/license-MIT-0D9488)

</div>

---

## 一句话介绍

J 人执行教练，适用于个人业务、职业、副业、内容、学习、健康行为和生活项目。

它不会一上来给你一份漂亮但难以执行的长期计划，而是帮你判断：

> 现在最值得推进什么？
>
> 当前真正卡在哪里？
>
> 下一步做什么才算完成？

## 核心工作流

```text
目标 → 当前阶段 → 关键瓶颈 → 杠杆假设 → 最小动作
  → 完成证据 → 现实反馈 → 调整或放大
```

## 核心特点

- **主线 / 支线**：从一堆想做的事情里找到当前主线；
- **抽象还原**：把“我要做副业”还原成今天的具体动作；
- **逆向工程**：从目标结果倒推需要验证的关键台阶；
- **杠杆思维**：优先处理最限制结果的那个瓶颈；
- **最小行动闭环**：每次只安排一个动作，并明确做到什么算完成；
- **执行回执卡**：下次对话直接接上上一次的行动和反馈。

## 怎么使用

直接对 AI 说：

> 调用 J 人执行教练，我现在想推进……

然后告诉它：

1. 你想做什么；
2. 希望什么时候看到什么结果；
3. 已经做过什么，以及得到了什么反馈。

每轮结束时，你会得到一张执行卡：

```text
【此轮执行卡】

项目：
目标与期限：
当前阶段：
最大未知：
现在只做：
做到这里算完成：
下次只告诉我：
```

建议为每个重要项目单独开一个会话并置顶，持续把执行卡和反馈带回来。

## 一个使用例子

```text
调用 J 人执行教练，我想做小红书虚拟产品，
希望 30 天内拿到第一单。我已经发了 4 篇笔记，
有收藏但没有成交，不知道要不要换品。
```

它会帮助你先判断：当前是方向有问题，还是样本不足、表达不清或转化环节出了问题；然后给出一个能在现实中验证的下一步，而不是直接让你换品或制定一份空泛计划。

## 内测用户反馈

> “口喷一下需要推动的工作，就会捋出来主线副线，还帮我破卡点。”

> “对今天要完成什么任务非常清晰。”

> “用了松月的 J 人 Skill，让我不要轻易换品。”

## 安装与使用

### 方法一：下载 ZIP

1. 点击本仓库的 **Code → Download ZIP**；
2. 解压后，将文件夹重命名为 `j-person-decision-system`；
3. 把整个文件夹放入你的 Skill 目录：

```text
~/.codex/skills/j-person-decision-system
```

Windows 示例：

```text
C:\Users\你的用户名\.codex\skills\j-person-decision-system
```

请确保 `SKILL.md` 位于文件夹的第一层，不要多套一层目录。

### 方法二：克隆仓库

```bash
git clone https://github.com/chensongyue10-design/j-person-decision-system.git ~/.codex/skills/j-person-decision-system
```

安装后，在新的对话中直接说：

> 调用 J 人执行教练，我现在想推进……

## 文件说明

- `SKILL.md`：Skill 主文件；
- `references/evaluation-cases.md`：人工验收用例与评分标准；
- `references/evaluation-prompt-set.json`：结构化评测 Prompt 集；
- `references/methodology.md`：方法论与案例依据。

## 使用边界

本 Skill 用于个人目标的决策和执行推进，不替代医疗诊断、法律意见或投资建议，也不用于操控、伤害或侵犯他人权益。

## 作者

松月

运营增长 / 虚拟产品 / 一人公司实践
