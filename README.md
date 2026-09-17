# Amazon US Fashion Deal Intelligence & Price Index Dataset

[![Open Data](https://img.shields.io/badge/Data-Open%20Dataset-brightgreen)](https://thefashiondeals.com/reports)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Update Frequency](https://img.shields.io/badge/Updates-Weekly%20(Automated)-blue)](https://thefashiondeals.com)
[![Verified Deals](https://img.shields.io/badge/Active%20Deals-13373-orange)](https://thefashiondeals.com)
[![MCP Ready](https://img.shields.io/badge/MCP-Compatible-purple)](https://thefashiondeals.com/api/social/mcp)

Weekly, machine-audited datasets of verified Amazon US fashion price drops, liquidation clearance discounts, and category statistical benchmarks. Published automatically every Monday by **[TheFashionDeals.com](https://thefashiondeals.com)**.

---

## 📈 Latest Intelligence Snapshot (2026-W38)

> **Audit Period:** Sep 14, 2026 — Sep 20, 2026  
> **Full Interactive Report:** [https://thefashiondeals.com/reports/weekly-deal-index-2026-W38](https://thefashiondeals.com/reports/weekly-deal-index-2026-W38)  
> **Pure Markdown View:** [https://thefashiondeals.com/reports/weekly-deal-index-2026-W38.md](https://thefashiondeals.com/reports/weekly-deal-index-2026-W38.md)

| Metric | Verified Value |
| :--- | :--- |
| **Active Monitored Deals** | **13373** |
| **Market Average Discount** | **30.5%** |
| **Deep Clearance (70%+ Off)** | **102 Deals** |
| **Average Sale Price** | **$39.51** (vs $58.85 Retail Baseline) |
| **Total Monitored Savings Pool** | **$255806.08** |

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