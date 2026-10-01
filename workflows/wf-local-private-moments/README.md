# 每日朋友圈文案

> 结合当日菜品/天气/热点 → 生成"像人话"的朋友圈

工作流 `wf-local-private-moments`　·　归属 私域复购管家　·　触发 定时（每日 7:30 推送 3 条候选）　·　
复杂度 S　·　阶段 P0

## 调用链

- `朋友圈文案生成`（moments-copy-writer）

## 文档

- [`WORKFLOW.md`](WORKFLOW.md) — 完整编排、闸门、降级与验收标准
- [`tests/cases.yaml`](tests/cases.yaml) — 端到端 / 闸门 / 降级用例

## 一句话试用

```text
帮我跑 私域复购管家 的「每日朋友圈文案」：<你的输入>
```
