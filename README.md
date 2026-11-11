# hedwigai for Cursor

The system of record for your agent. Your agent keeps its work in hedwigai workbooks: documents it reads and writes, with the source of every line and every version kept. Claude, ChatGPT, Cursor or any other assistant can open a workbook later and carry on.

## What you get

- **MCP server** `https://mcp.hedwigai.com` (streamable HTTP). Tools to search, read, write and create workbooks, save sources, and start research runs.
- **Skill** `hedwigai-workbooks`: tells the agent when to keep work in a workbook and how.

## Setup

1. Install the plugin from the Cursor Marketplace.
2. The first time the agent calls a hedwigai tool, Cursor opens a sign-in page. Sign in or create a free account at [hedwigai.com](https://www.hedwigai.com). There is no API key to paste.

## Try it

Say to the agent:

> Keep this in a hedwigai workbook.

> List my hedwigai workbooks.

> Read my "competitors" workbook and add the three companies we found today.

## Pricing

Reading, searching and writing workbooks is free. Research runs use credits. See [hedwigai.com/agents](https://www.hedwigai.com/agents).

## Links

- Docs: https://www.hedwigai.com/agents
- MCP Registry: `com.hedwigai/hedwigai`
- Support: shashank@hedwigai.com
