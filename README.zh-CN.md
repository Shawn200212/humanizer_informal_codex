[English](README.md) | [简体中文](README.zh-CN.md)

<a id="humanizer-informal"></a>

# Humanizer Informal

用于中英文网站文案、项目介绍、新闻播报和日常内容阐释。
目标是让读者看懂重点，让语气和节奏跟随内容轻重，而不是把文字写成标语、广告或一串碎短句。

完整 skill 在私有
[humanizer_informal_codex-core](https://github.com/Shawn200212/humanizer_informal_codex-core)。
界面显示 `humanizer_informal`，实际入口为 `$humanizer-informal`。

<a id="scope--适用范围"></a>
<a id="scope"></a>
<a id="适用范围"></a>

## 适用范围

它负责信息组织和文字润色，不负责前端实现或自动发布。
网站可以有个人态度，解释可以亲切，新闻必须保留消息来源和不确定性，维护通知则可以平静直接。
有起伏不等于夸大事实。

学术论文请使用 [Humanizer Formal](https://github.com/Shawn200212/humanizer_formal_codex)。

<a id="public-record--公开记录"></a>
<a id="public-record"></a>
<a id="公开记录"></a>

## 公开记录

公开仓库只提供说明和有限评估摘要，不包含内部规则、脚本、测试原文或用户文稿。
验证范围见 [初版评估说明](reports/2026-09-13-revision.md)。
本版没有训练语言模型或分类器；小规模测试也不能证明所有场景都适用，或永远不会过拟合。
本仓也不公开论文语料。
小规模合成测试不能证明普遍的读者偏好或所有双语场景的准确性。
表层检查器不评估语义或表达是否清楚。

<a id="licensing--许可"></a>
<a id="licensing"></a>
<a id="许可"></a>

## 许可

仓库说明文字和私有 Skill 源码保留全部权利，见 [LICENSE](LICENSE)。`data/` 中的聚合测量结果适用 [LICENSE-DATA](LICENSE-DATA) 的单独许可。
