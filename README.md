# 凸优化学习 Skill（Boyd《Convex Optimization》）

> 面向数学基础薄弱学习者的凸优化教学方法论 —— 把抽象数学用大白话 + 生活比喻讲清楚。

## 这是什么？

这是一个基于 **Stephen Boyd & Lieven Vandenberghe《Convex Optimization》** 教材、为 AI 助教（Claude Code Skill）设计的教学指南。它定义了从第 1 章到第 5 章的系统化教学方法（涵盖凸集、凸函数、凸优化问题、对偶理论），让 AI 能够像耐心的家教一样，帮助数学基础薄弱的学习者（大学文科生水平）逐章啃完这本教材。

虽然教学方法论本身（分块策略、比喻库、符号解释规范）可以迁移到其他数学教材，但 **references 中的所有材料都是围绕 Boyd 这本书展开的**，目前只在这本书上做过完整的教学验证。

## 核心理念

**先讲"为什么重要 / 直觉是什么"，再讲"数学怎么写"，绝不反过来。**

每块内容按五步讲解：

```
① 大白话直觉  →  ② 生活比喻  →  ③ 符号解释  →  ④ 数学本身  →  ⑤ 一句话总结
```

## 目录结构

```
├── SKILL.md                        # Skill 主文件（教学流程 + 规范）
├── README.md                       # 本文件
├── LICENSE                         # MIT 许可证
└── references/
    ├── chunking.md                 # 分块策略详细指南
    ├── symbols.md                  # 数学符号速查表
    ├── convex_opt_map.md           # 凸优化全书知识图谱
    └── teaching_examples.md        # 已验证有效的教学案例库
```

## 适用范围

- 正在啃 **Boyd《Convex Optimization》** 这本书，需要家教式讲解
- 数学基础薄弱（大学文科生水平），看不懂教材的符号和推导
- 需要大白话直觉 + 生活比喻 + 不跳步骤的逐步推导

## 已覆盖的教材内容

基于 Boyd《Convex Optimization》前五章教学实践验证：

| 章节 | 内容 |
|---|---|
| 第 1-3 章 | 凸集、凸函数、共轭函数等基础工具 |
| 第 4 章 | 凸优化问题 — LP / QP / SOCP / SDP 问题家族、DCP/CVXPY、多目标优化 |
| 第 5 章 | 对偶理论 — 拉格朗日对偶、KKT 条件、敏感性分析、Farkas 引理、无套利定理 |

## 使用方法

1. 将本目录作为 Claude Code Skill 加载
2. 上传 Boyd《Convex Optimization》PDF
3. 告诉 AI 你要学哪一章 / 哪一页
4. AI 会按 Skill 规范分块教学，每块讲完等你确认再继续

## License

MIT — 自由使用、修改、分发。
