# Exit valuation cases

Source: Crunchbase pull of comparable legal-AI exits, filtered to deals with an **announced** deal value. The workbook is `Exit_Valuation_Cases.xlsx`.

## Method

Adjusted EV/ARR = Implied EV/ARR × our gross margin (38%) ÷ gross margin at exit

Implied EV = adjusted multiple × revenue base of **$1,363,641**, which is total revenue for Nov 2025 – Oct 2026 from `Legal_AI_Monthly_Margins.xlsx` (Summary!C17).

## Cases

| Case | Multiple | Implied EV | Comp IDs |
|---|---|---|---|
| Bear | 5.2x | $7.2M | COMP-03 (Seal Software, 5.1x), COMP-08 (vLex, 5.4x), averaged |
| Base | 8.2x | $11.2M | COMP-02 (Lexion) |
| Bull | 15.0x | $20.5M | None, a judgment call. No comp adjusts to about 15x: the nearest are COMP-02 at 8.2x and COMP-01 (Casetext) at 20.4x |

## Excluded

These deals have no announced value: COMP-04 (Evisort), COMP-05 (Kira Systems), COMP-06 (Henchman) and COMP-07 (Safe Sign Technologies).

## Caveats

- **Margin:** the 38% margin was set by the user. The margin summary shows 26.1% (reported), and at that margin every multiple would be about 31% lower.
- **Bear comps:** COMP-03 is a pre-LLM product and COMP-08 is mostly a legal content database.
- **Data quality:** the comps' ARR and margin figures are estimates from Crunchbase and trade press.
