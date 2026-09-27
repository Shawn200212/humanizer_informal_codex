# Humanizer Informal

**English**

Clear, naturally paced Chinese and English everyday writing: website content organization,
project pages, news briefs/broadcast scripts and explanations. Emphasis should make the point
easier to understand, not turn every paragraph into a slogan or sales pitch.

The installable skill and internal evaluations are in the private
[humanizer_informal_codex-core](https://github.com/Shawn200212/humanizer_informal_codex-core) repository.
The UI display name is `humanizer_informal`; the validated invocation is `$humanizer-informal`.

**中文**

用于中英文网站文案、项目介绍、新闻播报和日常内容阐释。
目标是让读者看懂重点，让语气和节奏跟随内容轻重，而不是把文字写成标语、广告或一串碎短句。

完整 skill 在私有
[humanizer_informal_codex-core](https://github.com/Shawn200212/humanizer_informal_codex-core)。
界面显示 `humanizer_informal`，实际入口为 `$humanizer-informal`。

## Scope / 适用范围

**English**

This edition edits wording and information organization. It does not implement a frontend or
publish the result. Website copy can be personal, an explanation warm, a bulletin direct and a
maintenance notice calm. The source's facts, qualifications, quotations and intended meaning
remain important in every register.

Academic-paper copyediting belongs to
[Humanizer Formal](https://github.com/Shawn200212/humanizer_formal_codex).
The two skills do not impose each other's genre conventions.

**中文**

它负责信息组织和文字润色，不负责前端实现或自动发布。
网站可以有个人态度，解释可以亲切，新闻必须保留消息来源和不确定性，维护通知则可以平静直接。
有起伏不等于夸大事实。

学术论文请使用 [Humanizer Formal](https://github.com/Shawn200212/humanizer_formal_codex)。

## Public record / 公开记录

**English**

This repository contains overview documentation and bounded aggregate evaluation results only.
It does not expose skill instructions, helper code, internal cases, private user passages or
paper corpora. See [the initial evaluation summary](reports/2026-09-13-revision.md).

No language model or filler classifier was trained for this edition. Small synthetic tests do
not establish general reader preference, universal bilingual accuracy or an absence of overfitting.
The surface checker is not a semantic or clarity evaluator.

**中文**

公开仓库只提供说明和有限评估摘要，不包含内部规则、脚本、测试原文或用户文稿。
验证范围见 [初版评估说明](reports/2026-09-13-revision.md)。
本版没有训练语言模型或分类器；小规模测试也不能证明所有场景都适用，或永远不会过拟合。


## Licensing / 许可

**English**

Prose and private skill source remain all rights reserved; see [LICENSE](LICENSE).
Aggregate measurements in `data/` are licensed separately under [LICENSE-DATA](LICENSE-DATA).

**中文**

仓库说明文字和私有 Skill 源码保留全部权利，见 [LICENSE](LICENSE)。`data/` 中的聚合测量结果适用 [LICENSE-DATA](LICENSE-DATA) 的单独许可。
