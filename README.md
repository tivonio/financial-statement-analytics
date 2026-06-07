# Financial Statement Analytics with Python and SQL

This project examines the quality of revenue growth across selected apparel and retail companies. The analysis compares revenue growth with margins, operating cash flow, working capital discipline, and balance sheet trends to evaluate whether reported growth appears financially supported.

The project uses public company financial statement data and is designed as a reproducible analytics workflow using SQL and Python.

## Status

Planning and setup stage. Repository structure and project documentation are in progress.

## Project Question

Among selected apparel and retail companies, where is revenue growth present, is that growth supported by margins, operating cash flow, working capital discipline, and balance sheet trends, and which firms show signs of weaker or lower-quality performance?

## Peer Set

The initial peer set includes:

| Company | Ticker |
|---|---|
| Nike | NKE |
| Lululemon | LULU |
| Under Armour | UAA |
| Levi Strauss | LEVI |
| Gap | GPS |
| Abercrombie & Fitch | ANF |

The peer set intentionally includes related but distinct apparel and retail business models, including branded apparel, athletic apparel, and specialty apparel retail. This variation is part of the project design. The analysis focuses on signals that can travel across business models, such as revenue trends, margin support, cash conversion, inventory discipline, and balance sheet pressure. Absolute margin levels and operating structures will be interpreted with business-model differences in mind.

## Decision Supported

A strategic finance team at an apparel company is preparing a competitive review of selected apparel and retail peers. The analysis supports strategic planning and competitive monitoring by helping leadership identify which companies appear financially stronger, which show weaker or mixed performance, and which require closer monitoring based on revenue growth, margins, cash flow, working capital, and balance sheet trends.

## Planned Data Source

The planned primary data source is SEC EDGAR financial statement data, using company filings and XBRL/company facts data where practical. Annual reports and Form 10-K filings may be reviewed to validate financial statement definitions, fiscal periods, and reporting classifications.

If the SEC data structure creates limitations for consistent peer comparison, those limitations will be documented in the analysis.

## Planned Analysis

The project will evaluate:

- Revenue growth
- Gross, operating, and net margins
- Operating cash flow and free cash flow
- Earnings-to-cash conversion
- Inventory and receivables trends
- Liquidity and leverage indicators
- Overall quality of revenue growth

## Planned Output

The final project will produce a peer financial performance scorecard that summarizes each company's revenue trend, margin support, cash conversion, working capital discipline, and balance sheet position.

The scorecard will classify each company into one of the following categories:

| Classification | Meaning |
|---|---|
| Supported growth | Revenue growth is present and supported by stable or improving margins, cash conversion, working capital, and balance sheet indicators |
| Mixed performance | Revenue growth or profitability is present, but the supporting indicators are uneven |
| Growth with pressure | Revenue grows while margins, cash flow, inventory, receivables, liquidity, or leverage show signs of strain |
| Weaker performance | Revenue is flat or declining, or financial indicators point to broader deterioration |
| Inconclusive | The evidence does not support a clear interpretation |

The scorecard is intended to support strategic planning and competitive monitoring, not investment recommendations or valuation conclusions.

## Tools

Planned tools include:

- SQL for data validation, metric construction, and repeatable checks
- Python for data preparation, analysis, and visualization
- Public company financial statement data

## Repository Structure

```text
financial-statement-analytics/
    data/
        raw/
        interim/
        processed/

    docs/

    notebooks/

    outputs/
        tables/
        figures/

    sql/

    src/
```