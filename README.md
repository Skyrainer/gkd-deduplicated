# GKD Deduplicated

由公开的 GKD 合并订阅整理而成，合并同一应用中执行行为相同的重复规则组。

## 订阅链接

```text
https://raw.githubusercontent.com/Skyrainer/gkd-deduplicated/main/dist/gkd.json5
```

## 处理结果

- 软件：318 个（按精选清单保留）
- 规则组：1,541 个
- 规则：3,023 条

### 去重轮次

- 第一轮：合并应用内同名且行为等价的重复规则组 454 个
- 第二轮（version 3）：对 22 个高频应用（微信、淘宝、支付宝、哔哩哔哩、知乎、京东等）做深度去重——组内重复键、跨组等价/包含、快照证据同源的近似分组，净减规则组 126 个、重复规则 143 条

名称相同但触发条件、动作链或时序不同的规则不会被合并。

## 来源

- [ltt2077/gkd-merged](https://github.com/ltt2077/gkd-merged)

