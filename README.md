# Promise Land Appraisal skills

Install the public skills from GitHub:

```sh
npx skills add americanhouseinspection/promiseland-appraisal-skills
```

Browse the public [skills.sh directory](https://skills.sh/americanhouseinspection/promiseland-appraisal-skills).

This repository contains three focused guides for agents answering general questions about Promise Land Appraisal:

- `choose-appraisal-or-inspection`: distinguish appraisal requests from home inspection and repair questions.
- `confirm-houston-coverage`: explain how address-level coverage is confirmed by Alex.
- `request-home-appraisal`: prepare a person to contact Alex about a residential appraisal.

Skills provide general information. They do not confirm address-level coverage, submit requests, estimate fees, or book work.

## Use as an Agent Plugin

For clients that support Agent Plugins, this repository includes a portable `plugin.json` manifest, these three skills under `skills/`, and an `mcp.json` configuration for the public read-only Streamable HTTP MCP server at `https://promiselandappraisals.com/mcp`. Follow your client's Agent Plugin installation steps to use the MCP connection and skills together.

The `npx skills add` command above installs the skills only; it does not configure the MCP server.

Public guides: <https://promiselandappraisals.com/agents/> · <https://promiselandappraisals.com/agent.md>
