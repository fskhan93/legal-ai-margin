# Cost rule

**Cost** is the total of `amount_usd` on model-provider bills whose `workload` is one of:

- contract review (`contract_review`)
- legal research (`legal_research`)
- document drafting (`document_drafting`)

Add these up for each month and report one **Total Cost** figure per month. Don't split cost out by workload.

Nothing else counts as cost. That includes model evaluation and fine-tuning bills (`model_evaluation_and_finetuning`), which the ledger books to research and development.

## Measures built on this cost

- **Revenue**: the total of `amount_usd` on revenue invoices for the month.
- **Gross Margin ($)**: Revenue − Total Cost.
- **Reported Margin (%)**: Gross Margin ÷ Revenue.
- **Model Cost per Revenue $**: Total Cost ÷ Revenue.
