# Metric Plan

## Purpose

This document defines the financial metrics planned for the project. The goal is to evaluate selected apparel and retail companies using consistent, transparent, and reproducible definitions.

The analysis focuses on whether revenue growth is present, whether that growth appears financially supported, and where performance appears weaker, mixed, or under pressure.

## Analytical Question

Among selected apparel and retail companies, where is revenue growth present, is that growth supported by margins, operating cash flow, working capital discipline, and balance sheet trends, and which firms show signs of weaker or lower-quality performance?

## Metric Groups

This project will organize metrics into five evidence groups:

1. Revenue growth
2. Margin support
3. Cash conversion
4. Working capital discipline
5. Balance sheet pressure

The final output will use these metrics to support a peer financial performance scorecard.

---

## 1. Revenue Growth

Revenue growth establishes the headline trend. This section answers whether revenue increased, whether growth was consistent, and whether the company's top-line performance appears stronger, flat, or declining.

| Metric | Formula | Source Statement | Purpose | Potential Warning Sign |
|---|---|---|---|---|
| Revenue | Reported Revenue | Income statement | Establishes company size and sales trend | Revenue is flat, declining, or highly volatile |
| Year-over-year revenue growth | `(current_year_revenue / prior_year_revenue) - 1` | Income statement | Measures annual revenue growth | Growth reverses, declines, or depends on one unusual year |
| Revenue CAGR | `(ending_revenue / beginning_revenue) ^ (1 / number_of_years) - 1` | Income statement | Summarizes multi-year growth | CAGR is positive but driven by one abnormal period |
| Positive growth years | Count of years where revenue growth is greater than zero | Income statement | Measures consistency of growth | Revenue growth is inconsistent or frequently negative |

### Interpretation

Revenue growth is useful, but it is not enough by itself. A company can grow revenue while margins weaken, cash flow declines, inventory builds, or leverage increases.

### Key Question

Did revenue grow, and was the growth consistent enough to support a stronger performance story?

---

## 2. Margin Support

Margin metrics evaluate whether revenue trends are supported by profitability. For apparel and retail companies, margin trends can reflect pricing power, product mix, markdowns, cost pressure, inventory issues, and operating efficiency.

| Metric | Formula | Source Statement | Purpose | Potential Warning Sign |
|---|---|---|---|---|
| Gross margin | `gross_profit / revenue` | Income statement | Measures profitability after cost of goods sold | Revenue grows while gross margin declines |
| Operating margin | `operating_income / revenue` | Income statement | Measures profitability after operating expenses | Revenue grows while operating margin compresses |
| Net margin | `net_income / revenue` | Income statement | Measures bottom-line profitability | Net margin improves while operating margin weakens |
| SG&A ratio | `selling_general_admin_expenses / revenue` | Income statement | Measures operating cost burden | SG&A grows faster than revenue |

### Interpretation 

A stronger growth story should usually show stable or improving margins. If revenue grows while gross or operating margins decline, the company may be growing through discounting, higher costs, weaker operating leverage, or less profitable channels.

### Key Question

Did revenue growth come with stable or improving profitability, or did margins weaken?

---

## 3. Cash Conversion

Cash conversion metrics evaluate whether reported performance converts into operating cash flow. This is central to the quality-of-performance lens because earnings and revenue growth are more persuasive when they are supported by cash generation.

| Metric | Formula | Source Statement | Purpose | Potential Warning Sign |
|---|---|---|---|---|
| Operating cash flow | Reported net cash provided by operating activities | Cash flow statement | Measures cash generated from operations | Operating cash flow weakens while revenue or net income improves |
| Operating cash flow margin | `operating_cash_flow / revenue` | Income statement and cash flow statement | Measures operating cash generated per dollar of revenue | Revenue grows while OCF margin declines |
| Free cash flow | `operating_cash_flow - capital expenditures` | Cash flow statement | Measures cash after capital investment | Net income is positive but free cash flow is weak or negative |
| OCF to net income | `operating_cash_flow / net_income` | Income statement and cash flow statement | Compares operating cash flow to reported earnings | Net income rises while OCF does not keep pace |
| Net income to OCF gap | `net_income - operating_cash_flow` | Income statement and cash flow statement | Highlights earnings-to-cash divergence | Gap widens over time, with earnings exceeding cash flow |

### Interpretation

