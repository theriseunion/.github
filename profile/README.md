**English** | [中文](https://github.com/theriseunion/.github/blob/main/profile/README_zh.md)

## RiseUnion: AI-Native Platform for Unified Intelligent Compute Resource Management

**[RiseUnion](https://www.theriseunion.com/)** builds a full-stack AI-native infrastructure platform for managing large-scale heterogeneous compute and model workflows. Our system unifies the virtualization, scheduling, and intelligent orchestration of multi-vendor, cross-cluster GPU and AI compute resources.

### Core Modules

- **[Rise CAMP](https://www.theriseunion.com/product/camp.html)**  
  Unified model service management platform supporting both inference and distributed training. CAMP enables fast onboarding of diverse models and engines (vLLM, TGI, SGLang, MindIE, etc.), and provides fine-grained control for versioning, A/B testing, traffic routing, and multi-backend dispatch. Features include model marketplace, automatic GPU allocation, and elastic scheduling for inference & training tasks.

- **[Rise VAST](https://www.theriseunion.com/product/vast.html)**  
  A robust GPU virtualization and adaptive scheduling layer that supports fine-grained resource slicing, compute/memory oversubscription, and dynamic migration. Compatible with both domestic and international accelerators (NVIDIA, Ascend, MLU, DCU, etc.), VAST enables GPU pooling across clusters and tenants using vGPU, MIG, or passthrough modes. Features include resource defragmentation, compute reuse, and hot release.

- **[Rise ModelX](https://www.theriseunion.com/product/modelx.html)**  
  A dedicated ModelOps platform focused on deployment, management, service provisioning, and lifecycle operations of AI models. It supports integration with CAMP and VAST, enabling unified model-to-resource mapping, automated publishing, routing policies, service monitoring, and intelligent scaling across hybrid environments.

- **[Rise MAX](https://www.theriseunion.com/product/camp.html)**  
  An enterprise-grade, all-in-one solution for AI computing, offering out-of-the-box deployment and reduced AI application development costs.


### Open Source

We are also a core contributor and long-term supporter of the [HAMi open-source project](https://github.com/Project-HAMi/HAMi) — formerly known as '[k8s-vGPU-scheduler](https://github.com/4paradigm/k8s-vgpu-scheduler)', is a Heterogeneous device management middleware for Kubernetes. It can manage different types of heterogeneous devices (like GPU, NPU, etc.), share heterogeneous devices among pods, make better scheduling decisions based on topology of devices and scheduling policies.
RiseUnion actively promotes vGPU in enterprise environments, contributes to its core features (such as vGPU orchestration, scheduling, compute reporting, and node management), and integrates it deeply into our own products for unified GPU lifecycle management.


### Key Features

- Full-stack support for both training and inference of large AI models 
- Heterogeneous compute support: GPU, vGPU, Ascend, VPU, NPU  
- Multi-tenant elastic resource scheduling with fine-grained isolation  
- Real-time observability, resource fragmentation reduction, and HA support  
- Seamless edge-cloud collaborative deployment  
- Deep integration with and contributions to the HAMi open-source ecosystem  
- Built-in compatibility with domestic compute infrastructures

RiseUnion empowers AI-driven industries—such as finance, energy, telecom, and public sector—to deploy and operate large models efficiently, flexibly, and securely on modern hybrid infrastructures.


