# Changelog

## [1.0.0] - 2026-07-10

### Added
- 初始版本，覆盖三位中国顶流基金经理：张坤（易方达）、谢治宇（兴证全球）、高楠（永赢）
- 每位经理包含：
  - 投资方法框架 `method.md`（含原话佐证）
  - 评分卡 `scorecard.md`
  - 原文语料 `corpus/`（定期报告、媒体报道、简介、基金清单）
  - 真实基金数据 `fund_data/`（季度持仓、净值业绩规模）
- 全市场约2.7万只基金列表 `references/all_funds/fund_list.json`
- Python 脚本工具链：
  - `search_corpus.py` — 语料检索
  - `fund_lookup.py` — 基金代码查询
  - `fetch_any_fund.py` — 任意基金数据抓取
  - `score_fund.py` — 框架评分
  - `build_index.py` — 语料索引重建
  - `build_fund_list.py` — 全市场基金列表重建
  - `fetch_fund_data.py` — 经理基金数据刷新
