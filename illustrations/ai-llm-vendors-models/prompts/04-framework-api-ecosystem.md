LLMs API 统一接入架构 - Conceptual Framework
STRUCTURE: 3-layer architecture diagram.
LAYER 1 应用层: IDE Agent, Chatbot, Workflow Automation, Content Studio.
LAYER 2 统一网关层: 请求路由, 鉴权, 计费, 观测, 重试降级.
LAYER 3 厂商模型层: 国内（硅基流动、百炼、火山、百度智能云）, 国外（Vertex AI、AWS、Groq、Mistral）, 第三方（OpenRouter、NVIDIA）, 聚合 API（PackyAPI、AIGOCODE）。
RELATIONSHIPS: 应用层调用网关，网关分发到多供应商模型并统一响应。
STYLE: notion framework diagram, modular cards, thin connectors, simplified Chinese labels.
COLORS: 浅蓝/浅绿/浅橙分层，简洁背景。
ASPECT: 16:9.
