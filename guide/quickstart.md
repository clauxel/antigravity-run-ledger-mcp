# Quickstart

Antigravity Run Ledger is a hosted remote MCP for Antigravity agent run receipt MCP.

## Fast Path

1. Open Antigravity Run Ledger and select the buyer plan.
2. Create or request a bearer token from the hosted product.
3. Add https://antigravityrunledger.clauxel.com/mcp to a compatible MCP client.
4. Run tools/list, then call issue_run_receipt with public-safe sample data.
5. Save the returned receipt or export for human review.

## Useful Links

- https://antigravityrunledger.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=antigravityrunledger_public_docs&utm_content=quickstart_home
- https://antigravityrunledger.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=antigravityrunledger_public_docs&utm_content=quickstart_pricing
- https://antigravityrunledger.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=antigravityrunledger_public_docs&utm_content=quickstart_checkout

## MCP Endpoint

```text
https://antigravityrunledger.clauxel.com/mcp
```

Use bearer-token authentication for production calls. Keep the token in the MCP client's secret mechanism.
