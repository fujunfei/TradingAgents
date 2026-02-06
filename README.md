## TradingAgents

这个仓库用于沉淀一套“多角色（Macro / Fundamentals / Valuation / Technical / Risk / Odds）”的资产与行业研究工作流，并在 `TradingAgents/research-notes/` 中持续保存每次分析输出的研究记录。

### 目录结构

- `.cursor/skills/asset-industry-analysis/`: 资产/行业分析 Skill（输出模板 + 工作流）
- `.cursor/rules/agent.mdc`: 薄层规则（触发与硬约束）
- `research-notes/`: 每次分析的落盘记录（`{资产名}-{YYYY-MM-DD}.md`）

### 使用方式（示例）

在 Cursor 对话中直接说：

- “用 asset-industry-analysis 分析：XAUUSD，期限 6–12 个月，目标配置 + 波段。”
- “分析：A股-半导体设备，期限 12 个月，关注轮动与风险条件。”

输出会写入 `research-notes/` 下的新文件，并在聊天中回传路径与摘要。

