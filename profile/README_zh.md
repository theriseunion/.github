[English](https://github.com/theriseunion/.github/blob/main/profile/README.md) | **中文**

## 睿思智联: AI-Native 的统一智算管理平台
[北京睿思智联科技有限公司 (RiseUnion)](https://www.theriseunion.com/) 专注于构建高效、灵活的 AI 异构计算管理平台，为企业客户提供 GPU 及其他 AI 计算资源的池化、调度与优化方案。我们致力于提升 AI 计算资源的利用率，降低算力成本，并推动国产 AI 生态的发展。

### 核心模块

* **[Rise CAMP](https://www.theriseunion.com/product/camp.html)**
  一体化模型服务管理平台，支持大模型的推理服务与分布式训练开发。CAMP 可快速接入多种模型及推理引擎（如 vLLM、TGI、SGLang、MindIE 等），并提供版本控制、A/B 测试、流量路由、多引擎调度等精细化能力，同时支持模型广场、资源自动调度与弹性任务管理。

* **[Rise VAST](https://www.theriseunion.com/product/vast.html)**
  面向多租户和异构环境的 GPU 虚拟化与弹性调度层，支持精细化的算力/显存切分、超分配与动态迁移。兼容 NVIDIA、昇腾、寒武纪、海光等国产与国际加速芯片，支持 vGPU、MIG、passthrough 等多种模式。具备资源碎片整理、算力复用、热释放等高级功能。

* **[Rise ModelX](https://www.theriseunion.com/product/modelx.html)**
  专注于模型部署、管理、服务与运维的 ModelOps 平台。ModelX 与 CAMP 和 VAST 深度集成，实现模型与算力资源的自动映射、服务上线、路由策略下发、实时监控与智能扩缩容，适配多种混合部署环境。

* **[Rise MAX](https://www.theriseunion.com/product/camp.html)**
  面向企业的一体化 AI 计算解决方案，提供开箱即用的部署能力，降低 AI 应用研发与落地门槛，加速大模型商业化进程。

### 开源生态

我们是 [HAMi 开源项目](https://github.com/Project-HAMi/HAMi) 的核心贡献者和长期支持者。HAMi（原名 [k8s-vGPU-scheduler](https://github.com/4paradigm/k8s-vgpu-scheduler)）是 Kubernetes 上的异构设备管理中间件，可用于统一调度 GPU、NPU 等多种设备，支持设备共享、拓扑感知调度与自定义策略扩展。

睿思智联在企业场景中积极推广 vGPU 技术，持续贡献包括 vGPU 编排、算力调度、设备上报、节点管理等核心功能，并在自身产品中深度集成 HAMi，实现 GPU 生命周期的统一管理与调度优化。

### 核心特性

* 面向国产芯片的全面兼容适配能力；
* 支持大模型的训练与推理全流程管理；
* 支持 GPU、vGPU、昇腾、VPU、NPU 等异构计算资源；
* 多租户精细隔离与弹性资源调度能力；
* 实时可观测性、碎片整理与高可用支持；
* 边云协同的混合部署能力；
* 与 HAMi 开源生态深度融合与双向增强。


睿思智联致力于服务金融、电信、能源、制造、政务等 AI 驱动型行业，帮助客户高效、灵活、安全地部署和运营大模型，加速 AI 基础设施现代化升级。
