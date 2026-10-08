# DMIT VPS 全产品线推荐与选购指南

把 DMIT（dmit.io）官网在售的 **15 条云服务器产品线**逐款拆开：机房在哪、走哪种网络
（Premium / Eyeball / Tier 1）、什么硬件平台、月付多少、适合哪一类运营商用户，
以及 NodeSeek 社区的真实测评怎么说。

## 页面

| 文件 | 说明 |
|------|------|
| [`dmit-vps-guide.html`](dmit-vps-guide.html) | 主页面（单文件，含 JSON-LD 结构化数据；每个档位价格均有 aff 购买链接） |
| [`dmit-vps-guide.md`](dmit-vps-guide.md) | 同一内容的 Markdown 版；每个档位价格均附 aff 购买链接 |
| [`index.html`](index.html) | 首页跳转页（`/` → `dmit-vps-guide.html`） |
| [GitHub Pages 预览](https://peterxulove.github.io/dmit-vps/dmit-vps-guide.html) | 在线选购指南 |
| [Google Sites 预览](https://sites.google.com/view/dmit-vps-guide) | Google Sites 镜像页 |

## DMIT 推广购买入口（aff=27885）

以下为 DMIT 官方产品级推广链接。通过链接访问后购买，不会增加用户费用。

| 产品线 | 参考起价 | 推广购买链接 |
|--------|----------|--------------|
| 洛杉矶 AS3 Premium | $10.90/月 | [TINY · pid=253](https://www.dmit.io/aff.php?aff=27885&pid=253) |
| 洛杉矶 AN4 Premium | 官网暂未开放下单 | [DMIT 推广入口](https://www.dmit.io/aff.php?aff=27885) |
| 洛杉矶 AN5 Premium | $79.90/月 | [MINI · pid=58](https://www.dmit.io/aff.php?aff=27885&pid=58) |
| 洛杉矶 AS3 Eyeball | $10.90/月 | [TINY · pid=259](https://www.dmit.io/aff.php?aff=27885&pid=259) |
| 洛杉矶 AN4 Eyeball | 官网暂未开放下单 | [DMIT 推广入口](https://www.dmit.io/aff.php?aff=27885) |
| 洛杉矶 AN5 Eyeball | $79.90/月 | [MINI · pid=192](https://www.dmit.io/aff.php?aff=27885&pid=192) |
| 洛杉矶 AN5 Tier 1 | $14.90/月 | [V2C2G · pid=169](https://www.dmit.io/aff.php?aff=27885&pid=169) |
| 洛杉矶 AS3 Tier 1 | $6.90/月 | [TINY · pid=271](https://www.dmit.io/aff.php?aff=27885&pid=271) |
| 中国香港 AN5 Premium | $149.90/月 | [MINI · pid=125](https://www.dmit.io/aff.php?aff=27885&pid=125) |
| 中国香港 AS3 Premium | $39.90/月 | [TINY · pid=265](https://www.dmit.io/aff.php?aff=27885&pid=265) |
| 中国香港 AN5 Eyeball | $149.90/月 | [MINI · pid=156](https://www.dmit.io/aff.php?aff=27885&pid=156) |
| 中国香港 AS3 Eyeball | $39.90/月 | [TINY · pid=210](https://www.dmit.io/aff.php?aff=27885&pid=210) |
| 中国香港 AS3 Tier 1 | $6.90/月 | [TINY · pid=198](https://www.dmit.io/aff.php?aff=27885&pid=198) |
| 东京 AS3 Premium | $21.90/月 | [TINY · pid=138](https://www.dmit.io/aff.php?aff=27885&pid=138) |
| 东京 AS3 Tier 1 | $6.90/月 | [TINY · pid=131](https://www.dmit.io/aff.php?aff=27885&pid=131) |

> AN4 两条产品线在官网价格页展示了价格，但目前没有档位下单 pid；链接先到 DMIT 推广入口，
> 是否开放下单以官网为准。详细价格、规格与每档位的购买链接见 HTML / Markdown 指南。

## 内容结构

速览结论 → 15 条产品线速览表 → 运营商适配矩阵 → 逐款详解（含档位表、社区引用、适合/不适合）
→ 常见问题 → 选购注意事项 → 数据来源与引用。

## 核心结论

- 产品骨架 = **机房 × 网络系列 × 硬件平台**：洛杉矶 / 中国香港 / 东京 ×
  Premium / Eyeball / Tier 1 × AN5(EPYC 9005) / AN4(EPYC 9004) / AS3(EPYC 7003)
- **电信选 Premium（CN2 GIA），联通 / 移动选 Eyeball（CMIN2）** —— 出自 DMIT 客服工单原文
- 机房延迟：中国香港约 15ms、东京约 28ms
- 三个坑：不支持支付宝；正价机经常售罄且限定款二手溢价；154 IP 段 2027-01 起按 $1/月 收费

## 数据来源

- 产品与价格：DMIT 官网定价页（2026-10-08 抓取）；购买入口均用上方 aff 链接
- 第三方测评：NodeSeek 搜索「dmit」12 页 599 条结果中的 57 篇正文与 717 条评论
- 采集方式：本机 Chrome 登录态 + CDP

> 价格与库存为抓取时点快照，随时可能变动；以官网实时信息为准。
