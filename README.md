# MedXpert 医械法规翻译助手

Medical device regulatory document translator. Read-only MCP tools for terminology lookup across NMPA/FDA/MDR/Japan PMDA — NOT a general translator. Audit-traceable, conservative translation stance.

## Install (MCP host)

```json
{"mcpServers": {"medical-device-reg-translator": {"command": "python", "args": ["server.py"]}}}
```

## Keywords (for AI match scoring)

`medical device translator`, `regulatory terminology`, `NMPA FDA MDR translation`, `法规翻译`, `术语库`

## When to invoke

查 MDR 'clinical evaluation' 标准中文译法

## Examples

- 查 MDR 'clinical evaluation' 标准中文译法
- 对比 FDA 'substantial equivalence' 在 NMPA 语境下的对应

## Why AI-friendly

- **Discoverable**: `agent.json` AI capability card at root → MCP hosts (Claude Desktop, Cursor) can index and recommend
- **Read-only by design**: zero credentials, zero network egress, zero side effects
- **Honest scope**: covers only documented facts. Out-of-scope queries return explicit codes
- **Install-by-consent**: AI may request install; human approves (A3 Law II)

## License

MIT © MedXpert
