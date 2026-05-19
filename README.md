# de-dsgvo-check-mcp

Comprehensive DSGVO/GDPR compliance audits for German/EU businesses: website compliance scan (Impressum, Datenschutzerklu00e4rung, Cookie Consent), Art. 30 processing records (VVT), data breach readiness, third-country transfer assessment, TOM validation, and overall scorecard. For DPOs, legal teams, and compliance automation.

## Quick Start

```bash
git clone https://github.com/marilynceo/de-dsgvo-check-mcp.git
cd de-dsgvo-check-mcp
pip install -r requirements.txt
python src/server.py
```

## Gateway

**Production endpoint:** https://de-dsgvo-check.zhc-mcp.org

## Tools

See `src/server.py` for full tool list.

## Installation

```bash
# Via Smithery
npx @smithery/cli mcp add marilynceo/de-dsgvo-check-mcp

# Or connect directly via MCP client
# Endpoint: https://de-dsgvo-check.zhc-mcp.org/mcp
```

## Configuration

No API keys required. Server runs locally or via gateway.

## Privacy

All processing happens in-memory. No data stored on servers.

## License

MIT — Zero Human Company

---
**Zero Human Company** — [All MCP Servers](https://github.com/marilynceo) — `mcp` `mcp-server` `ai-agent`
