# Antigravity Run Ledger

Antigravity Run Ledger is a hosted remote MCP for Antigravity agent run receipt MCP.

This repository is a public documentation project for Antigravity Run Ledger. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://antigravityrunledger.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=antigravityrunledger_public_docs&utm_content=readme_home
- Pricing: https://antigravityrunledger.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=antigravityrunledger_public_docs&utm_content=readme_pricing
- Checkout: https://antigravityrunledger.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=antigravityrunledger_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://antigravityrunledger.clauxel.com/mcp
- Server card: https://antigravityrunledger.clauxel.com/server-card.json
- Registry name: `com.clauxel.antigravityrunledger/antigravityrunledger-mcp`
- Tools: `issue_run_receipt`, `summarize_agent_changes`, `check_test_evidence`, `flag_review_risk`, `export_run_log`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Security model](features/security-model.md)
6. [Public link reference](reference/links.md)

## Audience

AI product teams, operations leads, workflow owners, and technical evaluators.

## Capabilities

- Streamable HTTP MCP endpoint
- Bearer-token access for production calls
- Structured tool-call output
- Receipt-oriented evidence export
- Public server card and registry metadata
- MCP tool: issue_run_receipt
- MCP tool: summarize_agent_changes
- MCP tool: check_test_evidence
- MCP tool: flag_review_risk
- MCP tool: export_run_log

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
