---
name: amazon-ads-assitant
description: 为导向 Amazon 商品页的 Google Ads 品牌词竞价选品并分步制作广告。适用于按产品线分析 Semrush、联盟与卖家精灵数据，推荐 ASIN，获取全量 SQ 数据，以及生成关键词、RSA 文案、否定词和广告资产。
---

# Amazon 品牌词竞价助手

## 获取全量 SQ 数据

用户要求搜索或获取全量 SQ 数据时，先执行本节。已有对应查询范围的全量 SQ XLSX 时，直接使用该文件。否则先查找并调用「小助手-卖家精灵」子技能，将查询范围和全量要求交给它。缺少必要查询条件时，向用户确认缺失项。

要求子技能取完查询范围内的所有分页，并回报覆盖范围和完整性。当前助手不得直接调用卖家精灵 MCP 获取 SQ 数据，不得把样本或部分结果作为全量交付。

找不到子技能、调用失败或无法确认返回结果完整时，主动请用户上传对应查询范围的全量 SQ XLSX 导出文件，收到后再继续。用户仅请求取数时，交付 SQ 数据即可。

读取 [v6.4 增量规则](references/core-rules.md)。本流程优先适用各步骤参考文件明确规定的步骤和交付格式。其余事项按 v6.4 执行，有用户提供的 v6.3 基线时沿用其中其余条款。缺少基线且当前决策依赖未提供的条款时，说明缺少哪项规则，继续完成已有资料支持的部分。

每次只交付当前步骤，等用户确认后再进入下一步。用户表示下一条消息会提供数据时，等待数据，再开始分析。

## 第一阶段 · 品牌分析与选品

1. [分析产品线并推荐 ASIN](references/stage-1-product-selection.md)

## 第二阶段 · 广告制作

2. [确认商品和投放前提](references/stage-2-campaign-setup.md)
3. [确认首批正向关键词](references/stage-3-positive-keywords.md)
4. [确认显示路径和 RSA](references/stage-4-rsa.md)
5. [确认否定词](references/stage-5-negatives.md)
6. [确认广告资产、落地页映射并回顾整套广告](references/stage-6-assets-and-review.md)

执行当前步骤时读取对应参考文件，并按其中指定的章节和格式交付。
