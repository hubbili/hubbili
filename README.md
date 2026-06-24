# hubbili

Building AI gateway and observability infrastructure for production LLM systems.

面向生产环境的大模型系统，持续建设 AI Gateway 与 Observability 基础设施。

## Focus | 关注方向

- Multi-model gateway for production traffic
- Routing, auth, quotas, and governance
- Telemetry, tracing, and cost visibility
- Reliability for LLM workloads in real environments
- 大模型网关、多模型接入与流量治理
- 鉴权、限流、配额、路由与控制面能力
- 观测、链路追踪、成本可视化
- 面向真实生产环境的稳定性建设

## Current Direction | 当前主线

This GitHub is being rebuilt around a long-term AI infra track.

目前这套 GitHub 账号会围绕一条长期 AI Infra 主线持续更新：

- LLM gateway infrastructure
- traffic governance and control planes
- observability for model serving systems
- 大模型网关基础设施
- 流量治理与控制平面
- 模型服务系统的可观测性

## What I Build Here | 这里会放什么

- one primary gateway project
- supporting work around traces, metrics, and evaluation hooks
- smaller infra experiments that can later become reusable components
- 一个长期维护的主网关项目
- 围绕 tracing、metrics、evaluation hooks 的配套能力
- 可以逐步沉淀为通用组件的小型基础设施实验

## Working Style | 工作方式

- build for production, not only demos
- prefer clear interfaces over clever abstractions
- treat observability as part of the product surface
- 做能进入生产环境的系统，而不只是 demo
- 重视清晰边界和稳定接口，而不是炫技式抽象
- 把 observability 当成产品能力的一部分来建设

## Next | 接下来

- gateway core and provider integrations
- request tracing and usage telemetry
- reliability patterns for production LLM systems
- gateway 核心能力与 provider 接入
- 请求链路追踪与 usage telemetry
- 面向生产环境的大模型系统可靠性模式
