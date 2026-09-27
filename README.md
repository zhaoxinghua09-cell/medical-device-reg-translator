# MedXpert 医械法规翻译助手
## 许可说明 · License Notice

- **权利状态**：本仓库以 **MIT 许可** 许可发布，可依该许可证条款自由使用、修改与再分发。
- **引用建议**：引用时请标注仓库名与原文链接 `https://github.com/zhaoxinghua09-cell/medical-device-reg-translator`
  与权利人「赵兴华 / Steven Zhao·China」。
- **品牌状态限定**：MedXpert、SynomosAI、LGD 等为相关项目标识，
  **均未申请实体注册、未申请商标注册**；出现仅作来源标识，
  不构成对法人实体或商标权的任何主张。
- **完整条款**：见仓库根目录 [LICENSE](LICENSE)。
- **联系**：zhaoxinghua06@126.com ｜ ORCID 0009-0001-0512-1237

---


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
