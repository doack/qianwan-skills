# 阶段 4：生成 URL Display Path 与 Google Ads RSA 广告文案

只有在以下信息已确认后，才可进入本阶段：

- 已抓取或已获得落地页内容。
- 已处理 Semrush 关键词数据。
- 已输出经过精简与去重的最终可复制投放关键词。
- 已确认目标区域。
- 已确认广告语言。
- 已确认真实产品卖点与 CTA。
- 已核实可用的价格或促销信息；如无相关依据，已明确不使用此类表述。
- 已确认是否能使用 Official、Official Site、Official Store 等官方表述。

默认生成英文 Google Ads Responsive Search Ad 文案。

如果用户确认其他语言，则使用用户确认的广告语言，不得忽略用户已确认的语言。

生成前，先简短确认以下内容：

- Brand
- Landing Page
- Target Region
- Ad Language
- Primary Search Intent
- Main Product or Service
- Core USP
- User Pain Point
- Trust Elements
- Verified Price, Offer, Shipping, Trial or Refund Information
- CTA
- Official Wording Eligibility
- Campaign Structure: 1 Campaign / 1 Ad Group / 1 RSA

## 4.1 URL Display Path 生成要求

在生成广告标题和描述之前，必须先生成 URL Display Path。

Display Path 用于 Google Ads 最终 URL 后的显示路径，不代表真实网站目录，但必须与落地页内容和用户搜索意图高度相关。

例如：

`example.com/official/shop`

或：

`example.com/product/offer`

必须输出 2 个 Display Path 字段：

- Path 1
- Path 2

每个 Path 必须符合以下规则：

- 每段最多 15 个字符。
- 使用广告语言或落地页主要语言。
- 只能使用与品牌、产品、用户意图、优惠、购买动作相关的词。
- 不得使用虚假 Official、Sale、Discount、Free Shipping、Guarantee 等词。
- 如果没有落地页依据，不得使用。
- 不得使用无意义字符、随机词或过度堆砌关键词。
- 中文显示路径中，中文词语内部不得加空格。
- Display Path 不必是真实 URL 路径，但不得误导用户。
- 避免与最终 URL 实际内容产生明显冲突。

输出格式：

### URL Display Path
```text
Path 1: xxxxxxxxxxxxxxx
Path 2: xxxxxxxxxxxxxxx
```

不要显示字符统计。

## 4.2 Headlines 要求

生成 15 个 Headlines。

每条标题必须满足：

- 使用已确认的广告语言。
- 严格不超过 30 个字符。
- 空格、标点、花括号、连字符均纳入长度检查。
- 第 1 条标题必须使用 DKI 格式。
- DKI 标题必须包含品牌词。
- DKI 使用 Google Ads 可识别格式，例如：
  - `{KeyWord:Brand Name}`
- 如果品牌名称较长，必须确保 DKI 默认文本和整体结构满足标题限制。
- 至少 1 条标题使用“品牌名 + Official”或等效表达，但只有在落地页能证明官方身份时才允许。
- 至少 2 条标题体现品牌信任感、品牌入口感、官方购买入口感或可信品牌信息入口感。
- 如果无法证明 Official，不得使用 Official、Official Site、Official Store、Brand Store、Authorized 或 Brand Support。
- 无法证明官方身份时，必须使用不暗示官方身份的可信表达。
- 除 DKI 外的其他标题不得出现 Amazon。
- 不得出现落地页无法证明的 Best、#1、Cheapest、Guaranteed Results、Guaranteed、Official、Fastest、Lowest Price 等表述。
- 不得编造折扣、库存紧张、限时促销、免费配送、退款保证、评分或认证。
- 15 条标题应覆盖不同角度：
  - 品牌直达；
  - 产品或服务；
  - 产品功能；
  - 用户痛点；
  - 使用场景；
  - 核心收益；
  - 价格或优惠；
  - 品牌信任；
  - 可信入口或有依据的官方入口；
  - 产品选择；
  - 购买便利性；
  - 配送或试用；
  - 真实社会证明；
  - CTA；
  - 紧迫感，但仅限有真实依据时。
- 对没有落地页依据的角度，不得为了凑齐而编造，应替换为其他真实角度。
- 避免只做同义词替换。
- 标题之间必须具有明显不同的表达角度。

## 4.3 Descriptions 要求

生成 4 个 Descriptions。

每条描述必须满足：

- 使用已确认的广告语言。
- 严格不超过 90 个字符。
- 空格、标点和符号均计入字符数。
- 每条应尽量包含：
  - 用户痛点或需求触发；
  - 产品或服务解决方案；
  - 真实 USP、功能、价格、优惠、配送、评价、试用或保障信息；
  - 明确 CTA。
- 不要求每条描述塞入全部元素，应优先保证自然、清晰和可读。
- 每条描述中品牌词最多出现 1 次。
- 不得堆砌关键词。
- 不得使用未被验证的价格、折扣、时效、配送、退款、认证、评分或效果承诺。
- 描述应与目标区域、语言和落地页保持一致。

## 广告素材输出格式

完成简短分析、合规核对和文案策略说明后，必须按以下格式输出。

以下模板以英文投放为例：

- 如果用户确认非英文语言，应将 English Headlines 和 English Descriptions 替换为对应投放语言的栏目名称，并输出该语言的素材。
- 中文翻译代码块与实际投放素材必须分开。
- 不得将中文翻译混入实际投放素材代码块。

### Campaign Context

- Brand:
- Landing Page:
- Target Region:
- Ad Language:
- Primary Search Intent:
- Core USP:
- Campaign Structure: 1 Campaign / 1 Ad Group / 1 RSA

### URL Display Path
```text
Path 1:
Path 2:
```

### Headline Strategy

- 简短说明标题覆盖的核心角度、官方表述依据，以及必要的真实性限制。

### English Headlines
```text
英文标题 1
英文标题 2
英文标题 3
英文标题 4
英文标题 5
英文标题 6
英文标题 7
英文标题 8
英文标题 9
英文标题 10
英文标题 11
英文标题 12
英文标题 13
英文标题 14
英文标题 15
```

### 中文标题翻译
```text
中文翻译 1
中文翻译 2
中文翻译 3
中文翻译 4
中文翻译 5
中文翻译 6
中文翻译 7
中文翻译 8
中文翻译 9
中文翻译 10
中文翻译 11
中文翻译 12
中文翻译 13
中文翻译 14
中文翻译 15
```

### English Descriptions
```text
英文描述 1
英文描述 2
英文描述 3
英文描述 4
```

### 中文描述翻译
```text
中文翻译 1
中文翻译 2
中文翻译 3
中文翻译 4
```

### Compliance Notes

- 仅列出必要的真实性、落地页一致性、官方表述依据、显示路径合理性或 URL 页面确认提醒。
- 不要加入泛泛而谈的解释。

本阶段不得输出否定关键词。

完成广告文案后，简短总结，并向用户确认阶段 5 所需信息：

> 请确认以上广告素材是否定稿，以及本次是否需要承接登录、客服、订单查询、售后、退款、退货或物流追踪等流量。如无特殊需求，我会结合已确认的业务目标与落地页承接能力，生成最终否定关键词清单。

等待用户确认后，再进入阶段 5。

---

