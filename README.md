# Flu Shot Cost Toolkit

**Official website: [FluShotsNearMe — flushotsnearme.com](https://flushotsnearme.com/)**

Editable templates for comparing the flu shot quotes you collect for yourself or your family. Record the product, confirmed remaining doses, quoted price and extra costs. See the calculation before choosing where to go.

For published references and the online estimator, visit **[flu shot costs without insurance](https://flushotsnearme.com/flu-shot-cost/)**. To find nearby addresses, use the ZIP search on our [website](https://flushotsnearme.com/).

## Download and start

1. **[Download the comparison workbook](templates/flu-shot-cost-comparison.xlsx?raw=true)** and open it in a spreadsheet application that supports XLSX formulas.
2. Use the **Compare** tab for your own quotes. Yellow cells are editable. The **Example** tab contains invented prices to explain the calculation.
3. Enter up to three provider/location options and up to four people. Record each person's product, remaining doses confirmed with the provider, and price per dose.
4. Enter total extra fees for each option. Use `0` only when you have confirmed there are none. Add any immediate discount, then choose whether to include travel.
5. Read the estimate at the top and the line-by-line calculation below. A missing required amount produces a message rather than a misleading total.

No installation, account, macros or API keys are needed for the workbook. Download it before entering personal information. Opening the website links visits an external website; the workbook itself has no data connections or telemetry.

## What's included

| File | Use |
| --- | --- |
| [Comparison workbook](templates/flu-shot-cost-comparison.xlsx?raw=true) | Formula-based totals, three options, four people, editable inputs and a fictional example |
| [Quote collection CSV](templates/quote-collection.csv) | Record quotes in your preferred spreadsheet or notes workflow; this CSV does not calculate totals |
| [Family calculation example](examples/family-estimate.md) | Follow a complete $99 household estimate using fictional inputs |
| [Pharmacy quote checklist](docs/quote-checklist.md) | Questions to ask before relying on a quoted price |
| [Workbook instructions](docs/workbook-guide.md) | Understand blanks, fees, discounts, travel and formula messages |

## How costs are calculated

```text
Each person's cost = confirmed remaining doses × quoted price per dose
Option total = sum of person costs + total extra fees
               − immediate discount + travel included once
```

Amounts are entered in USD with at most two decimal places. Calculations use whole cents for multiplication, additions and deductions. The workbook keeps unknown costs visible and does not select a vaccine, determine medical eligibility, or prescribe a dose schedule.

An estimate does not confirm local availability, an appointment, insurance coverage or a provider's final bill. Compare the same people and dose requirements, check product differences with your provider, and use a consistent travel basis. The workbook does not automatically rank options or claim savings between different products.

## About this project

Maintained by **[FluShotsNearMe](https://flushotsnearme.com/)**, an independent resource for comparing flu shot costs and finding nearby pharmacy and health-center addresses in the United States.

This repository contains only the standalone templates and instructions listed here. It does not contain the website's application, account system, payment integration, data collection pipeline or private deployment files.

## Feedback and reuse

For website information or a correction, use our [contact page](https://flushotsnearme.com/contact/). Public issues can discuss template bugs using invented examples. **Do not upload filled workbooks, personal health information, insurance identifiers or private contact details.**

The original files in this repository are available under the [MIT License](LICENSE). That license covers this toolkit only, not other content or code on the website. Keep the attribution when sharing the templates.

Version 1.0.0 · October 8, 2026. See [the changelog](CHANGELOG.md) for scope and verification notes.
