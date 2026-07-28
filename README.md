# expense-tracker

单页记账应用（vanilla JS + Supabase）。仅供本人使用，含敏感财务数据，仓库私有。

## 使用
- 打开 `index.html` 或 GitHub Pages 部署地址即可。
- 数据双写：浏览器 `localStorage` + Supabase `expenses` 表。
- 首次使用需在 Supabase SQL Editor 建表（页面顶部有一键复制 SQL）。

## 数据来源
- 微信 / 支付宝 / 招商银行 多源账单打通，跨源去重、内部互转已剔除。
- 投资买入=支出、赎回/分红=收入；退款作为原类目负支出冲减。
