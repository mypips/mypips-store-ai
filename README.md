# mypips store AI

Skills and MCP setup that let AI agents open and run a mypips store. The agent guides the owner through signup,
connects to the store with the owner's approval (OAuth, no keys in chat), and helps set up the profile,
categories, products and home page.

Claude Code:

```
/plugin marketplace add mypips/mypips-store-ai
/plugin install mypips@mypips-store-ai
```

Codex:

```
codex plugin marketplace add mypips/mypips-store-ai
```

Gemini CLI:

```
gemini extensions install https://github.com/mypips/mypips-store-ai
```

Other agents:

```
npx skills add mypips/mypips-store-ai
```

MCP server: `https://mcp.mypips.app/mcp/merchant`

Privacy: https://mypips.co.il/privacy
