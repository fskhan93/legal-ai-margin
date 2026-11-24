# Prompt note

## Prompt excerpt (valuation cases)

> Filter for companies where the deal value is announced. Let's calculate our bear, base, and bull case based on multiples: (Implied EV/ARR \*38 (our gross margin))/Gross Margin at Exit. Once you calculate the multiples, set the cases: bear about 5x, base about 8x and bull about 15x, already lowered for our 38% margin. Save in GitHub repo with the COMP ids behind each case. Also, read the margin summary alongside the crunchbase so the revenue base ties back to it.

## Comparable list checked against the Implied EV/ARR column

| Comp | Deal value | Deal value ÷ est. ARR | Implied EV/ARR in sheet | Used |
|---|---|---|---|---|
| COMP-01 Casetext | $650M announced | 29.5x | 29.5x | Yes, listed but in no case |
| COMP-02 Lexion | $165M announced | 13.75x | 13.8x | Base |
| COMP-03 Seal Software | $188M announced | 10.44x | 10.4x | Bear |
| COMP-08 vLex | $1,000M announced | 10.0x | 10.0x | Bear |
| COMP-04, 05, 06, 07 | Undisclosed | — | blank | Excluded |

- **Filter:** the four comps with an announced deal value are exactly the four that have an Implied EV/ARR in the sheet, so nothing was dropped or added by the filter.
- **Multiples:** each Implied EV/ARR in the sheet matches deal value ÷ estimated ARR at exit, within rounding.

## Checked

- The monthly summary in `Legal_AI_Monthly_Margins.xlsx`: Total Cost, Revenue, Gross Margin, Reported Margin and Model Cost per Revenue $ for Nov 2025 – Oct 2026.

## Rejected

- **Cost split by workload.** The first version had separate columns for contract review, legal research and document drafting costs. These were dropped because only the total cost is wanted.

## Valuation cases: checked and decided

- **Margin.** The model uses 38% as the user specified. The reported 26.1% from the margin summary was offered and not chosen.
- **Bull case.** It is set at 15x as a judgment call. Using COMP-01 (Casetext) at 20.4x was offered and rejected. So was averaging COMP-01 and COMP-02.
- **Revenue base.** The base is all revenue for the 12 months, $1.36M. Trailing-12-month recurring revenue ($1.32M) and October run-rate × 12 ($1.69M) were offered and rejected.

## Still open

- **Memo columns.** The workbook still has two grey reference columns: R&D-booked model spend (evaluation and fine-tuning) and an all-in margin that also subtracts it. Whether to keep them hasn't been decided.
