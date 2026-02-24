# 01-comparison-global-landscape
2026 全球 AI 模型版图 - Comparison + Framework

Layout: 四象限结构，横轴“闭源 API ←→ 开源可控”，纵轴“高推理能力 ↑ / 高成本效率 ↓”

ZONES:
- 右上（闭源+高推理）: OpenAI GPT-5.3, Google Gemini 3 Pro, Anthropic Claude Opus 4.6
- 左下（开源+高性价比）: DeepSeek V3.2, Qwen 3, GLM 4.7
- 中右（闭源+实时/产品化）: xAI Grok 4.1, Doubao 1.5 Pro
- 中左（开源+生态扩展）: Llama 4, Kimi K2.5

LABELS:
- 标题: “2026 AI 模型竞争格局：没有单一王者，按任务选型”
- 注释1: “闭源在推理上领先”
- 注释2: “开源在成本与可定制性上加速追赶”
- 注释3: “混合多模型成为主流策略”

STYLE: notion minimalist hand-drawn line art, clean neutral background, rounded cards, concise Chinese labels, subtle icons
COLORS: 蓝色=闭源推理优势, 绿色=开源成本效率, 橙色=混合策略, 灰色=中性维度
ASPECT: 16:9, medium complexity

---

# 02-infographic-benchmark-snapshot
2026 顶尖模型基准快照 - Data Visualization

Layout: 左侧模型列表 + 右侧多指标横向可视化（条形图+图标）

ZONES:
- Zone 1: 模型列（Gemini 3 Pro, GPT-5.3, Claude Opus 4.6, Qwen 3, DeepSeek V3.2）
- Zone 2: 指标列（编码 CPI、推理 GPQA、多模态强度、上下文窗口）
- Zone 3: 结论区（“任务导向选型优于单模型崇拜”）

LABELS:
- 编码: Claude 96, GPT-5.3 94, Gemini 91
- 推理: Gemini 91.9, GPT-5.3 91.3
- 成本效率: DeepSeek V3.2（高）
- 上下文: Gemini 1M, GPT-5.3 400K

COLORS: 蓝=推理, 青=编码, 紫灰=多模态, 绿=成本效率
STYLE: notion style, hand-drawn infographics, clear Chinese annotations, high readability
ASPECT: 16:9, medium complexity

---

# 03-flowchart-model-selection
企业模型选型流程 - Process Flow

Layout: top-down flowchart with decision diamonds

STEPS:
1. 明确业务目标（编码提效 / 内容生成 / 智能客服 / 多模态）
2. 识别关键约束（预算、延迟、合规、数据主权）
3. 决策节点 A：是否强合规与私有化需求？
4. 决策节点 B：是否追求最强推理精度？
5. 输出路径：
   - 闭源优先（GPT / Claude / Gemini）
   - 开源优先（Qwen / DeepSeek / Llama）
   - 混合架构（主模型 + 备份模型 + 路由层）
6. 最终建议：按场景持续评测和动态切换

CONNECTIONS: solid arrows, clear yes/no branches, one final convergence box
STYLE: notion flowchart, minimalist icons, rounded blocks, Chinese text only
COLORS: 决策节点橙色, 执行节点蓝色, 结果节点绿色
ASPECT: 16:9, medium complexity

---

# 04-framework-api-ecosystem
LLMs API 统一接入架构 - Conceptual Framework

STRUCTURE: 3-layer architecture diagram

NODES:
- Layer 1 应用层: IDE Agent, Chatbot, Workflow Automation, Content Studio
- Layer 2 统一网关层: 请求路由, 鉴权, 计费, 观测, 重试降级
- Layer 3 厂商模型层:
  - 国内: 硅基流动, 百炼, 火山, 百度智能云
  - 国外: Vertex AI, AWS, Groq, Mistral
  - 第三方: OpenRouter, NVIDIA
  - 聚合 API: PackyAPI, AIGOCODE

RELATIONSHIPS: 应用层调用网关层，网关层分发到多供应商模型端点，回传统一响应
STYLE: notion framework diagram, modular cards, thin connector lines, simplified Chinese labels
COLORS: 层级区分色块（浅蓝/浅绿/浅橙），背景干净
ASPECT: 16:9, medium complexity

---

# 05-timeline-2026-outlook
2026 AI 模型演进时间线 - Chronological View

DIRECTION: horizontal timeline (Q1 to Q4)

EVENTS:
- Q1: 长上下文常态化（400K→1M+），多模态能力增强
- Q2: 代理化工作流普及，模型编排平台增长
- Q3: 开源模型份额提升，企业混合架构加速落地
- Q4: 合规与治理加强，成本优化与能耗议题上升
- 终点里程碑: “混合多模型策略成为企业默认配置”

MARKERS: quarter nodes with icon hints (context, agent, open-source, regulation)
STYLE: notion timeline, clean spacing, professional and readable Chinese labels
COLORS: 蓝色主线 + 绿色增长节点 + 橙色风险治理节点
ASPECT: 16:9, medium complexity
