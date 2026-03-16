# Lumen Architectural Lighting — Cost Reconciliation Dashboard

Interactive financial dashboard for cost reconciliation analysis, built as a portfolio demonstration piece.

## Live Demo

**[View the Dashboard →](https://YOUR_USERNAME.github.io/lumen-cost-reconciliation/)**

## Overview

This project demonstrates financial data analysis and visualization capabilities for a fictional architectural lighting company. It includes:

- **Sales vs Budget Analysis** — Track actual revenue against budgeted targets by product segment
- **Gross Margin Analysis** — Monitor profitability across 6 product segments with health indicators
- **Invoice Drill-Down** — Search, filter, sort, and export 179 individual invoice records
- **Month-over-Month Comparison** — Visual comparison of January vs February 2026 performance

## Features

| Feature | Description |
|---------|-------------|
| KPI Cards | Real-time summary metrics for sales, margins, and budget variance |
| Segment Charts | Horizontal bar charts for sales distribution and GM% by segment |
| Budget Variance | Color-coded over/under budget indicators per segment |
| Invoice Table | Sortable, searchable, filterable with pagination (40 per page) |
| CSV Export | One-click export of filtered invoice data |
| Margin Detail | Segment-level margin breakdown with status health indicators |
| Responsive | Adapts to desktop and tablet screen sizes |

## Tech Stack

- **React 18** (production build via CDN)
- **Pure JavaScript** — No build tools, no Babel, no bundler required
- **Single-file architecture** — Everything in one `index.html` (88 KB)
- **Zero dependencies** — Just React + ReactDOM from CDN

## Data

All data in this project is **completely fictional**. "Lumen Architectural Lighting" is a made-up company. All financial figures, customer names, invoice numbers, and product details are randomly generated dummy data created for portfolio demonstration purposes only.

### Data Structure
- **6 Product Segments**: Architectural Indoor, Architectural Outdoor, Decorative Indoor, Poles & Mounting, Nordic Collection, Other
- **12 Product Classes** with unique cost structures
- **179 Invoices** (92 January + 87 February)
- **25 Fictional Customers** across 30 projects

## Companion Excel Workbook

The repository also includes `Lumen_Cost_Reconciliation.xlsx` — a professionally formatted Excel workbook with 4 sheets:
1. **Budget vs Actual** — Segment-level budget comparison
2. **January Data** — Full January invoice detail
3. **February Data** — Full February invoice detail
4. **Margin Analysis** — Product class margin breakdown

## GitHub Pages Setup

1. Push this folder to a new public GitHub repository
2. Go to **Settings** → **Pages** (under "Code and automation")
3. Set Source to **Deploy from a branch**, Branch: **main**, Folder: **/ (root)**
4. Your dashboard will be live at `https://YOUR_USERNAME.github.io/REPO_NAME/`

## Author

Portfolio project demonstrating financial analysis, data visualization, and web development skills.

---

*Built with React 18 · Navy & Gold design system · March 2026*
