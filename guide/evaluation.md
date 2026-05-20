# Evaluation Guide

Use this page to evaluate whether Antigravity Run Ledger fits a real workflow.

## What To Test

- Antigravity agent run receipt MCP
- Antigravity Run Ledger
- Antigravity Run Ledger documentation
- Antigravity Run Ledger remote MCP
- antigravityrunledger server card

## Expected Evidence

- Open Antigravity Run Ledger and select the buyer plan.
- Create or request a bearer token from the hosted product.
- Add https://antigravityrunledger.clauxel.com/mcp to a compatible MCP client.
- Run tools/list, then call issue_run_receipt with public-safe sample data.
- Save the returned receipt or export for human review.

## Risk Checks

- Do not put API keys, tokens, payment details, private logs, or customer records in public issues.
- Use public-safe sample data for examples and directory submissions.
- Treat generated receipts and scores as reviewer evidence, not as a substitute for accountable human approval.

## Buyer Path

Default plan: team.

- https://antigravityrunledger.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=antigravityrunledger_public_docs&utm_content=evaluation_checkout
