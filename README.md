# Source-Backed M&A / Asset Deal Memo Workflow

A document-driven workflow for building source-backed M&A and asset-deal research memos from a transaction headline, clue, or public-source lead.

## What this does

This workflow helps an analyst turn a transaction clue into a structured memo using public documents and strict source discipline.

It is designed for:
- M&A research analysts
- strategy teams
- transaction intelligence teams
- infrastructure and energy-transition researchers
- competitive intelligence workflows

## What the output includes

The workflow produces a memo with the following sections:

1. Transaction Identification  
2. Transaction Snapshot  
3. Parties Identified  
4. Document Search Log  
5. Ownership Structure of Buyer(s) as of Announcement Date  
6. Ownership Structure of Seller(s) as of Announcement Date  
7. Transaction Details  
8. Asset / Company Details  
9. Advisors  
10. Status Update  
11. Not Found  
12. Source Register  

## Core principles

- Primary-source first
- No unsupported inference
- No guessing on ownership, value, or terms
- Clear separation between confirmed facts and secondary-source facts
- Explicit reporting of what was not found
- Exhaustive document retrieval where public materials exist

## Best use cases

This workflow is especially useful for:
- acquisitions
- asset sales
- minority or majority stake transactions
- project acquisitions
- platform deals
- joint ventures
- carve-outs
- energy-transition transactions

Typical sectors:
- electricity generation
- transmission and distribution
- renewables
- storage
- EV and battery value chain
- mining
- transition infrastructure
- industrial decarbonization

## Quick start

1. Open `prompt/transaction_memo_prompt.md`
2. Copy the workflow prompt
3. Replace the placeholders with your deal clue
4. Run it in your preferred LLM
5. Compare the output against the example files in `examples/`

## Example cases in this repo

### Example 1 — GIP and EQT / AES
- Input: `examples/input_01_headline.txt`
- Output: `examples/output_01_memo.md`

### Example 2 — XCF Global / Focus Impact BH3
- Input: `examples/input_02_headline.txt`
- Output: `examples/output_02_memo.md`

### Example 3 — STEC / Braes Bayou and Brotman Generating Stations
- Input: `examples/input_03_headline.txt`
- Output: `examples/output_03_memo.md`

## Repo structure

- `prompt/transaction_memo_prompt.md` — main workflow prompt
- `docs/methodology.md` — how the workflow is meant to operate
- `docs/source_policy.md` — source hierarchy and evidence rules
- `docs/limitations.md` — known limitations
- `examples/` — sample inputs and memo outputs

## Why this workflow is different

Many transaction summaries stop at the headline. This workflow does not.

It is built to:
- verify the actual transaction structure from documents
- retrieve filings, press releases, and transaction materials
- separate confirmed facts from unsupported assumptions
- track post-announcement developments
- show missing items explicitly

## Example input format

```text
Deal headline: Company A to acquire Project X from Company B
Announcement date if known: 2025-03-14
Region if known: Spain
Source hint if known: company press release
