# 模仿文风写作

A reusable agent skill: given samples of a writer's Chinese prose, draft a new piece in that style—learn the craft, not the ideas.

给出某位作者的文章样本，按其文风写一篇新内容的文章，只学写法、不借内容观点。

技能文件：[skills/style-imitation/SKILL.md](skills/style-imitation/SKILL.md)

## 基本原则

- 只学习文风和写作方法，不参考样本的内容和观点；论点、材料、例子都要自己来。
- 不照抄整句、标志性段落或独特比喻；可以学句式骨架，但要换成自己的词。
- 模仿的是“像他会怎么写”，不是“把他写过的再说一遍”。

## 步骤

1. **收集样本**：尽量拿到 2 篇以上、同一体裁的样本，并问清题目、体裁、字数和用途。
2. **拆解文风**：从句式、用词、语气、修辞、结构、引用和排版写成清单，先给用户看。
3. **搭思考框架**：按“发现现象 → 定调 → 论述 → 用自己的框架解释”组织全文（样本结构更鲜明时以样本为准）。
4. **写初稿**：对照清单落实文风特征，内容和观点全部是新的。
5. **对照修改**：并排检查“不像”之处和雷同句，删掉样本里没有的 AI 套话。
6. **交付**：先给成稿，再附 3–5 个模仿要点，并按用户反馈再改一轮。

## 怎么用

把 [skills/style-imitation/SKILL.md](skills/style-imitation/SKILL.md) 复制到 Cursor 或其他支持 SKILL.md 技能的助手的 skills 目录里；也可以把文件内容粘贴进对话，当作写作指令使用。
