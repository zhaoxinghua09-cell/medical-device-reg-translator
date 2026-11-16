# MedXpert 医械法规翻译助手

> **Status (2026-11-16, updated): this pack is an expert/agent card, not a server — and the connector it depends on now exists.** `medxpert-ortho-mcp` 0.1.1 is published: on PyPI (wheel + sdist), in the official MCP Registry (`isLatest: true`, published 2026-11-16T12:56:07Z), and verified by a real `uvx` handshake returning 8 tools. Install it first:
>
> ```bash
> uvx medxpert-ortho-mcp
> ```
>
> The tools run over **illustrative sample data** and say so in every result; point `ORTHO_DATA_DIR` at your own datasets for real work. This repository still ships no `server.py` — it is a card that a host loads, and the capability lives in the connector.
>
> **状态（2026-11-16 更新）：本包是专家/Agent 卡片，不是服务；它所依赖的连接器现在真的存在了。**`medxpert-ortho-mcp` 0.1.1 已发布：PyPI（wheel + sdist）、官方 MCP Registry（`isLatest: true`，发布于 2026-11-16T12:56:07Z），并由真实 `uvx` 安装握手验证——返回 8 个工具。先安装它：
>
> ```bash
> uvx medxpert-ortho-mcp
> ```
>
> 工具跑在**示例数据**上，且每个返回值都会说明这一点；正式使用请把 `ORTHO_DATA_DIR` 指向你自己的数据集。本仓仍然没有 `server.py`——它是宿主加载的卡片，能力在连接器里。

## 许可说明 · License Notice

- **权利状态**：本仓库以 **MIT 许可** 许可发布，可依该许可证条款自由使用、修改与再分发。
- **引用建议**：引用时请标注仓库名与原文链接 `https://github.com/zhaoxinghua09-cell/medical-device-reg-translator`
  与权利人：© 2026 赵兴华 / Steven Zhao (ORCID 0009-0001-0512-1237). All rights reserved.
- **品牌状态限定**：MedXpert、SynomosAI、LGD 等为相关项目标识，
  **均未申请实体注册、未申请商标注册**；出现仅作来源标识，
  不构成对法人实体或商标权的任何主张。
- **完整条款**：见仓库根目录 [LICENSE](LICENSE)。
- **联系**：zhaoxinghua06@126.com ｜ ORCID 0009-0001-0512-1237

---


Medical device regulatory document translator. Read-only MCP tools for terminology lookup across NMPA/FDA/MDR/Japan PMDA — NOT a general translator. Audit-traceable, conservative translation stance.

## Install (MCP host)

```text
# No MCP host configuration is available yet: this repository ships no server entry.
# The connector it was meant to call, medxpert-ortho-mcp, is not published anywhere.
# 暂无 MCP 宿主配置：本仓没有 server 入口，它本应调用的 medxpert-ortho-mcp 也尚未发布。
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

代码许可 (code license) : MIT (see LICENSE)
© 2026 赵兴华 / Steven Zhao (ORCID 0009-0001-0512-1237). All rights reserved.
