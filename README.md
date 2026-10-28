<div align="center">

<a href="https://only-mcp.com"><img src=".github/assets/banner.jpg" alt="OnlyMCP: One MCP. Every device." width="100%"></a>

### Your skills, agents and memory in the cloud, the same in every AI client on every device.

[![Website](https://img.shields.io/badge/only--mcp.com-website-a78bc9?style=flat-square&logo=googlechrome&logoColor=white)](https://only-mcp.com)
[![Docs](https://img.shields.io/badge/docs-setup%20guides-1f2937?style=flat-square&logo=readthedocs&logoColor=white)](https://only-mcp.com/docs)
[![Release](https://img.shields.io/github/v/release/Francesco070/onlymcp-community?style=flat-square&label=release&color=a78bc9)](https://github.com/Francesco070/onlymcp-community/releases/latest)
[![npm](https://img.shields.io/badge/npm-npx%20onlymcp-cb3837?style=flat-square&logo=npm)](https://www.npmjs.com/package/onlymcp)
[![MCP Registry](https://img.shields.io/badge/MCP%20Registry-com.only--mcp%2Fonlymcp-0f766e?style=flat-square)](https://registry.modelcontextprotocol.io/v0/servers?search=com.only-mcp/onlymcp)

**[Get started free](https://only-mcp.com)** · **[Docs](https://only-mcp.com/docs)** ·
**[Report a bug](https://github.com/Francesco070/onlymcp-community/issues/new/choose)** ·
**[Releases](https://github.com/Francesco070/onlymcp-community/releases)**

[![X](https://img.shields.io/badge/X-@OnlyMCP-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/OnlyMCP)
[![Bluesky](https://img.shields.io/badge/Bluesky-@only--mcp.com-0285ff?style=flat-square&logo=bluesky&logoColor=white)](https://bsky.app/profile/only-mcp.com)
[![YouTube](https://img.shields.io/badge/YouTube-@onlymcp-ff0000?style=flat-square&logo=youtube&logoColor=white)](https://www.youtube.com/@onlymcp)
[![Instagram](https://img.shields.io/badge/Instagram-onlymcp.official-e4405f?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/onlymcp.official/)
[![Reddit](https://img.shields.io/badge/Reddit-u%2FOnlyMCP-ff4500?style=flat-square&logo=reddit&logoColor=white)](https://www.reddit.com/user/OnlyMCP/)

Works with Claude, ChatGPT, Claude Code, Codex, Cursor, Gemini CLI, Windsurf, Zed, Cline and any other MCP client.

</div>

## What OnlyMCP does

<table>
  <tr>
    <td width="50%" valign="top">
      <img src=".github/assets/memory.jpg" alt="Memory: what your agent learns becomes a linked note">
      <br><b>Memory</b><br>
      What your agent learns becomes a markdown note, linked to what it touches. Read, write, search and link it from
      any client.
    </td>
    <td width="50%" valign="top">
      <img src=".github/assets/gateway.jpg" alt="Gateway: every tool through one MCP connection">
      <br><b>Gateway</b><br>
      Connect your other remote MCP servers once. Every client reaches their tools through the same connection.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <img src=".github/assets/agents.jpg" alt="Agents: the same agent definitions on every machine">
      <br><b>Skills and agents</b><br>
      Kept once in your account, the same version on every device, loaded when a conversation needs them.
    </td>
    <td width="50%" valign="top">
      <img src=".github/assets/catalogue.jpg" alt="Catalogue: GitHub, Linear, Notion, Stripe and more">
      <br><b>Catalogue</b><br>
      Pick GitHub, Linear, Notion, Stripe and more from the catalogue, or add any remote MCP server that signs in with
      OAuth or a token.
    </td>
  </tr>
</table>

## Quick start

1. Create a free account at [only-mcp.com](https://only-mcp.com).
2. Point your client at the remote MCP server `https://only-mcp.com/api/mcp` (Streamable HTTP, OAuth 2.1).

**Claude and ChatGPT** (in developer mode): add the address as a custom connector and sign in with OAuth.

**Claude Code:** create an access token under "Connect" on the website, then run

```bash
claude mcp add --transport http --scope user onlymcp https://only-mcp.com/api/mcp \
  --header "Authorization: Bearer omk_…"
```

Setup for Codex, Cursor, Gemini CLI and every other client: [only-mcp.com/docs](https://only-mcp.com/docs). The CLI
`npx onlymcp` imports existing skills, agents and memory from your disk.

## This repository

This is OnlyMCP's public place for bug reports, feature requests and release notes. OnlyMCP is a hosted service: its
source code is private and is not in this repository.

### Report a bug or ask for a feature

[Open an issue](https://github.com/Francesco070/onlymcp-community/issues/new/choose). Issues are public, so leave
out tokens, passwords and the content of your memory files.

### Security

Please do not report a vulnerability in a public issue. [SECURITY.md](SECURITY.md) says how to report it privately.

### Account and billing

Questions about your account, your plan or an invoice: admin@only-mcp.com

### Releases

Every OnlyMCP release is listed under [Releases](https://github.com/Francesco070/onlymcp-community/releases) with
what changed.

### Follow OnlyMCP

News and updates from OnlyMCP:
[X](https://x.com/OnlyMCP) ·
[Bluesky](https://bsky.app/profile/only-mcp.com) ·
[YouTube](https://www.youtube.com/@onlymcp) ·
[Instagram](https://www.instagram.com/onlymcp.official/) ·
[Reddit](https://www.reddit.com/user/OnlyMCP/)

<div align="center">
<br>
<a href="https://only-mcp.com"><img src="https://only-mcp.com/brand/favicon.svg" width="40" alt="OnlyMCP"></a>
<br>
<sub>OnlyMCP is run from Switzerland and hosted in Europe.</sub>
</div>
