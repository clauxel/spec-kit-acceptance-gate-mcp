# Quickstart

Spec Kit Acceptance Gate is a hosted remote MCP for spec driven development acceptance gate MCP.

## Fast Path

1. Open Spec Kit Acceptance Gate and select the buyer plan.
2. Create or request a bearer token from the hosted product.
3. Add https://speckitacceptance.clauxel.com/mcp to a compatible MCP client.
4. Run tools/list, then call check_spec_acceptance with public-safe sample data.
5. Save the returned receipt or export for human review.

## Useful Links

- https://speckitacceptance.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=speckitacceptance_public_docs&utm_content=quickstart_home
- https://speckitacceptance.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=speckitacceptance_public_docs&utm_content=quickstart_pricing
- https://speckitacceptance.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=speckitacceptance_public_docs&utm_content=quickstart_checkout

## MCP Endpoint

```text
https://speckitacceptance.clauxel.com/mcp
```

Use bearer-token authentication for production calls. Keep the token in the MCP client's secret mechanism.
