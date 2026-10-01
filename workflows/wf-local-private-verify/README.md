# 到店核销引导

> 提醒话术+预约入口推送

工作流 `wf-local-private-verify`　·　归属 私域复购管家　·　触发 事件（领券后 48h 未到店）　·　
复杂度 M　·　阶段 P1

## 调用链

- `优惠券策略`（coupon-strategy）
- `企微 SCRM 对接`（wecom-connect）

## 文档

- [`WORKFLOW.md`](WORKFLOW.md) — 完整编排、闸门、降级与验收标准
- [`tests/cases.yaml`](tests/cases.yaml) — 端到端 / 闸门 / 降级用例

## 一句话试用

```text
帮我跑 私域复购管家 的「到店核销引导」：<你的输入>
```
