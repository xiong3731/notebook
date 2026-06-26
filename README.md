# record my life

[https://xiong03.cn](https://xiong03.cn)

这是一个聚合了运维、云原生、Web3 及 AI 大模型技术的综合知识库与实战项目集合。通过 Git Submodule 统一管理，记录技术探索与工作沉淀。

## 核心模块

*   **10-notes (基础与运维)**: Linux、网络、存储、K8s、监控、CI/CD 及 Go/Python/Rust 编程。
*   **15-LLM (AI & 大模型)**: 模型推理 (vLLM/Ray)、微调 (PyTorch) 及 AI 辅助开发。
*   **20-web3 (区块链)**: 以太坊基础设施、私有网构建及智能合约开发。
*   **30-project (实战项目)**: 基础服务搭建、中间件集群 (Kafka/MinIO) 及架构设计。
*   **40-diary (个人日志)**: 周报与复盘。
*   **88-Ucloud / 89-startdt (经验沉淀)**: 生产环境故障排查与定制化解决方案。

## 快速开始

本项目使用 Git Submodule 管理。

**初次克隆**

```bash
git clone --recursive git@github.com:xiong3731/notebook.git
```

**更新代码**
```bash
git submodule update --init --recursive
# 或更新到远程最新
git submodule update --remote --recursive
```