A company can report revenue growth and net income growth while operating cash flow tells a weaker story. For this project, cash conversion will be one of the main tests of whether performance appears financially supported.

### Key Question

Is reported performance supported by operating cash flow?

---

## 4. Working Capital Discipline

Working capital metrics evaluate whether revenue trends are accompanied by inventory or receivables pressure. This is especially relevant in apparel and retail because inventory levels, markdown risk, wholesale exposure, and collection timing can affect the quality of reported growth.

| Metric | Formula | Source Statement | Purpose | Potential Warning Sign |
|---|---|---|---|---|
| Inventory | Reported inventory | Balance sheet | Measures goods held for sale | Inventory rises while revenue is flat or declining |
| Inventory growth | `(current_year_inventory / prior_year_inventory) - 1` | Balance sheet | Measures inventory buildup | Inventory grows faster than revenue |
| Inventory as percentage of revenue | `inventory / revenue` | Balance sheet and income statement | Scales inventory against sales | Inventory intensity rises over time |
| Inventory growth minus revenue growth | `inventory_growth - revenue_growth` | Balance sheet and income statement | Compares inventory growth to sales growth | Inventory materially exceeds revenue growth |
| Accounts receivable | Reported accounts receivable | Balance sheet | Measures amounts owed by customers or wholesale partners | Receivables rise while revenue growth is weak |
| Accounts receivable growth | `(current_year_accounts_receivable / prior_year_accounts_receivable) - 1` | Balance sheet | Measures growth in receivables | Receivables grow faster than revenue |
| Accounts receivable as percentage of revenue | `accounts_receivable / revenue` | Balance sheet and income statement | Scales receivables against sales | Receivables intensity rises over time |
| Receivables growth minus revenue growth | `accounts_receivable_growth - revenue_growth` | Balance sheet and income statement | Compares receivables growth to sales growth | Receivables growth materially exceeds revenue growth |

### Interpretation

Inventory and receivables can reveal pressure beneath the revenue line. Inventory growth that outpaces revenue may indicate demand risk, markdown risk, or operational strain. Receivables growth that outpaces revenue may indicate collection pressure or wholesale-channel effects.

### Key Question

Is growth creating working capital pressure beneath the revenue line?

---

## 5. Balance Sheet Pressure

Balance sheet metrics evaluate whether financial position is strengthening or weakening. These metrics help identify whether revenue growth or operating performance is paired with liquidity or rising leverage.

| Metric | Formula | Source Statement | Purpose | Potential Warning Sign |
|---|---|---|---|---|
| Current ratio | `current_assets / current_liabilities` | Balance sheet | Measures short-term liquidity | Current ratio weakens over time |
| Cash as percentage of total assets | `cash_and_cash_equivalents / total_assets` | Balance sheet | Measures balance sheet flexibility | Cash cushion declines materially |
| Financial debt-to-assets | `financial_debt / total_assets` | Balance sheet | Measures traditional interest-bearing debt relative to assets | Financial debt burden rises over time |
| Financial debt-to-equity | `financial_debt / shareholders_equity` | Balance sheet | Measures traditional interest-bearing debt relative to equity | Financial debt-to-equity rises sharply |
| Lease-adjusted debt-to-assets | `lease_adjusted_debt / total_assets` | Balance sheet | Measures leverage after including operating lease liabilities | Lease-adjusted obligations rise materially |
| Lease-adjusted debt-to-equity | `lease_adjusted_debt / shareholders_equity` | Balance sheet | Measures leverage after including operating lease liabilities relative to equity | Lease-adjusted debt-to-equity rises sharply |
| Operating income interest coverage | `operating_income / interest_expense` | Income statement | Measures whether operating profit covers reported interest expense | Coverage weakens while debt rises |

### Debt Definition Note

This project will distinguish between financial debt and lease-adjusted debt.

Financial debt includes short-term debt, current portion of long-term debt, long-term debt, and finance lease liabilities where separately reported.

Lease-adjusted debt includes financial debt plus current and noncurrent operating lease liabilities. This distinction matters for apparel and retail companies because store lease obligations can materially affect leverage comparisons.

The analysis will report lease-adjusted leverage separately rather than folding operating lease liabilities into total debt without labeling the adjustment.

### Interest Coverage Definition Note

This project will use operating income interest coverage, defined as `operating_income / interest_expense`.

This measure evaluates whether operating profit covers reported interest expense. It is not the same as EBITDA-based interest coverage, which adds back depreciation and amortization, and it is not a fixed-charge coverage measure that incorporates lease-related obligations.

