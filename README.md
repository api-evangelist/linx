# Linx

Linx Security is an AI-native identity security and governance platform covering the full identity lifecycle across human, non-human, and AI-agent identities. The platform builds an Identity Graph that normalizes identity data across SaaS, cloud, and on-prem systems, then layers identity security posture management, modern IGA (access requests, approvals, provisioning, access certification), just-in-time access, automated lifecycle management, and an autonomous remediation agent called Autopilot.

Founded by Israel Duanis, Niv Goldenberg, and Sarit Reiner Frumkes. Headquartered at 500 7th Ave, New York, NY 10018. Has raised $85M total from Cyberstarts, Index Ventures, and Insight Partners.

- Website — https://www.linx.security/
- Blog — https://www.linx.security/blog
- Trust Center — https://trust.linx.security/
- GitHub — https://github.com/linx-security
- Sign in — https://app.linxsecurity.io

## API surface

Linx publishes **no public developer portal, API reference, or API specification**. Its Master Services Agreement references "the API provided by Company" and its Documentation, but that documentation is available to customers only. No `docs.`, `developer.`, or `api.` host resolves on `linx.security`, and no `.well-known` discovery documents are published.

The agent-facing surface is real but not publicly specified: Linx announced the **Linx MCP Server** on 2025-06-04, exposing the Identity Graph and governed identity actions (investigation, risk detection, access profiles, JIT access requests, access certification, remediation) to LLM agents such as ChatGPT, Claude, and Gemini. A separate **MCP Gateway** product governs AI agent traffic. Neither publishes an endpoint or tool schema.

## Artifacts

| Artifact | File | Method |
|---|---|---|
| llms.txt | `llms/linx-llms.txt` | searched (verbatim, 111 lines) |
| MCP server | `mcp/linx-mcp.yml` | searched |
| Trust center | `security/linx-trust-center.yml` | searched |
| Conformance | `conformance/linx-conformance.yml` | searched |
| Lifecycle / SLA | `lifecycle/linx-lifecycle.yml` | searched |
| Domain security | `security/linx-domain-security.yml` | probed |
| Well-known | `well-known/linx-well-known.yml` | searched (no documents found) |

## Compliance

SOC 2 Type II, SOC 1, ISO 27001:2022, ISO 42001, HIPAA, and GDPR — all listed as fully implemented on the Scytale-hosted trust center, with SOC reports and a 2026 pen-test confirmation available on request.

## Not published

No status page, changelog, roadmap, pricing page, public SDKs, CLI, sandbox, webhooks/AsyncAPI, security.txt, or vulnerability disclosure program were found. These are recorded as honest absences, not gaps to be filled with fabricated artifacts.
