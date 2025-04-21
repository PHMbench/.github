# PHMbench: 故障预测与健康管理基准测试生态系统

<div align="center">
  <img src="pic/PHMbench.png" alt="PHMbench Logo" width="300"/>
  <p><strong>🔬 一个综合性的故障预测与健康管理基准测试生态系统 🔬</strong></p>
  <p><em>⚠️ 内测阶段 - 仅限邀请访问 ⚠️</em></p>

  <p>
    <img src="https://img.shields.io/badge/状态-内测中-orange" alt="Status: Alpha"/>
    <img src="https://img.shields.io/badge/版本-0.1.0--alpha-blue" alt="Version"/>
    <img src="https://img.shields.io/badge/许可-Apache%202.0-green" alt="License"/>
  </p>
</div>

## 📖 目录
- [📋 项目概览](#-项目概览)
- [🧩 生态系统组成](#-生态系统组成)
- [🔔 最新动态](#-最新动态)
- [🚀 快速导航](#-快速导航)
- [📂 项目结构](#-项目结构)
- [🏛️ 许可证](#️-许可证)
- [📎 引用方式](#-引用方式)

## 📋 项目概览

**PHMbench** 是一个全面的故障预测与健康管理(Prognostics and Health Management, PHM)基准测试生态系统，旨在为 PHM 领域的研究人员提供统一的评估环境。该生态系统通过一系列子基准平台（SubBench），涵盖了各种工业场景下的故障诊断、预测性维护和剩余使用寿命预测任务。

### 💡 核心理念

- 🔍 **标准化评估**：提供统一的数据处理流程、模型实现和评估指标
- 🔄 **可复现研究**：确保实验设置、训练过程和结果分析的完全透明
- ⚖️ **简化比较**：在相同条件下评估不同算法的性能
- 🧱 **模块化设计**：便于扩展和应用到新的 PHM 场景

<div align="center">
  <img src="pic/architecture.png" alt="PHMbench Architecture" width="700"/>
  <p><em>PHMbench 生态系统架构</em></p>
</div>

## 🧩 生态系统组成

PHMbench 生态系统由以下专业子基准平台组成：

| 子平台 | 描述 | 状态 |
|--------|------|------|
| [**Vbench**](./Vbench/) | 🏭 工业设备故障诊断与预测性维护基准平台 | 🔒 内测中 |
| [**SLbench**](./SLbench/) | 🔄 系统级健康管理与剩余寿命预测基准平台 | 🛠️ 开发中 |
| [**VLbench**](./VLbench/) | 👁️ 多模态故障诊断与可视化分析基准平台 | 🛠️ 开发中 |
| [**Awesome-PHM-Paper-Agent**](./Awesome-PHM-Paper-Agent/) | 📚 PHM 领域文献检索与知识库 | 🛠️ 开发中 |

每个子平台专注于 PHM 的不同方面，提供特定领域的数据集、模型和评估方法。

<div align="center">
  <img src="pic/bench_overview.png" alt="SubBench Overview" width="700"/>
  <p><em>PHMbench 子平台功能概览</em></p>
</div>

## 🔔 最新动态

- **2023.04**: 🔬 PHMbench 核心框架与 Vbench 子平台进入内测阶段
- **2023.03**: 🔧 完成生态系统整体设计与子平台规划
- **2023.02**: 🚀 项目启动并完成初步市场调研

## 🚀 快速导航

> ⚠️ **注意**: 当前项目处于内测阶段，仅向特定研究机构和合作伙伴开放。如需访问权限，请联系项目维护者。

内测参与者可通过以下链接访问各子平台文档：

- **Vbench** - [📚 文档](./Vbench/README.md) | [🏃‍♂️ 快速开始](./Vbench/doc/quickstart.md)
- **SLbench** - [📚 文档](./SLbench/README.md) *(开发中)*
- **VLbench** - [📚 文档](./VLbench/README.md) *(开发中)*
- **Awesome-PHM-Paper-Agent** - [📚 文档](./Awesome-PHM-Paper-Agent/README.md) *(开发中)*

<div align="center">
  <img src="pic/workflow.png" alt="PHMbench Workflow" width="600"/>
  <p><em>PHMbench 典型工作流程</em></p>
</div>

## 📂 项目结构

```bash
📂 PHMbench
├── 📄 README.md                 # 主项目说明文档
├── 📂 Vbench                    # 🏭 工业设备故障诊断基准平台
├── 📂 SLbench                   # 🔄 系统级健康管理基准平台
├── 📂 VLbench                   # 👁️ 多模态故障诊断基准平台
├── 📂 Awesome-PHM-Paper-Agent   # 📚 PHM 文献检索与知识库
└── 📂 docs                      # 📋 通用文档
```

## 🏛️ 许可证

本项目采用 [Apache License (Version 2.0)](https://github.com/PHMbench/PHMbench/blob/master/LICENSE) 许可协议。各子平台可能有独立的许可说明，请参考相应文档。

## 📎 引用方式

> 📝 **注意**: 项目尚未正式发布，以下引用格式仅供内测用户参考，正式引用格式将随项目公开发布提供。

```bibtex
@misc{phmbench2023,
  title={PHMbench: A Comprehensive Benchmark Ecosystem for Prognostics and Health Management},
  author={PHMbench Team},
  year={2023},
  howpublished={Internal Testing Version}
}
```

<div align="center">
  <br>
  <p>🌟 欢迎内测用户提供宝贵反馈! 🌟</p>
  <img src="pic/contact_qrcode.png" alt="联系方式" width="150"/>
  <p><em>扫描二维码加入内测讨论组</em></p>
</div>