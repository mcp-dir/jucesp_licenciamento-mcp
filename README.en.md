# JUCESP: Consulta Pública de Licenciamento

### JUCESP: Consulta Pública de Licenciamento for Claude, ChatGPT and AI agents

Public business licensing lookup at the São Paulo Board of Trade (JUCESP) by CNPJ. Platform-hosted, no credentials, pay per query with prepaid credit.

- 📊 **1 tool**
- 🔒 **Read-only**
- 💬 **Works with any MCP client**: Claude Desktop, Cursor, VS Code, Cline, Continue
- 🔑 **Magic-link login (no password)**

[Portuguese version](README.md) · [Full docs (PT-BR)](docs/)

---

## One-click install

### Claude (Web and Desktop)

[➕ Open in Claude and connect](https://claude.ai/new?modal=add-custom-connector#settings/customize-connectors)

Manual: [claude.ai/customize/connectors](https://claude.ai/customize/connectors?surface=cowork) → **+** → **Add custom connector** → name `JUCESP: Consulta Pública de Licenciamento`, URL `https://api.mcp.ai/p_jucesp_licenciamento`.

### Cursor

[➕ Install in Cursor](cursor://anysphere.cursor-deeplink/mcp/install?name=jucesp_licenciamento&config=eyJ1cmwiOiJodHRwczovL2FwaS5tY3AuYWkvcF9qdWNlc3BfbGljZW5jaWFtZW50byJ9)

### VS Code (Copilot Chat)

[➕ Install in VS Code](vscode:mcp/install?name=jucesp_licenciamento&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fapi.mcp.ai%2Fp_jucesp_licenciamento%22%7D)

### Any other MCP-over-HTTP client

```
https://api.mcp.ai/p_jucesp_licenciamento
```

---

## 1 tool

| Tool | Description |
|---|---|
| `jucesp_licenciamento_consultar` | Consulta pública de licenciamento de uma empresa na Junta Comercial de São Paulo (JUCESP) pelo CNPJ. |

---

## Pricing

See [docs/precos.md](docs/precos.md) (PT-BR).

---

## License

MIT — see [LICENSE](LICENSE). The MCP server at `api.mcp.ai/p_jucesp_licenciamento` is proprietary (hosted); this repo (manifests, docs, skills) is MIT.
