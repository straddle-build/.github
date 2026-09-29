# Straddle Build

Open-source developer tools for [Straddle](https://straddle.com)'s Pay by Bank and Embed APIs. This organization publishes the Straddle CLI, official SDKs, and agent skills. For API concepts and endpoint reference, see the [Straddle docs](https://docs.straddle.com).

## Get started

Install the CLI, then run `straddle doctor` to check your API key and environment:

```sh
brew install straddle-build/tap/straddle
straddle doctor
```

The CLI defaults to the sandbox environment. For other install methods, see the [CLI README](https://github.com/straddle-build/straddle-cli#install).

## CLI

[straddle-cli](https://github.com/straddle-build/straddle-cli) covers every Straddle API operation from one binary, with a human surface and an agent surface (`--agent`). It also syncs charges, payouts, customers, paykeys, and funding events to a local SQLite store for offline search, reconciliation, and return analytics.

## SDKs

Each SDK wraps the full Straddle API for one language:

| Language | Repository | Install |
| --- | --- | --- |
| TypeScript | [straddle-typescript](https://github.com/straddle-build/straddle-typescript) | `npm install @straddlecom/straddle` |
| Python | [straddle-python](https://github.com/straddle-build/straddle-python) | `pip install straddle` |
| Go | [straddle-go](https://github.com/straddle-build/straddle-go) | `go get github.com/straddle-build/straddle-go` |
| Ruby | [straddle-ruby](https://github.com/straddle-build/straddle-ruby) | `gem install straddle` |
| .NET | [straddle-dotnet](https://github.com/straddle-build/straddle-dotnet) | `dotnet add package Straddle` |

## Agent skills

[skills](https://github.com/straddle-build/skills) teaches coding agents to plan, build, test, and audit a Straddle integration, check it before go-live, and migrate from another payment provider. Install the skills with the [`skills`](https://github.com/vercel-labs/skills) CLI:

```sh
npx skills add straddle-build/skills
```

## Contributing and security

To contribute, read the [contributing guide](https://github.com/straddle-build/.github/blob/main/CONTRIBUTING.md). To report a vulnerability, follow the [security policy](https://github.com/straddle-build/.github/blob/main/SECURITY.md) instead of opening a public issue.
