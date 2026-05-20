# Evaluation Guide

Use this page to evaluate whether Spec Kit Acceptance Gate fits a real workflow.

## What To Test

- spec driven development acceptance gate MCP
- Spec Kit Acceptance Gate
- Spec Kit Acceptance Gate documentation
- Spec Kit Acceptance Gate remote MCP
- speckitacceptance server card

## Expected Evidence

- Open Spec Kit Acceptance Gate and select the buyer plan.
- Create or request a bearer token from the hosted product.
- Add https://speckitacceptance.clauxel.com/mcp to a compatible MCP client.
- Run tools/list, then call check_spec_acceptance with public-safe sample data.
- Save the returned receipt or export for human review.

## Risk Checks

- Do not put API keys, tokens, payment details, private logs, or customer records in public issues.
- Use public-safe sample data for examples and directory submissions.
- Treat generated receipts and scores as reviewer evidence, not as a substitute for accountable human approval.

## Buyer Path

Default plan: team.

- https://speckitacceptance.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=speckitacceptance_public_docs&utm_content=evaluation_checkout
