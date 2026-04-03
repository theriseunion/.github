**English** | [中文](https://github.com/theriseunion/.github/blob/main/profile/README_zh.md)

## RiseUnion: AI Infrastructure Management Platform — From Resource Allocation to Value Delivery

**[RiseUnion](https://www.theriseunion.com/)** builds a three-layer, full-stack AI infrastructure management
platform. Through unified heterogeneous compute management, intelligent scheduling, and model service delivery, we
help enterprises achieve manageable, controllable, and operable AI infrastructure — boosting GPU cluster utilization
from 30% to 70%+.

### Core Modules

- **[Rise ModelX](https://www.theriseunion.com/product/modelx.html)**
  A unified training & inference AI service platform covering the full model lifecycle. ModelX integrates data
engineering (dataset management, augmentation, cleaning), model fine-tuning (SFT/LoRA/QLoRA), quantization
(GPTQ/AWQ/GGUF), automated evaluation (Benchmarks & LLM-as-Judge), model hub with one-click inference deployment, and
 a built-in AI Gateway for routing, rate limiting, MCP protocol conversion, and multi-model comparison. Supports
vLLM, SGLang, MindIE, TensorRT, Xinference engines with dual-dimension resource/Token metering and FinOps cost
governance.

- **[Rise CAMP](https://www.theriseunion.com/product/camp.html)**
  AI compute scheduling platform — fine-grained slicing, precise scheduling. Features 4-way intelligent scheduling
strategies (topology-aware, priority-aware, load-aware, resource-aware), vGPU fine-grained slicing with compute/VRAM
overcommit, and domestic chip dynamic partitioning beyond vendor fixed-spec limitations. Includes out-of-box dev
environments (Jupyter/VSC), multi-node distributed training with checkpointing, and multi-tenant resource isolation
with 4-tier RBAC.

- **[Rise VAST](https://www.theriseunion.com/product/vast.html)**
  AI compute management platform — unified collection, full observability. Unifies 10+ chip vendors (NVIDIA, Ascend,
Hygon, Cambricon, Iluvatar, KunlunXin, Enflame, MetaX, Moore Threads) through a single scheduling framework with
cloud-native zero-intrusion GPU virtualization via Kubernetes Device Plugin. Provides microscope-level full-stack
observability (Node → GPU → Task → Model), automatic fault isolation with XID alerting, and an enterprise alert
platform with 6-step closed-loop incident management.

- **[Rise MAX](https://www.theriseunion.com/product/max.html)**
  AI compute appliance — pre-integrated with the full Rise platform stack (VAST + CAMP + K8s Dashboard + distributed
storage), deployable in 15 minutes. Supports x86/ARM multi-architecture with domestic chip certifications, scaling
from 3-node clusters to cross-datacenter deployments. Includes one-stop K8s operations and cloud-edge elastic
scaling.

### Open Source

We are a core maintainer of the [HAMi open-source project](https://github.com/Project-HAMi/HAMi) (CNCF Sandbox) —
Heterogeneous AI Computing Virtualization Middleware for Kubernetes. HAMi manages heterogeneous devices (GPU, NPU,
etc.), enables device sharing among pods, and makes scheduling decisions based on device topology and policies.
RiseUnion contributes to HAMi's core features including vGPU orchestration, scheduling, compute reporting, and node
management. [Rise VAST is the enterprise edition built on HAMi](https://www.theriseunion.com/product/vast.html).

### Key Capabilities

- Unified training & inference lifecycle: data → fine-tuning → quantization → evaluation → deployment
- 10+ heterogeneous chip vendors unified under one scheduling framework
- 4-way intelligent scheduling: topology, priority, load, and resource aware
- Cloud-native zero-intrusion GPU virtualization with hard isolation
- Full-stack observability from GPU device layer to model performance
- AI Gateway with routing, rate limiting, MCP protocol, and FinOps cost governance
- Enterprise-grade alerting, fault auto-isolation, and multi-cluster multi-tenant management
- Domestic chip dynamic partitioning beyond vendor fixed-spec limitations

RiseUnion serves benchmark customers including PetroChina, State Grid, and NSCC, with production deployments across
finance, energy, manufacturing, retail, and education. As the Group Leader of the AI Compute Pooling Working Group,
we led the development of the National Group Standard for Heterogeneous Virtualization and Pooling.
