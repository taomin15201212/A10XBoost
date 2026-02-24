---
type: mixed
density: minimal
style: notion
image_count: 3
---

## Illustration 1: 部署流程对比

**Position**: 第1章开头 (Line 13)
**Purpose**: 直观展示传统部署与Serverless部署的流程差异，降低读者认知门槛
**Visual Content**:
- 左侧：传统部署流程（6步：买服务器→配环境→装Nginx→域名备案→SSL证书→部署上线）
- 右侧：Serverless部署（2步：写代码→一键部署）
- 时间对比：3天 vs 5分钟
- 使用Notion风格的卡片式布局
**Type Application**: comparison
**Filename**: 01-comparison-deployment-flow.png

## Illustration 2: 架构对比图

**Position**: "Serverless到底是什么？"章节 (Line 49)
**Purpose**: 可视化展示传统架构与Serverless架构的工作原理差异
**Visual Content**:
- 左侧：传统架构图（用户→服务器→返回，服务器24小时运行）
- 右侧：Serverless架构图（用户→边缘节点→函数执行→返回，按需启动）
- 箭头流程图 + 节点图标
- 成本示意：持续付费 vs 按量付费
**Type Application**: framework
**Filename**: 02-framework-architecture.png

## Illustration 3: 平台对比

**Position**: "平台怎么选？"章节 (Line 81)
**Purpose**: 帮助读者快速对比Vercel和Cloudflare Workers的特点
**Visual Content**:
- 两栏对比卡片
- Vercel: 开发体验、Next.js集成、Fluid Compute
- Cloudflare: 全球覆盖、成本控制、免费额度
- 适用场景标签
- 简洁的图标和颜色区分
**Type Application**: infographic
**Filename**: 03-infographic-platform-comparison.png
