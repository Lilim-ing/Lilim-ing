# 李明辉

会员数据分析 / 增长分析方向。  
关注怎么把 Agent 做成**可信、可评测、可治理、可接入**的系统，而不只是能跑通的 demo。

> Member growth analytics · building trustworthy, evaluable, governable LLM agents.

## 作品集

[Agent Portfolio · 会员增长智能体工程](https://github.com/Lilim-ing/agent-portfolio)

六个可独立运行、可离线评测的 Agent 工程。领域取自服装/内衣会员运营，数据全部为合成数据。

| 项目 | 一句话 | 关键机制 |
|---|---|---|
| [membergraph](https://github.com/Lilim-ing/membergraph) | 会员增长多智能体工作台 | 证据账本 / Critic 回路 / 预算降级 / trace 回放 |
| [metricguard](https://github.com/Lilim-ing/metricguard) | 指标口径守卫与可信问数网关 | 语义层 / AST 策略 / PII 拦截 / 审计 |
| [agent-evalkit](https://github.com/Lilim-ing/agent-evalkit) | Agent 评测与回归工具包 | trace-first 断言 / bootstrap CI / flaky 检测 |
| [uplift-copilot](https://github.com/Lilim-ing/uplift-copilot) | 增量建模与预算分配 | T-learner / Qini / 预算约束选人 |
| [fitwise](https://github.com/Lilim-ing/fitwise) | 内衣尺码与穿着知识助手 | 确定性尺码 / 引用式检索 / 默认拒答 |
| [mcp-member-ops](https://github.com/Lilim-ing/mcp-member-ops) | 会员运营 MCP 服务 | JSON-RPC / RBAC / 返回层脱敏 / 审计 |

## 我关注的三件事

- **结论可追溯**：每条结论挂证据，不靠 prompt 祈使句。
- **口径可治理**：指标定义是可执行契约，不是文档里的注释。
- **质量可证明**：断言对象是 trace，评测能进 CI 门禁。

## 技术栈

Python · SQL · DuckDB · pandas · scikit-learn · LLM Agents · MCP · GitHub Actions

---

> 所有项目使用合成数据，不含任何企业的真实数据、真实会员信息或真实口径文档。
