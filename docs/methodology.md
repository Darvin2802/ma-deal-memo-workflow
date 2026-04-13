# Methodology

This repository contains a workflow for building source-backed M&A and asset-deal memos from public information.

## Objective

The objective is not to summarize a headline. The objective is to verify the transaction and document it using the strongest available evidence.

## Working order

1. Identify the transaction from the starting clue
2. Verify the real structure from primary sources
3. Retrieve all relevant public documents
4. Build a transaction snapshot
5. Map buyer and seller ownership chains as of announcement date
6. Extract deal terms and transaction mechanics
7. Build the asset or company section
8. Identify advisors
9. Check post-announcement developments
10. Record what was not found
11. Produce a clean source register

## Transaction identification rule

The starting clue is never treated as confirmed fact.

The workflow should confirm:
- the true buyer
- the true seller
- the target or asset
- the transaction type
- the stake involved
- the relevant dates
- the status

If the transaction cannot be identified confidently, the workflow should stop and request clarification.

## Document retrieval rule

The workflow should search widely, but rank evidence quality.

Preferred order:
1. official company press release
2. stock exchange or regulator filing
3. official transaction document
4. investor presentation
5. official company website pages
6. advisor release
7. reputable secondary reporting

## Deduplication rule

If the same press release or filing appears in multiple places, retain the best version only.

Preferred version order:
1. official company source
2. exchange or regulator source
3. officially hosted PDF
4. reputable repost

## Ownership rule

Ownership chains should be reported only where confirmed by evidence.

Do not infer:
- missing ownership links
- implied control
- unstated parent entities

If confirmation stops at an intermediate entity, say so clearly.

## Deal value rule

Deal value should only be reported where confirmed in retrieved sources.

If not confirmed, use:

“No confirmed deal value found in retrieved sources.”

## Presentation window rule

The workflow should search for presentation materials from both buyer and seller within:
- 7 calendar days before announcement date
- 7 calendar days after announcement date

This includes:
- investor presentations
- acquisition presentations
- transaction decks
- analyst presentations
- webcast slides
- conference materials mentioning the deal

## Post-announcement status rule

The workflow should check for:
- closing
- amendments
- termination
- pending status
- superseding deals

Official updates should be preferred over secondary reporting.

## Output rule

The memo should distinguish clearly between:
- facts confirmed in transaction documents
- supplemental facts from company websites or filings
- secondary-source facts used only where necessary

## Not found rule

The workflow must include a “Not Found” section that explicitly lists important materials that were searched for but not confirmed or not retrieved.
