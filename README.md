# 品牌第一课 · Claude Skill 系统

> 一套基于实战品牌方法论的 Claude Skill 系统，帮助品牌顾问和创始人：筛选合作客户、分析品牌案例、在合作过程中提供结构化支持。

---

## 一键安装

将以下命令复制到 Claude Code 终端，即可直接安装全套 Skill：

```bash
claude mcp add https://github.com/bruiandy/brand-first-course-skills
```

或者手动克隆后本地安装：

```bash
git clone https://github.com/bruiandy/brand-first-course-skills.git
cd brand-first-course-skills
claude skill install ./skills/brand-method-hub
claude skill install ./skills/brand-course-01-rhythm
claude skill install ./skills/brand-course-02-resource-scan
claude skill install ./skills/brand-course-03-operating-think
claude skill install ./skills/brand-course-04-brand-ultimate-question
claude skill install ./skills/brand-course-05-brand-narrative-system
claude skill install ./skills/brand-course-06-product-value-shaping
claude skill install ./skills/brand-course-07-channel-product-loop
claude skill install ./skills/brand-course-08-minimum-marketing-loop
claude skill install ./skills/brand-foundation-diagnosis
claude skill install ./skills/brand-case-lens
```

---

## 系统结构

这套系统共 **11 个 Skill**，分三层架构：

```
品牌方法总控（brand-method-hub）
├── 课程层（8 节）
│   ├── 01 · 开篇节奏感
│   ├── 02 · 盘资源
│   ├── 03 · 经营思维
│   ├── 04 · 品牌终极之问
│   ├── 05 · 品牌叙事体系
│   ├── 06 · 产品价值塑造
│   ├── 07 · 产品×渠道闭环
│   └── 08 · 最小营销闭环
└── 支撑层（2 个工具）
    ├── 品牌基础诊断（brand-foundation-diagnosis）
    └── 案例拆解镜头（brand-case-lens）
```

---

## 各 Skill 说明

### 总路由

| Skill | 功能 |
|-------|------|
| `brand-method-hub` | 用户带着任何品牌问题进来时，先接住、判断意图，再路由到对应章节 |

### 课程层

| Skill | 节次 | 核心方法论 |
|-------|------|-----------|
| `brand-course-01-rhythm` | 开篇 | 认知→战略→运营→业务，四步节奏感 |
| `brand-course-02-resource-scan` | 第一节 | 盘资源三维度 + 真优势三问 |
| `brand-course-03-operating-think` | 第二节 | 品类×渠道×团队×毛利，五元素经营框架 |
| `brand-course-04-brand-ultimate-question` | 第三节 | 愿景使命价值观（VMV）实战化追问 |
| `brand-course-05-brand-narrative-system` | 第四节 | 定位→命名→Slogan→视觉→触点，五层叙事体系 |
| `brand-course-06-product-value-shaping` | 第五节 | JTBD + 产品价值 = 动人叙事 × 超预期体验 |
| `brand-course-07-channel-product-loop` | 第六节 | 反向渠道逻辑，四层产品×渠道匹配判断 |
| `brand-course-08-minimum-marketing-loop` | 第七节 | 单渠道+单人群+单卖点，最小可盈利闭环 |

### 支撑层

| Skill | 功能 |
|-------|------|
| `brand-foundation-diagnosis` | 互动式品牌诊断：真实案例 / 问卷筛选 / 合作支持，三种对话模式 |
| `brand-case-lens` | 案例拆解：资源 / 经营 / 品牌 / JTBD / 闭环，五种分析镜头 |

---

## 使用方式

### 场景一：筛选合作客户

触发 `brand-foundation-diagnosis`，进入问卷筛选模式。

Claude 会通过 5-6 个核心问题，判断潜在客户的阶段、资源禀赋、合作匹配度，并给出是否适合深入合作的初步信号。

### 场景二：分析品牌案例

触发 `brand-case-lens`，选择 1-2 个最相关的拆解镜头。

不强制全套分析，避免把方法论硬套在所有问题上。每次先问"这个案例最值得用哪个视角看"。

### 场景三：合作过程支持

触发对应章节的课程 Skill，结合客户的真实情况，给出阶段性方向建议、备忘录或下一步行动清单。

---

## 核心设计原则

1. **先听懂再问，先问清再分析** — 不急着给方案，先把问题搞清楚
2. **一次只问一个问题** — 避免问卷式轰炸，保持对话节奏
3. **区分已知事实 / 判断推测 / 仍需确认** — 不把推断当事实
4. **不做什么和做什么同样重要** — 每次输出都包含"暂时不要做"的建议
5. **章节间有明确路由** — 每节课结束后，明确指向下一个最该看的节点

---

## 适用人群

- 品牌顾问：用于客户筛选和合作支持
- 品牌创始人：用于自我诊断和阶段判断
- 品牌团队：用于方法论对齐和案例复盘

---

## 关于这套课程

《品牌第一课》是一套面向中国消费品创始人的实战品牌方法论，涵盖从资源盘点到最小营销闭环的完整路径。

核心方法论脊梁：**盘资源 → 看经营 → 聚焦优势 → 建品牌产品 → 跑营销闭环**

---

*由 Claude Cowork 协助整理和封装*
