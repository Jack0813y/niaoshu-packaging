# niaoshu-packaging

让你的 agent 帮你写项目发布帖。

这是一个 agent skill：把花叔（[@AlchainHust](https://x.com/AlchainHust)）公开帖里包装项目的写法，拆成 12 招，再按同一套结构改写你自己的 app、skill 或开源仓库：发布标题、开源帖、README 第一句、发布前的 PRFAQ。

## 安装

```bash
npx skills add Jack0813y/niaoshu-packaging
```

或者手动放进 skills 目录：

```bash
git clone https://github.com/Jack0813y/niaoshu-packaging ~/.claude/skills/niaoshu-packaging
```

## 用法

把项目丢给 agent，说一句：

> /niaoshu-packaging 帮我给这个仓库写一条开源帖：{仓库链接或一段介绍}

想先学方法：

> /niaoshu-packaging 先讲第一招

## 它会做什么

- **改写模式**：一句话结果 → 发布标题 → 开头两句 → PRFAQ → 正文三段 → 结尾拿走（链接 + 一句用法）。
- **学习模式**：十二招目录，一次讲透一招，配原帖链接和一道改写题。
- **不编数字**：每条主张标成「你给的事实 / 推出的判断 / 还不能说」。你的项目没有星标、播放、用户数，它就写「还不能这么说」。

## 里面有什么

| 文件 | 内容 |
| --- | --- |
| `SKILL.md` | 十二招、学习模式、改写模式和边界 |
| `references/corpus.md` | 29 条公开帖的节选，每条都链回原帖，收集于 2026-11-05 |

## 说明

- 非官方项目，与花叔本人无关联。这是对公开写法的学习笔记，不代表他本人，也不保证帖子会火。
- `references/corpus.md` 里的引文版权归原作者，只做节选和链接，完整内容请看原帖。
- 其余内容使用 MIT 协议。
