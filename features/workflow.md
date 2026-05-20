# Workflow

Spec Kit Acceptance Gate is a hosted remote MCP for spec driven development acceptance gate MCP.

## Repeatable Flow

1. Open Spec Kit Acceptance Gate and select the buyer plan.
2. Create or request a bearer token from the hosted product.
3. Add https://speckitacceptance.clauxel.com/mcp to a compatible MCP client.
4. Run tools/list, then call check_spec_acceptance with public-safe sample data.
5. Save the returned receipt or export for human review.

## Output Mindset

The useful artifact is not a marketing claim. It is evidence that a reviewer can inspect, export, and compare later.
