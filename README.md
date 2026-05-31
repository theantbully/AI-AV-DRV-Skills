# AI-AV-DRV-Skills
Personal skills map as AI-Audio/Video-Driver-developing Enigneer

• 完善的Camera系统及音视频编解码、图像处理技术应用体系

• 掌握AI模型训练、异构平台的部署与集成全流程

• 拥有丰富的Linux外设驱动调试经验


<img width="648" height="266" alt="image" src="https://github.com/user-attachments/assets/ef99d05d-f850-43f0-b905-f65759ba5acb" />


三大能力域关系（关键总结）

① 是业务核心能力（camera/codec）

② 是增长曲线（AI+异构）

③ 是护城河（driver+debug+稳定性）


核心技术能力（Embedded Multimedia \& Edge AI System Engineer）


**1. Camera / ISP / Multimedia 端到端系统能力**

具备完整的摄像头成像与音视频处理链路工程能力，覆盖从硬件到应用层的全栈实现与优化：

熟悉 MIPI CSI-2 / Image Sensor / ISP pipeline，理解 RAW→YUV 图像处理链路及关键图像算法流程

掌握 Linux V4L2 / Media Controller 框架，可完成 sensor / ISP / capture driver 的调试与集成

掌握 DMA-BUF / zero-copy buffer 机制，具备跨模块（ISP/codec/AI）共享buffer设计能力

使用 FFmpeg / GStreamer / MPP 构建音视频采集、编码、推流系统

深入理解 H.264 / H.265 编码链路（GOP / B-frame / latency tradeoff）

具备端到端链路优化能力（sensor → ISP → V4L2 → encoder），可进行 低延迟（<50ms）IPC级优化设计







**2. AI模型部署 \& 异构计算系统集成能力**

具备嵌入式AI工程落地能力，能够完成模型从训练到端侧推理的全流程系统集成：

理解 CNN / Transformer 推理流程及量化原理（FP32→INT8）

熟悉 ONNX / RKNN  等推理框架集成与适配

具备 CPU / GPU / NPU 异构计算调度经验，可进行多算力协同优化

支持 camera → AI inference → display/encode 的实时推理流水线设计

掌握 zero-copy inference（dmabuf直通NPU）与内存带宽优化策略

可完成模型部署性能分析（latency breakdown / DDR bandwidth bottleneck）







**3. Linux内核 / 驱动 / SoC系统级工程能力**

具备扎实的Linux内核与外设驱动能力，能够支撑复杂多媒体SoC系统稳定运行与调试：

熟悉 Linux 内核机制：进程调度 / 内存管理 / 中断 / workqueue / softirq

掌握 platform driver / device tree / V4L2 / ALSA / I2C / SPI 驱动开发与调试

理解 DMA / cache coherency / IOMMU / dma-buf buffer共享机制

具备复杂系统 bring-up 能力（sensor / ISP / codec / AI NPU）

熟练使用 kernel debug 工具：ftrace / perf / dmesg / crash dump / oops分析

能定位系统级问题：死锁 / 内存泄漏 / buffer corruption / frame drop









