# Security

## Reporting a vulnerability

Please report a vulnerability privately, never in a public issue:

- through GitHub: **Security → Report a vulnerability** in this repository, or
- by e-mail to admin@only-mcp.com

Include what you found, how to reproduce it and what an attacker could reach with it. Please do not access other
people's data and do not run tests that degrade the service for others.

## Scope

- the website and dashboard at https://only-mcp.com
- the MCP endpoint `https://only-mcp.com/api/mcp` and its OAuth flow
- the `onlymcp` CLI on npm

Remote MCP servers that users connect through the OnlyMCP gateway belong to their own operators; please report
issues in those servers to them.

There is no bug bounty programme. How OnlyMCP stores and protects data: https://only-mcp.com/docs/security
