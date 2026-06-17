---
name: score-forge
description: |
  针对机器批改英语作文系统（iWrite/批改网pigai）的高分写作策略。
  基于语料库距离算法的评分机制，用结构化技巧最大化机器评分。
  Triggers: "iwrite作文", "批改网高分", "英语作文机改", "essay scoring", "CET作文", "英语写作提分"
  不用于：人工批改的学术论文（用 brainstorming）、口语练习、非英语语种写作。
---

# Score-Forge：机器批改英语作文高分锻造

## 核心原理

iWrite/批改网的评分本质 = **你的作文与母语者标准语料库的"距离"**。距离越近，分越高。
- 系统拥有 **192+ 个评分维度**，通过 NLP + 机器学习打分
- 4 大维度：语言（语法+词汇）、内容（切题度+连贯性）、篇章结构、技术规范
- **关键洞察：机器不真正"读懂"内容，它靠表面特征打分**

## 六大提分策略（按性价比排序）

### 1. 字数超量（最容易 + 效果最明显）
- 要求 180 词 → 写 **250-280 词**（超 30%-50%）
- 字数是"流利度"核心指标，字数越多分数基础越高
- 不要凑废话，写有实质的展开

### 2. 结构词轰炸（亲测最有效）
每段开头必须加连接词，即使逻辑上不需要：
```
Firstly / To begin with / Secondly / Moreover / Furthermore
In addition / However / Nevertheless / Last but not least
In conclusion / To sum up / Taking all factors into consideration
```
**技巧：段落间不需要连接词时，加上也不会扣分，但会被识别为"结构好"**

### 3. 关键词高频复现（决定"内容相关性"分数）
- 题目关键词全文出现 **5-8 次**
- 用同义词替换避免纯复制
- 例：题目含 "AI" → 全文出现 10+ 次，配合 "artificial intelligence", "this technology", "such systems"

### 4. 高级词汇替换表

| ❌ 低分词 | ✅ 高分替换 |
|----------|-----------|
| think | maintain / contend / hold the view that |
| important | crucial / indispensable / paramount |
| very good | exceptional / outstanding / remarkable |
| more and more | an increasing number of / a growing proportion of |
| because | on account of / owing to / given that |
| show | demonstrate / illustrate / indicate |
| big | substantial / considerable / immense |
| help | facilitate / contribute to / enable |
| use | utilize / employ / leverage |
| problem | dilemma / predicament / adverse issue |
| many | a multitude of / numerous / a host of |
| so | consequently / accordingly / as a result |

### 5. 系统偏爱的特殊句式

**倒装句（最爱）：**
- `Only by doing so can we...`
- `Not only does it..., but it also...`
- `Under no circumstances should we...`

**虚拟语气：**
- `Were I to..., I would...`
- `Had it not been for..., ...`
- `If I were..., I would...`

**强调句：**
- `It is ... that...`

**非谓语开头：**
- `Faced with this challenge, we should...`
- `Given the rapid development of...`
- `Taking all factors into consideration...`

**定语从句嵌套：**
- `The issue, which has attracted widespread attention from scholars who specialize in..., is...`

### 6. 格式零成本加分
- **标点后必须空格**：`, ` 不是 `,`（这直接影响技术规范分）
- 段落间空一行
- 零拼写错误（1 个拼写错误可能扣 2-3 分）

## 图表/数据描述类作文策略

图表描述是 CET-6 Practical Writing 的常见题型，与议论文策略不同：

### 核心结构
1. **开头段**：总述图表主题 + 整体趋势（1-2 句）
2. **主体段**：按维度归类数据（经济→健康→教育），每段一个维度
3. **总结段**：归纳政策/现象意义 + 展望

### 数据描述动词（绝不重复！每换一个数据就换一个动词）

| 方向 | 可用动词 |
|------|---------|
| 急剧上升 | surged / soared / skyrocketed / climbed dramatically |
| 缓慢上升 | increased steadily / rose gradually / witnessed a moderate growth |
| 急剧下降 | plummeted / plunged / experienced a precipitous decline / dropped sharply |
| 翻倍 | nearly doubled / tripled / increased by approximately X times |
| 达到顶峰 | peaked at / reached a pinnacle of |
| 趋于稳定 | stabilized at / leveled off at / remained relatively constant |
| 对比 | while / whereas / in contrast / correspondingly |

### 关键数据写作技巧
- **必须引用具体数字**：`from 98.4% to 1.7%` 而不是 `decreased significantly`
- **用倍数强调反差**：`an increase of approximately 448 times`
- **数据归类叙述**：不要逐行罗列，按主题分组（经济指标 / 健康指标 / 教育指标）
- **用 which/indicating/demonstrating 从句连接数据与意义**

### 高分句式（图表专用）
- `Table/Figure X presents a comprehensive overview of...`
- `It is clearly illustrated that remarkable progress has been achieved in...`
- `The most striking change lies in..., which...`
- `Correspondingly, ... witnessed a substantial surge...`
- `The data overwhelmingly indicates that...`
- `Not only has... been drastically reduced, but... have also been remarkably elevated.`

## CET-4/6 议论文万能模板

```
第一段（开头）：
Nowadays, [关键词] has become a topic of widespread concern.
It is universally acknowledged that [关键词] plays a crucial role in...
Therefore, how to [题目要求] has sparked heated debate.

第二段（主体1）：
Firstly, the advantages of [关键词] are indisputable.
To begin with, [论点1]. For instance, [例子].
Moreover, [展开]. In addition, [补充].

第三段（主体2）：
However, the disadvantages of [关键词] cannot be overlooked.
Not only does [问题1], but it also raises concerns regarding [问题2].
Given that [原因], the potential for [风险] is considerable.
Furthermore, [补充]. Were adequate safeguards not implemented, [后果].

第四段（总结）：
In conclusion, taking all these factors into consideration,
we can safely draw the conclusion that [重申].
Only by [措施] can we [展望].
It is our collective responsibility that will determine...
```

## 迭代修改策略

iWrite 支持多版本提交，每改一版重新提交，分数持续上升：
- 论文实证：学生从 V1 的 78.5 分改到 V7 的 88.2 分
- 另一案例：150 次修改从 30 分提到 73.5 分
- **策略：提交 → 看系统反馈 → 逐条修改错误 → 重新提交 → 重复**

## 避坑清单

- ❌ 不用中式英语（系统有专门的中式英语识别模块）
- ❌ 不全篇简单句（句子复杂度是评分维度）
- ❌ 不跑题（关键词不在文中 = 内容相关性直接低分）
- ❌ 不重复用同一个词（词汇多样性会被统计）
- ❌ iWrite ≠ 批改网（两个不同系统，评分细节不同但核心逻辑一致）
- ❌ 不要在机器批改上花太多精力——它是技巧而非实力

## 参考资料

- 评分原理和技术细节：`references/scoring-mechanism.md`
- CET-4/6 议论文高分模板：`templates/cet-essay-template.md`
- CET-6 图表/数据描述类模板：`templates/chart-description-template.md`
