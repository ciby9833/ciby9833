<!-- 封面徽章 -->
<p align="center">
  <img src="https://img.shields.io/badge/Role-Product%20Manager-4B8BFF" />
  <img src="https://img.shields.io/badge/Focus-Geo%20API%20%7C%20Billing%20Platform%20%7C%20Logistics%20AI-blueviolet" />
  <img src="https://img.shields.io/badge/Location-🌏%20Jakarta%20%7C%20Shanghai-brightgreen" />
</p>

<h1 align="center">Hi, I'm Xavier Wu，中文名 (吴川) 👋</h1>
<p align="center">
  Product Manager | Geo Data & AI Platform | Logistics Intelligence
</p>

---

## 🧭 About Me
从现实世界的业务痛点出发，我专注于推动产品的商业化落地与 AI 工程化转化。  
擅长将复杂的地理数据、API 与商业模型融合，打造可规模化、可复用的平台能力，驱动实际业务增长与高效自动化。

💡 **核心方向：**
- 东南亚地理信息系统（GIS）与地址标准化  
- 阶梯计费与后付费账单体系  
- 基于历史业务量产能预测与排班  
- AI 驱动的地址识别与业务自动化  
- AI 工程化、结果导向转化与商业落地  

---

## 🚀 Featured Projects

### 🗺️ GistMap — Geocoding & Billing Platform
**定位**：开放式地理编码平台 + 按量计费系统  
**主要功能**：
- 地址 ↔ 坐标互转（支持多语言）  
- 按调用次数阶梯计费 / 专属定价 / VIP 宽限期  
- 余额账户、赠送额度、账单明细、信用扣费  
**技术栈**：NestJS · PostgreSQL + PostGIS · TypeScript  
**成果**：
- 费用相比Google便宜 20%以上
- 平均延迟控制在 80ms 内  
- 支持上亿次 API 调用 / 月  
- 实现可视化账单与 UTC 计费周期  
🔗 [查看仓库](https://github.com/ciby9833/GistMap)

---

### 📦 CargoTranslator — 地址清洗与结构化系统
**定位**：将混乱的物流地址转换为可分析的地理数据  
**主要功能**：
- 中文/印尼语混合地址解析、模糊匹配  
- 行政区划层级映射（省-市-区-镇）  
- 与 Geocode API、客户表联动  
**技术栈**：Python · pandas · FastAPI · DuckDB  
**成果**：
- 异常地址识别准确率提升 92% → 99%
- 人工地址映射两周工作量降低为十几分钟完成
🔗 [查看仓库](https://github.com/ciby9833/translator/tree/main/frontend/src)

---

### 💳 Billing Engine — 阶梯计费与账单系统
**定位**：兼容多 SKU、多用户定价的通用计费引擎  
**亮点功能**：
- 支持“累进阶梯”与“用户专属定价”  
- UTC 自然月账期、宽限期与信用扣费  
- 账单展示与余额流水  
**主要逻辑**：
- 原始费用按阶梯累计，结果向上取整到分（防亏损）  
- 信用额度与余额分开扣减、实时账单生成  
**成果**：
- 完全兼容 OpenAI / Google Cloud 的后付费模式  
🔗 [查看文件](https://github.com/ciby9833/GistMap/blob/main/backend-node/src/billing/pricing-engine.service.ts)

---

### 🚚 Courier Scheduling & Capacity Model
**定位**：快递网点排班与产能匹配系统  
**逻辑模型**：
1. 以快递员岗位 + 历史出勤构建排班表  
2. 每日计算计划出勤率、实际出勤率、排班准确率  
3. 结合车辆类型能力模型计算预计产能差距  
4. 输出产能-业务差距告警  
**产能公式**：
- 预计产能 = 班次数量 × 人均效率 × 车辆系数  
- 人均效率 = 近 N 天件量 ÷ 近 N 天人天  
- 车辆系数 = 车型单班产能 ÷ 平均产能  
🔗 [需求文档概览](#)

---

## 🧠 AI Projects Snapshot
<div align="center">
  <img src="https://github.com/ciby9833/ciby9833/blob/main/iloveimg-compressed%20(2)/ai1.png" width="30%" />
  <img src="https://github.com/ciby9833/ciby9833/blob/main/iloveimg-compressed%20(2)/ai2.png" width="30%" />
  <img src="https://github.com/ciby9833/ciby9833/blob/main/iloveimg-compressed%20(2)/ai3.png" width="30%" />
</div>
<p align="center"><sub>AI 模型可视化识别与自动化场景示意</sub></p>

## 🗺️ GIS Projects Snapshot
<div align="center">
  <img src="https://github.com/ciby9833/ciby9833/blob/main/iloveimg-compressed/gis1.png" width="30%" />
  <img src="https://github.com/ciby9833/ciby9833/blob/main/iloveimg-compressed/gis2.png" width="30%" />
  <img src="https://github.com/ciby9833/ciby9833/blob/main/iloveimg-compressed/gis3.png" width="30%" />
  <img src="https://github.com/ciby9833/ciby9833/blob/main/iloveimg-compressed/gis4.png" width="30%" />
  <img src="https://github.com/ciby9833/ciby9833/blob/main/iloveimg-compressed/gis5.png" width="30%" />
</div>
<p align="center"><sub>GIS 空间分析与聚类等模型展示</sub></p>

---

## 🧩 Tech & Product Skillset
<p>
  <img src="https://img.shields.io/badge/Product-JTBD%20%7C%20Roadmap%20%7C%20PRD-blue" />
  <img src="https://img.shields.io/badge/Data-PostgreSQL%20%7C%20DuckDB%20%7C%20PostGIS-orange" />
  <img src="https://img.shields.io/badge/Backend-NestJS%20%7C%20Node.js%20%7C%20FastAPI-lightgrey" />
  <img src="https://img.shields.io/badge/Design-Figma%20%7C%20Flowchart%20%7C%20Userflow-ff69b4" />
  <img src="https://img.shields.io/badge/Cloud-GCP%20%7C%20AWS%20%7C%20Vercel-yellow" />
  <img src="https://img.shields.io/badge/Tools-Notion%20%7C%20Feishu%20%7C%20Cursor-green" />
</p>

---

## 🧮 Product Thinking Snapshot
- 📊 指标驱动：以成功率、调用延迟、单位成本为核心指标  
- 🧠 用户导向：从开发者体验（DX）与财务可见性双线优化  
- 🔁 可扩展性：所有功能模块均 API-first，可多租户复用  
- 🧾 成本管理：实现自动账单、配额控制、后付费模式对齐 Google / OpenAI

---

## 📈 Metrics I Care About
| 指标 | 含义 | 示例 |
|------|------|------|
| API 成功率 | 成功响应占比 | ≥ 99.9% |
| 调用延迟 | P50 / P95 延迟 | 80ms / 150ms |
| 单位成本 | 每千次调用成本 | $0.004 |
| 账单误差率 | 实际 vs 账单偏差 | ≤ 0.1% |

---

## 🧭 My Workflow

```mermaid
flowchart LR
    A[用户调用API] --> B[Usage Log 写入]
    B --> C[计费引擎计算阶梯费用]
    C --> D[扣减余额/信用额度]
    D --> E[生成账单与日统计]
    E --> F[用户控制台展示]
```

---

## 🪪 Contact

- [GitHub](https://github.com/ciby9833)
- [Email](mailto:noelgfr@gmail.com)
- [LinkedIn](https://www.linkedin.com/in/%E5%B7%9D%EF%BC%88xavier%EF%BC%89-%E5%90%B4-583526223)
- Location: Jakarta 🇮🇩 · Shanghai 🇨🇳

<p align="center">
  <img src="https://img.shields.io/github/followers/ciby9833?label=Follow%20Me&style=social" />
  <img src="https://img.shields.io/github/stars/ciby9833?label=Stars&style=social" />
</p>

<p align="center">
  <i>“Turning complexity into clarity — one product at a time.”</i>
</p>