This distinction matters for apparel and retail companies because depreciation, amortization, store leases, and capital intensity can vary across business models. Operating income interest coverage is used as a conservative, statement-based measure for the first version of the project. If depreciation, amortization, and lease expense data are consistently available, EBITDA-based coverage or fixed-charge coverage may be added later as supplemental metrics.

### Interpretation

A company may show revenue growth while becoming more financially strained. Liquidity and leverage metrics help show whether performance is supported by a stable financial position or whether the company is taking on more risk.

### Key Question

Is the company becoming financially stronger, or is performance paired with balance sheet strain?

## Scorecard Framework

The final scorecard will classify each company based on the combined evidence across the metric groups.

| Classification | Meaning |
|---|---|
| Supported growth | Revenue growth is present and supported by stable or improving margins, cash conversion, working capital, and balance sheet indicators |
| Mixed performance | Revenue growth or profitability is present, but the supporting indicators are uneven |
| Growth with pressure | Revenue grows while margins, cash flow, inventory, receivables, liquidity, or leverage show signs of strain |
| Weaker performance | Revenue is flat or declining, or financial indicators point to broader deterioration |
| Inconclusive | The evidence does not support a clear interpretation |

## How Evidence Maps to Classification

The scorecard will use analyst judgment rather than a rigid point system. Each company will be evaluated across five evidence groups: revenue growth, margin support, cash conversion, working capital discipline, and balance sheet pressure.

Revenue growth establishes the performance trend, but it is not enough by itself to classify a company as stronger. The supporting evidence groups determine whether that growth appears financially supported.

A supporting evidence group will be considered strained when multiple metrics in that group move in an unfavorable direction, or when one primary metric shows meaningful deterioration. For example, margin support may be strained if gross and operating margins decline while revenue grows. Cash conversion may be strained if operating cash flow weakens relative to revenue or net income. Working capital may be strained if inventory or receivables grow materially faster than revenue. Balance sheet pressure may be strained if liquidity weakens or leverage rises.

In general:

- **Supported growth** requires revenue growth plus broadly stable or improving support from margins, cash conversion, working capital, and balance sheet indicators.
- **Mixed performance** applies when the evidence is split, such as revenue growth with one or two strained support areas, or weaker revenue growth with otherwise stable financial indicators.
- **Growth with pressure** applies when revenue grows but two or more supporting evidence groups show strain, or when one major area, such as cash conversion or leverage, raises a significant concern.
- **Weaker performance** applies when revenue is flat or declining and multiple supporting indicators also deteriorate.
- **Inconclusive** applies when missing data, inconsistent reporting, unusual one-time events, or conflicting signals prevent a clear interpretation.

The classification should be supported by the full pattern of evidence, not by a single ratio.

## Metric Construction Notes

The project will use annual financial statement data for the latest five complete fiscal years available.

Each company year record should include, where available:

- Revenue
- Gross profit
- Operating income
- Net income
- Operating cash flow
- Capital expenditures
- Inventory
- Accounts receivable
- Current assets
- Current liabilities
- Cash and cash equivalents
- Total assets
- Total liabilities
- Short-term debt
- Current portion of long-term debt
- Long-term debt
- Finance lease liabilities, where separately reported
- Current operating lease liabilities
- Noncurrent operating lease liabilities
- Shareholders' equity
- Interest expense

## Planned Data Checks

Before interpreting results, the project will check for:

- Missing company year records
- Duplicate company year records
- Missing values in required financial statement fields
- Fiscal year and reporting period inconsistencies
- Sign convention issues, especially for cash flow items
- Zero or near-zero denominators in ratio calculations
- Negative values that require explanation
- Large year-over-year changes that may require review
- Reporting classification differences across companies

## Interpretation Rules

The analysis will avoid treating any single metric as conclusive.

A company will not be classified as financially stronger only because revenue increased. The interpretation must consider whether revenue trends are supported by margins, cash conversion, working capital discipline, and balance sheet position.

The analysis will also avoid treating the peer set as perfectly comparable. Differences in business model, channel mix, product mix, fiscal year timing, and reporting classification will be documented where relevant.

## Exclusions

This metric plan does not support:

- Investment advice
- Valuation conclusions
- Stock price predictions
- Buy, sell, or hold recommendations
- Claims that the selected companies are perfectly comparable