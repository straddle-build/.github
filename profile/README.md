# Straddle Build

Build Pay by Bank and Embed integrations with [Straddle](https://straddle.com). Use coding-agent skills, MCP servers, guided setup, a command-line tool, and official SDKs to connect your application to the API.

## Build with your coding agent

Start the [Straddle Wizard](https://github.com/straddle-build/wizard) from your application directory. You need Node.js 22.18 or later and a supported coding agent: Claude Code, Codex, or Cursor.

```sh
npx @straddlecom/wizard@latest
```

The Wizard helps you choose an integration and agent, install the Straddle skills, and begin the workflow. The skills guide setup, planning, implementation, sandbox testing, and a production readiness review.

To add skills to an existing agent setup, start with the [Straddle skills installation guide and catalog](https://github.com/straddle-build/skills).

## Connect your agent with MCP

Use Straddle's hosted Model Context Protocol (MCP) servers to work with documentation and the API from your coding agent:

- **Docs MCP:** Search Straddle documentation without an API key.
- **API MCP:** Discover endpoints and send requests authorized by your Straddle API key.

Follow the [MCP connection guide](https://straddle-build-straddle-openapi.apidocumentation.com/connect-mcp) to connect your client. The [Straddle plugin](https://github.com/straddle-build/skills) includes both connections alongside the integration skills.

## Choose a tool

Choose the starting point for your task.

| Task | Start here |
| --- | --- |
| Build an integration with a coding agent | [Wizard](https://github.com/straddle-build/wizard) |
| Plan, test, migrate, or audit an integration | [Skills](https://github.com/straddle-build/skills) |
| Call the API from a terminal or return JSON to an agent | [Straddle CLI](https://github.com/straddle-build/straddle-cli) |
| Search local payment records, investigate returns, or reconcile funding | [CLI data workflows](https://github.com/straddle-build/straddle-cli) |
| Install the CLI with Homebrew | [Homebrew tap](https://github.com/straddle-build/homebrew-tap) |

## Use an SDK

Choose your application's language. Each SDK README includes installation, configuration, and request examples.

| Language | SDK |
| --- | --- |
| TypeScript and JavaScript | [straddle-typescript](https://github.com/straddle-build/straddle-typescript) |
| Python | [straddle-python](https://github.com/straddle-build/straddle-python) |
| Go | [straddle-go](https://github.com/straddle-build/straddle-go) |
| Ruby | [straddle-ruby](https://github.com/straddle-build/straddle-ruby) |
| C# and .NET | [straddle-dotnet](https://github.com/straddle-build/straddle-dotnet) |

## Read the docs

Use the following guides to understand the API and plan your integration:

- [Product guides](https://docs.straddle.com/guides/overview): Learn how customers, bank connections, payments, and embedded accounts work together.
- [API reference](https://docs.straddle.com/api-reference/introduction): Find endpoints, request fields, authentication, and response formats.
- [Sandbox guide](https://docs.straddle.com/guides/resources/sandbox-paybybank): Test payment flows with sandbox data.

## Contribute or report an issue

Open usage questions and bug reports in the relevant repository. Read the [contributing guide](https://github.com/straddle-build/.github/blob/main/CONTRIBUTING.md) before submitting changes. For vulnerabilities, use the private reporting route in the [security policy](https://github.com/straddle-build/.github/blob/main/SECURITY.md).
