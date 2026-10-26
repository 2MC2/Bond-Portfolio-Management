# Bond Portfolio Management

An Excel workbook for recording fixed-rate bonds and reviewing a portfolio through summary tables. The workbook is an educational project; its calculations and sample inputs should be independently checked before use.

## What's in the workbook

- **Bond** — a table for bond details, including issuer, ISIN, currency, rating, purchase and maturity dates, coupon, prices, quantity and tax rate. It also contains calculated fields.
- **PortfolioAnalysis** — portfolio summaries, including invested capital, issuer, bond type, maturity and rating breakdowns, and coupon and gain measures.
- **RTable** — a rating reference table used by the workbook.

The workbook includes notes identifying possible future additions such as yield to maturity, duration and credit risk. These should not be assumed to be implemented or validated.

## Getting started

1. Download [Bond Portfolio Management.xlsx](Bond%20Portfolio%20Management.xlsx) from this repository.
2. Open it in Microsoft Excel and review the existing entries and formulas in the **Bond** sheet.
3. Update inputs as appropriate, then inspect the summaries in **PortfolioAnalysis**. Save a separate copy before making changes.

The workbook's compatibility with other spreadsheet applications has not been verified. Data and prices in the file may be historical; check them against current sources.

## Scope and limitations

- The workbook is labelled for **fixed-rate bonds**; it is not a general model for all fixed-income instruments.
- Calculations, tax treatment, price conventions and portfolio summaries have not been independently validated. Check formulas and assumptions against the instruments and situation being analysed.
- Outputs depend on the accuracy and completeness of the inputs. They are not investment recommendations.

## Repository contents

| File | Purpose |
| --- | --- |
| `Bond Portfolio Management.xlsx` | Excel workbook |
| `README.md` | Project overview and instructions |
