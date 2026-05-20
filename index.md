# Spec Kit Acceptance Gate

Spec Kit Acceptance Gate is a hosted remote MCP for spec driven development acceptance gate MCP.

This repository is a public documentation project for Spec Kit Acceptance Gate. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://speckitacceptance.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=speckitacceptance_public_docs&utm_content=readme_home
- Pricing: https://speckitacceptance.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=speckitacceptance_public_docs&utm_content=readme_pricing
- Checkout: https://speckitacceptance.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=speckitacceptance_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://speckitacceptance.clauxel.com/mcp
- Server card: https://speckitacceptance.clauxel.com/server-card.json
- Registry name: `com.clauxel.speckitacceptance/speckitacceptance-mcp`
- Tools: `check_spec_acceptance`, `map_diff_to_requirements`, `verify_acceptance_evidence`, `issue_acceptance_receipt`, `export_acceptance_audit`

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
- MCP tool: check_spec_acceptance
- MCP tool: map_diff_to_requirements
- MCP tool: verify_acceptance_evidence
- MCP tool: issue_acceptance_receipt
- MCP tool: export_acceptance_audit

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
