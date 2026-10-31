<p align="center">
  <a href="https://upty.io"><img src="https://raw.githubusercontent.com/uptyio/.github/main/profile/assets/upty.png" alt="Upty" width="72" height="72" /></a>
</p>
<h1 align="center">Upty</h1>
<p align="center"><strong>Less checking. More knowing.</strong></p>
<p align="center">A clear view of your websites, APIs, servers and background jobs.</p>
<p align="center">
  <a href="https://upty.io">Website</a> ·
  <a href="https://upty.io/docs">Documentation</a> ·
  <a href="https://upty.io/docs/api/reference">API reference</a> ·
  <a href="https://upty.io/docs/mcp">MCP guides</a>
</p>

## Keep your whole stack in view

Upty brings availability checks, host metrics, alerts and public status pages into one monitoring workspace. Follow an interruption from the first signal to recovery, and keep your team and customers informed.

- **Check your services:** HTTP, APIs, ping, TCP ports, IP addresses and DNS.
- **Watch the details:** certificate expiry, domain renewals, host resources, logs and scheduled-job heartbeats.
- **Stay informed:** email and Telegram notifications, maintenance windows and incident updates.
- **Work together:** workspace roles, monitor groups and customer-facing status pages.

## Build with Upty

| Project | Start here |
| --- | --- |
| **[Upty platform](https://upty.io)** | Monitor services, investigate issues and share status updates. |
| **[Claude Code plugin](https://github.com/uptyio/mcp)** | Connect your assistant through OAuth and work with your monitoring workspace. |
| **[REST API](https://upty.io/docs/api/reference)** | Build integrations with bearer API keys, ownership checks and plan limits. |
| **[Documentation](https://upty.io/docs)** | Setup guides, monitoring concepts, API reference and MCP workflows. |

## Quick start: Claude Code

```sh
claude plugin marketplace add uptyio/mcp
claude plugin install upty@upty
```

Open `/mcp` in Claude Code, select **upty** and authenticate. Sign in to Upty, choose your workspace and approve **Read-only** or **Full access**. The connection stays within your current role and workspace plan.

[Connection guide](https://upty.io/docs/mcp/connect-your-assistant) · [Tools](https://upty.io/docs/mcp/tools) · [Example prompts](https://upty.io/docs/mcp/examples)

## Quick start: the API

Create a read-only key under **Integration & API → API keys**, then:

```sh
curl https://upty.io/api/monitors \
  -H "Authorization: Bearer $UPTY_API_KEY"
```

API keys are separate from OAuth MCP connections. See [API authentication](https://upty.io/docs/account/api-keys) for scopes and access requirements.

## Get help or share an idea

- **Using Upty:** start with the [documentation](https://upty.io/docs) or open a [support ticket](https://upty.io/app/support).
- **Plugin bugs and ideas:** open an issue in [uptyio/mcp](https://github.com/uptyio/mcp/issues).
- **Private or security-sensitive reports:** contact [root@upty.io](mailto:root@upty.io). Keep credentials and private monitoring data out of public issues.

The public MCP plugin is [MIT licensed](https://github.com/uptyio/mcp/blob/main/LICENSE). The hosted platform and backend are maintained separately.
