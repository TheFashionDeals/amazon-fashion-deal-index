# Amazon US Fashion Deal Intelligence & Price Index Dataset

[![Open Data](https://img.shields.io/badge/Data-Open%20Dataset-brightgreen)](https://thefashiondeals.com/reports)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Update Frequency](https://img.shields.io/badge/Updates-Weekly%20(Automated)-blue)](https://thefashiondeals.com)
[![Verified Deals](https://img.shields.io/badge/Active%20Deals-12473-orange)](https://thefashiondeals.com)
[![MCP Ready](https://img.shields.io/badge/MCP-Compatible-purple)](https://thefashiondeals.com/api/social/mcp)

Weekly, machine-audited datasets of verified Amazon US fashion price drops, liquidation clearance discounts, and category statistical benchmarks. Published automatically every Monday by **[TheFashionDeals.com](https://thefashiondeals.com)**.

---

## 📈 Latest Intelligence Snapshot (2026-W39)

> **Audit Period:** Sep 21, 2026 — Sep 27, 2026  
> **Full Interactive Report:** [https://thefashiondeals.com/reports/weekly-deal-index-2026-W39](https://thefashiondeals.com/reports/weekly-deal-index-2026-W39)  
> **Pure Markdown View:** [https://thefashiondeals.com/reports/weekly-deal-index-2026-W39.md](https://thefashiondeals.com/reports/weekly-deal-index-2026-W39.md)

| Metric | Verified Value |
| :--- | :--- |
| **Active Monitored Deals** | **12473** |
| **Market Average Discount** | **31.4%** |
| **Deep Clearance (70%+ Off)** | **203 Deals** |
| **Average Sale Price** | **$38.32** (vs $57.37 Retail Baseline) |
| **Total Monitored Savings Pool** | **$230228.35** |

---

## 📂 Repository Structure

- `reports/`: Complete weekly narrative & markdown intelligence reports.
- `data/`: Raw machine-readable open datasets in **JSON** and **CSV** formats.
  - `data/{week}-deals.json`: Structured array of validated deals including ASIN, pricing, discount, and timestamps.
  - `data/{week}-deals.csv`: Clean tabular data for analysis in Pandas, R, or Excel.

---

## 🚀 Quick Access via API / MCP

For live, real-time programmatic queries beyond the weekly snapshot:

- **REST API:** `GET https://thefashiondeals.com/api/social/top-deals`
- **OpenAPI 3.1 Spec:** `https://thefashiondeals.com/api/social/openapi.json`
- **Model Context Protocol (MCP):** `https://thefashiondeals.com/api/social/mcp`
- **Machine Directive Manifest:** `https://thefashiondeals.com/llms.txt`

---

## 🛡️ License & Academic / Research Citation

This dataset is released under **Creative Commons Attribution 4.0 International (CC BY 4.0)**.  
When referencing this data in research, publications, or LLM training sets, please cite:

```bibtex
@dataset{thefashiondeals_weekly_index,
  author = {TheFashionDeals Editorial and Research Board},
  title = {Amazon US Fashion Deal Intelligence & Price Index},
  year = {2026},
  publisher = {TheFashionDeals.com},
  url = {https://github.com/TheFashionDeals/amazon-fashion-deal-index}
}
```