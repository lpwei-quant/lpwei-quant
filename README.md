# 魏来平 | Investment × Mathematics

上海财经大学投资学 × 数学双学位本科生（2028 届），关注数据分析、量化研究与可复现建模。

**在找什么**：上海的数据分析 / 商业分析 / 策略分析实习 ｜ 可立即到岗 · 每周 5 天 · 可连续实习 6 个月

## 精选项目

### [Olist 电商数据 SQL 分析：漏斗、留存与 RFM](https://github.com/lpwei-quant/olist-sql-analysis)

`SQL` · `SQLite / MySQL` · `窗口函数` · `经营看板` · `分析报告`

- 对 8 张表、99,441 笔订单建模，编写 12 个查询，覆盖多表 JOIN、CTE 与 ROW_NUMBER / LAG / NTILE / SUM OVER 窗口函数。
- 关键结论：订单签收率 97.02%；配送 21 天以上订单差评率 38.18%，为 7 天内的 5.1 倍；复购率 3.12%；Top10 卖家仅贡献 12.8% 的 GMV。
- 先做数据质量体检再分析（评论标题缺失 88%、2,965 笔订单无签收时间），配套经营看板与 3 页分析报告，全流程可用 `node run.mjs` 一键复现。

### [微网购电与储能调度：预测不确定性下的策略分析](https://github.com/lpwei-quant/modeling-analytics-portfolio/tree/main/projects/microgrid-2026)

`2026 年正式竞赛` · `策略比较` · `费用拆分` · `结果验证`

- 基于 334 日历史回放比较日前计划、日内反馈与合同调整，统一核算费用和末库存。
- 审查充放电约束并推动模型重做，保留显式互斥对照及信息条件；个人侧重方案审查、研究推进和成果整理。
- [六页作品集 PDF](https://github.com/lpwei-quant/modeling-analytics-portfolio/blob/main/output/pdf/modeling-analytics-portfolio.pdf) · [研究记录与复现代码](https://github.com/lpwei-quant/modeling-analytics-portfolio)

### [农业种植规划：收益与风险的情景分析](https://github.com/lpwei-quant/modeling-analytics-portfolio/tree/main/projects/agriculture-2024)

`2026 年 8 月赛题训练` · `2024 C 题` · `情景分析` · `下尾风险`

- 覆盖 54 个地块、41 种作物，区分 60 个优化情景与 3000 条模拟样本外评价路径。
- 在统一相关风险环境下比较冻结方案，保留扩展模型未超过基线的结果；明确模拟条件与 AI 辅助范围。

### [沪深 300 收益率与极端交易日研究](https://github.com/lpwei-quant/quant-research-2026)

`Python` · `pandas` · `NumPy` · `Matplotlib` · `pytest`

- 检查沪深 300 价格指数历史行情的数据类型、缺失值、重复日期与时间顺序。
- 分别计算简单收益率与对数收益率，以两条数学等价路径重构净值并交叉验证。
- 分析极端交易日，同时说明价格指数不含股息再投资、收盘收益不代表日内路径等口径限制。

### [AI Financial News Agent](https://github.com/lpwei-quant/AI-Financial-News-Agent)

`Python` · `API` · `JSON` · `LLM workflow`

- 学习型工程项目：采集金融新闻和市场行情，筛选新闻并生成结构化分析结果。
- 包含日报保存、人工审核与评估脚本；外部 API 的端到端运行状态仍待刷新验证。

### [高等代数交互式学习平台](https://github.com/lpwei-quant/linear-algebra-learning-platform)

`React` · `Vite` · `Three.js` · `KaTeX`

- 通过交互式动画呈现向量空间、线性变换、特征值、二次型与 PCA 等概念。
- 仓库包含自动测试、构建流程与 Vercel 配置；项目文档与贡献边界仍在整理。

## 持续学习

### [机器学习学习记录](https://github.com/lpwei-quant/machine-learning-journey)

`Python` · `scikit-learn` · `数据审计` · `学习进度`

- 整理 Digits 分类与误分类分析、House Prices 数据入门、CreditRisk Lab 数据审计，以及 SVM / 逻辑回归复述记录。
- 当前主线为信用数据审计；房价回归和信用评分模型尚未训练。提供实际运行结果、复现代码与明确的学习停点。
- [当前进度与下次入口](https://github.com/lpwei-quant/machine-learning-journey/blob/main/PROGRESS.md)

## 当前能力

- 数据处理：Python、pandas、NumPy、Matplotlib、openpyxl
- SQL：MySQL 8 / SQLite，多表 JOIN、子查询、CTE、窗口函数
- 分析方法：数据清洗、口径定义、聚合、统计分析与结果交叉校验
- 建模实践：数学规划、Monte Carlo 模拟、分类模型评估与风险度量
- 工程工具：Git、GitHub、基础前端与 API 集成；AI Agent 工具辅助分析流程

## 正在做什么

- 继续完善可复现的数据分析与金融数据项目
- 学习计量经济学、数据挖掘与机器学习
- 寻找数据分析、商业分析、策略运营与 FinTech 相关实习机会

## 联系方式

- 学校邮箱：2024111285@stu.sufe.edu.cn
