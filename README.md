# AMZ Agent MCP Server

> Lightweight MCP (Model Context Protocol) server that connects your Amazon business data to AI assistants like Claude Desktop.

**Coming Soon** - Under active development.

## What It Does

AMZ Agent MCP Server brings your Amazon Seller metrics directly into your AI workflow:

- **KPI Queries** - Ask natural language questions about your TACOS, ACOS, revenue, and ad spend
- **Profit Context** - ASIN-level profitability with real margin data
- **Campaign Health** - Quick campaign performance checks without opening Seller Central
- **Trend Analysis** - Period-over-period comparisons with automatic anomaly detection

## Why MCP?

MCP (Model Context Protocol) is the emerging standard for connecting AI assistants to external data sources. Instead of copy-pasting reports, your AI assistant queries your data directly — in real time.

## How It Works

```
Claude Desktop / OpenClaw / Any MCP Client
        |  (MCP Protocol)
  AMZ Agent MCP Server
        |  (Authenticated API)
    AMZ Agent Backend
        |
  Your Amazon Data (Ads, Sales, Catalog, Profit)
```

## Roadmap

- [ ] Core MCP server implementation
- [ ] Authentication flow
- [ ] KPI query tools
- [ ] Campaign performance tools
- [ ] Profit analysis tools
- [ ] Documentation

## Built By

**[Adlevate](https://adlevate.de)** — Amazon PPC Agency building AI-powered tools for sellers and agencies.

## License

MIT
