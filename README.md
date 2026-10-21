# 李明辉

会员数据分析 / 增长分析。

下面几个项目是从日常工作里反复卡住的地方拆出来的：Agent 给出的结论怎么核对，指标口径为什么每个渠道算出来都不一样，评测怎么才能进 CI 而不是靠人看报告。领域用服装 / 内衣会员运营，数据全部合成。

## 作品集

[Agent Portfolio · 会员增长智能体工程](https://github.com/Lilim-ing/agent-portfolio)

六个项目都能离线跑，不需要 API key。

| 项目 | 做什么 | 主要实现 |
|---|---|---|
| [membergraph](https://github.com/Lilim-ing/membergraph) | 会员增长多智能体工作台 | 黑板版本化 / 证据账本 / Critic 打回 / 预算降级 / trace 回放 |
| [metricguard](https://github.com/Lilim-ing/metricguard) | 指标口径守卫、可信问数网关 | 语义层 YAML / sqlglot AST 策略 / PII 拦截 / 审计 |
| [agent-evalkit](https://github.com/Lilim-ing/agent-evalkit) | Agent 评测与回归 | trace 断言 / bootstrap 置信区间 / flaky 检测 |
| [uplift-copilot](https://github.com/Lilim-ing/uplift-copilot) | 增量建模与预算分配 | T-learner / Qini / 预算约束选人 |
| [fitwise](https://github.com/Lilim-ing/fitwise) | 内衣尺码与穿着知识助手 | 确定性尺码计算 / 引用式检索 / 默认拒答 |
| [mcp-member-ops](https://github.com/Lilim-ing/mcp-member-ops) | 会员运营 MCP 服务 | JSON-RPC / 能力级 RBAC / 返回字段脱敏 / 审计 |

## 技术栈

Python · SQL · DuckDB · pandas · scikit-learn · LLM Agents · MCP · GitHub Actions

---

> 仓库数据全部合成，没有真实企业数据、会员信息或口径文档。
