# awesome-sre-skills

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of AI-SRE skills, MCP servers, and resources for building autonomous reliability into engineering organizations.

Maintained by [Anyshift](https://www.anyshift.io). We're building the AI-SRE skills category and tracking what good looks like here.

## Contents

- [Skill libraries](#skill-libraries)
- [MCP servers for SRE](#mcp-servers-for-sre)
- [Reading](#reading)
- [Related awesome lists](#related-awesome-lists)
- [Contributing](#contributing)

## Skill libraries

Methodology-shaped skills for AI agents working on reliability: incident investigation, change-impact analysis, oncall handover, postmortem authoring, reliability audits.

- [anthropics/skills](https://github.com/anthropics/skills) - Anthropic's reference repository of Agent Skills using the SKILL.md folder format that agents discover and load on demand.
- [anthropics/claude-cookbooks](https://github.com/anthropics/claude-cookbooks) - Anthropic's collection of notebooks and recipes for agentic workflows and tool use that reliability agents can build on.
- [anyshift-io/sre-skills](https://github.com/anyshift-io/sre-skills) - Apache 2.0 library of methodology-shaped SRE skills published by Anyshift.
- [openai/skills](https://github.com/openai/skills) - OpenAI's reference collection of agent skills with operational examples.

## MCP servers for SRE

Model Context Protocol servers that give AI agents access to the systems oncall engineers actually use.

- [Datadog MCP Server](https://docs.datadoghq.com/mcp_server/setup/) - Datadog's official remote MCP server exposing logs, metrics, traces, monitors, and incidents to AI clients.
- [GitHub MCP Server](https://github.com/github/github-mcp-server) - GitHub's official MCP server giving agents access to repositories, issues, pull requests, and Actions for change context.
- [Grafana MCP Server](https://github.com/grafana/mcp-grafana) - Grafana's official MCP server exposing dashboards, Prometheus and Loki queries, and alerting to AI agents.
- [incident.io Remote MCP Server](https://docs.incident.io/ai/remote-mcp) - incident.io's official remote MCP server for querying incidents, alerts, on-call schedules, and post-mortems.
- [Kubernetes MCP Server](https://github.com/containers/kubernetes-mcp-server) - An MCP server for Kubernetes and OpenShift that lets agents inspect and manage cluster resources.
- [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers) - The official reference and community index of MCP servers for connecting agents to operational systems.
- [PagerDuty MCP Server](https://github.com/PagerDuty/pagerduty-mcp-server) - PagerDuty's official MCP server exposing incidents, services, and on-call schedules to MCP clients.
- [Rootly MCP Server](https://github.com/Rootly-AI-Labs/rootly-mcp-server) - Rootly AI Labs MCP server exposing incident-management tools and example incident-responder skills.
- [Sentry MCP Server](https://github.com/getsentry/sentry-mcp) - Sentry's official MCP server for querying errors, issues, and performance data during investigations.
- [tessl.io/registry](https://tessl.io/registry) - Searchable registry of MCP servers covering observability, ticketing, and adjacent SRE tooling.

## Reading

Curated reading that shaped how the AI-SRE category thinks.

- [Equipping agents for the real world with Agent Skills](https://www.anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills) - Anthropic's engineering write-up on the Agent Skills format and the progressive-disclosure design behind skill libraries.
- [How Complex Systems Fail](https://how.complexsystems.fail/) - Richard Cook's 18-point treatise on failure in complex systems, a core reference for incident analysis.
- [Site Reliability Engineering (Google SRE Book)](https://sre.google/sre-book/table-of-contents/) - Google's foundational SRE book, free online, defining error budgets, SLOs, and on-call practice.
- [The Site Reliability Workbook](https://sre.google/workbook/table-of-contents/) - Google's companion volume with practical SRE implementation guidance, free online.

## Related awesome lists

- [awesome-ai-sre](https://github.com/agamm/awesome-ai-sre) - A curated list of AI-powered tools, agents, and resources for Site Reliability Engineering.
- [awesome-AIOps](https://github.com/OpsPAI/awesome-AIOps) - A curated list of academic research and industrial materials on AI for IT operations.
- [awesome-incident-response](https://github.com/meirwah/awesome-incident-response) - A curated list of tools and resources for incident response.
- [awesome-observability](https://github.com/adriannovegil/awesome-observability) - A curated list of observability tools, platforms, and learning resources.
- [awesome-sre](https://github.com/dastergon/awesome-sre) - Dastergon's curated list of Site Reliability and Production Engineering resources.
- [awesome-sre-agents](https://github.com/last9/awesome-sre-agents) - Last9's curated list of AI-powered DevOps and SRE agents and tooling.
- [awesome-sre-tools](https://github.com/SquadcastHub/awesome-sre-tools) - Squadcast's curated list of Site Reliability and Production Engineering tools.
- [howtheysre](https://github.com/upgundecha/howtheysre) - A curated collection of publicly available resources on how organizations practice SRE.

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md). Open a PR adding your entry to the right section with a one-sentence description.

## License

[Apache 2.0](./LICENSE).
