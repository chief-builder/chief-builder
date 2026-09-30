# Murali Kurukunda

**Engineering executive who still builds.** By day I lead enterprise platform teams that run API, foundation-model, and MCP gateways at large scale, connecting agents to enterprise systems. On my own time I build and measure the pieces that make agents safe to run with real data and real permissions.

What I work on here:

- **Agent identity and permissions.** Agents that act as the signed-in person, with scoped, auditable access and no shared tokens.
- **Evidence over opinion.** Controlled, repeatable experiments on agentic harnesses, not demo videos.
- **Governance you can run.** Validators, registries, and rollout gates that let an enterprise say yes to agents safely.
- **Modernization with agents.** Agent teams that map, test, and migrate legacy codebases, built on lessons from leading large migrations. See [modernization-agent](https://github.com/chief-builder/modernization-agent).

## Featured

| Repo | What it shows |
|---|---|
| [mcp-healthcare-reference](https://github.com/chief-builder/mcp-healthcare-reference) | A lab for an enterprise MCP platform: multi-IdP identity hub, a three-tier Kong gateway, certificate-bound machine identity, stateless MCP servers over synthetic FHIR, and a vault-backed token broker for SaaS egress. |
| [vendor-token-broker](https://github.com/chief-builder/vendor-token-broker) | An MCP gateway that lets Claude Code and other assistants use GitHub, Linear, Jira, and Cloudflare as each signed-in person, with no one handling tokens and read-only tools by default. |
| [cli-vs-mcp](https://github.com/chief-builder/cli-vs-mcp) | Claude Code across baseline, CLI-skill, and MCP tool surfaces with paired seeds and N=5 trials. One well-designed MCP primitive cut workflow-status turns from 60 to 8. |
| [local-vs-remote-mcp](https://github.com/chief-builder/local-vs-remote-mcp) | Local stdio vs. remote streamable-HTTP MCP: token cost, latency, and prompt-injection exposure, with transport isolated from server implementation. |
| [mcp_tool_description_validator](https://github.com/chief-builder/mcp_tool_description_validator) | 57 rules for MCP tool definitions covering LLM compatibility, security, and spec compliance. CLI, HTTP service, and SARIF output for CI. |
| [codex_rollout_healthcare](https://github.com/chief-builder/codex_rollout_healthcare) | An executive rollout plan for a governed AI coding platform in regulated healthcare: gateway policy, identity claims, metering, chargeback, and explicit rollout gates. |

## More

- **Research:** [codex-local-vs-remote-mcp](https://github.com/chief-builder/codex-local-vs-remote-mcp) (same transport question with the Codex CLI) · [cc-combo-bench](https://github.com/chief-builder/cc-combo-bench) (48-run benchmark of orchestrator/implementer configurations)
- **Platform:** [mcp-sub-registry](https://github.com/chief-builder/mcp-sub-registry) (internal MCP registry with approval and audit) · [mcp-taskflow](https://github.com/chief-builder/mcp-taskflow) (MCP reference server with OAuth 2.1 and role-based access)
- **Agents:** [claweb](https://github.com/chief-builder/claweb) (MCP servers, clients, and agents up to multi-server OAuth 2.1) · [modernization-agent](https://github.com/chief-builder/modernization-agent) (Claude Agent SDK multi-agent codebase modernization) · [openapi-mcp-generator](https://github.com/chief-builder/openapi-mcp-generator)

## Elsewhere

- NYSE panel on enterprise AI connectivity, with Kong, McKinsey, and Mistral AI
- Earlier talks: InfoQ (real-time CQRS cache for banking), Dashcon 2018 (serverless statements engine), Rackspace Solve
- [LinkedIn](https://linkedin.com/in/mkurukunda)

<sub>Code and opinions here are my own and don't represent my employer.</sub>
