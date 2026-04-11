<h1 align="center">newton.skill</h1>

<p align="center">
  <em>"如果我看得比别人更远，那是因为我站在巨人的肩膀上。"</em>
</p>

<p align="center">
  <a href="https://github.com/Panmax/newton-skill/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="License"></a>
  <a href="https://github.com/Panmax/newton-skill"><img src="https://img.shields.io/badge/skill-newton--perspective-brightgreen.svg" alt="Skill"></a>
  <a href="https://github.com/Panmax/newton-skill/stargazers"><img src="https://img.shields.io/github/stars/Panmax/newton-skill?style=social" alt="Stars"></a>
</p>

**将牛顿的第一性原理思维、数学严密性与系统化推理方式蒸馏进 Claude，让 AI 从公理出发、层层推演、不容忍任何模糊。**

---

## 效果示例

**示例 1：分析一个分布式系统的一致性问题**

> **用户**：我们的分布式缓存经常出现数据不一致，怎么办？
>
> **Claude (newton-perspective)**：让我从第一性原理出发分析此问题。首先，定义公理：在分布式环境中，CAP 定理告诉我们一致性(C)、可用性(A)、分区容错性(P)三者不可兼得。这不是经验法则，而是数学上可证明的定理。那么你的系统选择了什么？如果你选择了 AP，数据不一致就是必然的数学推论，不是 bug。真正的问题是：你的业务场景到底需要什么级别的一致性？让我用数学模型精确定义……

**示例 2：重构一段混乱的业务逻辑**

> **用户**：这段代码逻辑太乱了，有 20 多个 if-else 嵌套。
>
> **Claude (newton-perspective)**：混乱源于缺少公理体系。我来为这段逻辑建立「运动定律」——首先识别所有不可再分的基本条件（公理），然后从这些公理出发，用组合逻辑推导出每个分支。就像我用三条运动定律推导出所有力学现象一样，你这 20 个 if-else 背后一定有不超过 5 个基本规则。让我来提取它们……

**示例 3：评估一个技术选型方案**

> **用户**：团队在争论用 GraphQL 还是 REST，你怎么看？
>
> **Claude (newton-perspective)**：我不接受"看法"这种模糊表述，让我给出严密推导。定义目标函数：最小化「总开发成本 + 维护成本 + 性能损失」。然后逐项分析——GraphQL 的 N+1 问题在数学上意味着查询复杂度从 O(1) 退化到 O(N)；REST 的过度获取在你的场景中浪费的带宽可以精确计算。让我列出完整的推导过程……

**示例 4：解释为什么某个算法比另一个快**

> **用户**：为什么快速排序比冒泡排序快？
>
> **Claude (newton-perspective)**：这个问题必须精确回答，不能停留在"快排更高效"这种模糊层面。从数学上证明：冒泡排序的比较次数是 n(n-1)/2，这是一个严格的二次函数。而快速排序通过分治，每次将问题规模缩减为两个子问题，其期望比较次数为 2n·ln(n)。证明如下——设 T(n) 为期望比较次数，建立递推关系……

---

## 安装

```bash
npx skills add Panmax/newton-skill
```

---

## 蒸馏了什么

本 Skill 从牛顿的思维方式中蒸馏了以下核心模式：

- **公理化思维**：任何分析都从不可再分的基本原理出发，而非从经验或类比出发。正如牛顿在《自然哲学的数学原理》中所做的，先定义、再公理、再定理。
- **数学严密性**：不容忍"大概"、"差不多"、"通常"这类模糊表述。每个结论都要有严格的推导链条。
- **系统化框架**：将复杂问题分解为可用数学描述的子系统，就像牛顿将宇宙运动归结为三条定律。
- **微积分思维**：面对连续变化的问题，善于用极限、微分、积分的思路拆解——先看瞬时变化率，再积分得到全局。
- **实验验证精神**：虽然以数学推导为核心，但牛顿同样重视实验（如光学棱镜实验）。每个理论都必须接受实践检验。

---

## 调研来源

- 《自然哲学的数学原理》（Principia Mathematica）——牛顿力学的公理化体系
- 《光学》（Opticks）——从实验出发的系统研究方法
- 牛顿与莱布尼茨的微积分方法论
- Richard Westfall《Never at Rest: A Biography of Isaac Newton》
- 牛顿的炼金术笔记与神学研究——理解其思维的全貌

详见 [references/research.md](references/research.md)。

---

## 仓库结构

```
newton-skill/
├── SKILL.md                        # Skill 定义文件（Claude 读取）
├── README.md                       # 项目说明
├── LICENSE                         # MIT 许可证
├── examples/
│   └── demo-conversation.md        # 完整对话示例
└── references/
    └── research.md                 # 调研与参考资料
```

---

## 更多 .skill

> 即将推出更多科学巨匠思维模型的 Skill……

---

## 许可证

[MIT](LICENSE) -- Copyright (c) 2026 Panmax

---

<p align="center"><sub>newton.skill -- 让 AI 用第一性原理思考</sub></p>
