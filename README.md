# IaDbp

## OpenCode

USamos OpenCode

### MCP

MCP de postgresql

```json

"postgres": {
  "command": "npx",
  "args": ["-y", "@modelcontextprotocol/server-postgres", "postgresql://usuario:password@localhost:5432/tu_base_datos"]
}

```
MCP Sqlite
```json
"sqlite": {
  "command": "npx",
  "args": ["-y", "@modelcontextprotocol/server-sqlite", "--db", "C:\\Users\\blanc\\ia\\springBootEjemplo\\demo\\data\\demo.db"]
}

```
