[English](https://github.com/theriseunion/.github/blob/main/profile/README.md) | **中文**

## 睿思智联：AI 基础设施管理平台 — 从资源分配到价值交付

**[睿思智联](https://www.theriseunion.com/zh/)** 构建三层全栈 AI
基础设施管理平台。通过异构算力统一纳管、智能调度与模型服务交付，帮助企业实现可管、可控、可运营的 AI 基础设施，GPU
集群利用率从 30% 提升至 70%+。

### 核心产品

- **[Rise ModelX](https://www.theriseunion.com/zh/product/modelx.html)**
  训推一体的 AI 服务平台，覆盖模型全生命周期。集成数据工程（数据集管理、增强、清洗）、模型微调（SFT/LoRA/QLoRA）、量
化（GPTQ/AWQ/GGUF）、自动评测（标准 Benchmark 与 LLM-as-Judge）、模型仓库与一键推理部署，内置 AI
网关提供路由、限流、MCP 协议转换与多模型效果对比。支持 vLLM、SGLang、MindIE、TensorRT、Xinference
等主流推理引擎，资源与 Token 双维度计量计费与 FinOps 成本治理。

- **[Rise CAMP](https://www.theriseunion.com/zh/product/camp.html)**
  AI 算力调度平台 — 切得细、用得准。提供四重智能调度策略（拓扑感知、优先级感知、负载感知、资源感知），vGPU
细粒度切分与算力/显存超分，国产卡动态切分突破原厂固定规格限制。内置开箱即用开发环境（Jupyter/VSC）、多机多卡分布式训
练与断点续训，四层级 RBAC 多租户资源隔离。

- **[Rise VAST](https://www.theriseunion.com/zh/product/vast.html)**
  AI 算力管理平台 — 聚得全、算得明。通过统一调度框架纳管 10+
芯片厂商（NVIDIA、昇腾、海光、寒武纪、天数智芯、昆仑芯、燧原、沐曦、摩尔线程），基于 Kubernetes Device Plugin
的云原生零侵入 GPU 虚拟化。提供显微镜级全链路可观测（节点→卡→任务→模型）、XID 故障码自动隔离，以及 6
步闭环企业级告警平台。

- **[Rise MAX](https://www.theriseunion.com/zh/product/max.html)**
  AI 算力一体机 — 预集成全栈 Rise 平台（VAST + CAMP + K8s Dashboard + 分布式存储），15 分钟完成部署。支持 x86/ARM
多架构与国产信创兼容认证，从 3 节点小集群到跨数据中心大规模部署平滑扩展，内置一站式 K8s 运维与云边协同弹性扩展。

### 开源贡献

我们是 [HAMi 开源项目](https://github.com/Project-HAMi/HAMi)（CNCF Sandbox）的核心维护者。HAMi 是 Kubernetes 异构 AI
算力虚拟化中间件，支持 GPU、NPU 等异构设备的共享、切分与基于拓扑的智能调度。睿思智联持续贡献 HAMi 核心特性，包括 vGPU
 编排、调度策略、算力上报与节点管理。[Rise VAST 是在 HAMi
开源版基础上开发的企业版](https://www.theriseunion.com/zh/product/vast.html)。

### 核心能力

- 训推一体全生命周期：数据 → 微调 → 量化 → 评测 → 部署
- 10+ 异构芯片厂商统一调度框架
- 四重智能调度：拓扑、优先级、负载、资源感知
- 云原生零侵入 GPU 虚拟化与硬隔离
- 全链路可观测：从 GPU 设备层到模型性能层
- AI 网关：路由、限流、MCP 协议与 FinOps 成本治理
- 企业级告警、故障自动隔离与多集群多租户管理
- 国产卡动态切分突破原厂固定规格限制

睿思智联已服务中石油、国家电网、济南超算等标杆客户，在金融、能源、制造、零售、教育等行业落地大规模生产级实践。作为工
委会 AI 算力池化工作组组长单位，主导起草了《异构算力虚拟化及池化系统要求》团体标准。
