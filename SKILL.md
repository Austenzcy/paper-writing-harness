---
name: paper-writing-harness
description: 为经济学及其他社会科学论文进行选题论证、资料驱动撰写、学术润色、统计表述审查、论文格式与参考文献整理及投稿前检查。用于正式学术论文任务；不用于普通文案润色，也不替代数据分析、重新估计或投稿授权。
---

# Paper Writing Harness

以研究问题与经济学解释组织写作，采用最小必要修改。适用于其他社会科学时，用该学科的解释框架，勿强行套用经济学术语。

## 工作方式

根据请求选择模式；仅在范围确实不明时询问：
- **撰写**：从研究资料形成选题论证或论文内容；缺失证据保留待补项，不写成已完成的研究。
- **润色**：调整逻辑、语言与结构，保留作者真实论点和准确清晰的原文。
- **审查**：只输出有位置、依据、影响和建议的问题清单，不修改被审文件。建议替换句须标为建议。

每次先读 [scientific-integrity.md](references/scientific-integrity.md)。它是本 Skill 内部最高优先级约束；格式和语言偏好不得改变事实。识别输入版本、任务范围、研究问题、目标期刊和已有证据。已有上下文能确定的事项不重复询问。

按需阅读，不默认加载全部资料：
- 选题、正文、摘要、结论、润色：[writing-principles.md](references/writing-principles.md)。
- Word、公式、图表、版式：[formatting-standards.md](references/formatting-standards.md)。
- 引文核对、书目、期刊体例：[citation-standards.md](references/citation-standards.md)；中文默认及《经济研究》配置见 [journal-profiles.md](references/journal-profiles.md)。
- 投稿前审查：[review-checklist.md](references/review-checklist.md)。

文件编辑保留原稿，另存明确版本；核对变化涉及的数值、权重、证据强度、图表和引文。只润色一段时无需审查整篇论文。交付简述实际修改、核验结果和未决项，区分未发现问题与已证实正确。用户未要求生成文件时可直接在对话中交付。

## 维护

更新写作原则时修改对应 reference；新增期刊时按 journal-profiles 的字段新增配置并补充路由。保留来源、核验日期和未核验项；期刊投稿前重新核验现行要求。使用 skill-creator 的 quick_validate.py 检查结构，并在隔离临时目录重跑与变更相关的典型案例。不把一次论文的特殊规则扩大为所有论文的通则。本 Skill 不授权公开论文资料、推送仓库或实际投稿。
