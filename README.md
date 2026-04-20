# 房地产 Agent 项目

## 项目目标
为世邦魏理仕（CBRE）相关商业地产业务设计并逐步实现一套 Agent 系统，用于提升研究、交易、招商租赁、资管、设施管理、项目管理、文档自动化等工作效率。

## harness 方法简介
本项目采用 harness 思想推进：Agent = Model + Harness，而不是单次问答。
最小 harness 先聚焦任务编排、状态管理、工具调用、文件读写、结果追踪与基础评测入口。
`docs/02_competitor_fact_table.md` 是后续竞品研究的统一事实入口。
`docs/03_capability_matrix.md` 是竞品能力比较的统一入口。
`docs/04_cbre_business_mapping.md` 是从能力层走向业务场景层的统一入口。

## 当前阶段
- 已完成：任务文档与研究边界
- 待完成：竞品事实表、能力矩阵、CBRE业务映射、MVP设计、PoC实现、Eval与验收
- 本轮目标：建立最小 harness 起点

## 下一步计划
1. 完成 `docs/02~06`
2. 固化 `prompts/`
3. 跑通 `competitor_research workflow`
4. 补齐 `eval case`
