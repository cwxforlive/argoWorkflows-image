<p align="center">
  <h1 align="center">开源镜像商品</h1>
  <p align="center">
    <a href="README.md"><strong>English</strong></a> | <strong>简体中文</strong>
  </p>
</p>

## 目录

- [仓库简介](#仓库简介)
- [前置条件](#前置条件)
- [镜像说明](#镜像说明)
- [获取帮助](#获取帮助)
- [如何贡献](#如何贡献)

## 仓库简介
Argo Workflows是一个开源的容器原生工作流引擎，用于在Kubernetes上编排并行作业。Argo Workflows是作为Kubernetes CRD（自定义资源定义）实现的。

定义工作流，每个步骤都是一个容器。
将多步骤工作流建模为任务序列，或使用有向无环图（DAG）捕获任务之间的依赖关系。
使用Kubernetes上的Argo Workflows，在一小部分时间内轻松运行用于机器学习或数据处理的计算密集型作业。
Argo是一个云原生计算基金会（CNCF）的毕业项目。

**核心特性：**

1.深度集成 K8s，每个工作流步骤作为一个 Pod 运行。

2.使用 YAML 文件定义工作流，易于版本控制、共享和复用。

3.工作流支持参数化，任务可配置超时、重试策略以提高容错性。

4.提供 Web UI 可视化监控工作流状态和日志。

5.支持为任务设置 CPU、内存等资源请求和限制，支持工作流级别资源限制。

本项目提供的开源镜像商品 [**`Argo-Workflows`**](https://marketplace.huaweicloud.com/contents/992480da-64a3-4ba8-90cb-686d1832e96a#productid=OFFI1111485128289529856)，已预先安装 chroma 软件及其相关运行环境，并提供部署模板。快来参照使用指南，轻松开启“开箱即用”的高效体验吧。

> **系统要求如下：**
> - CPU: 2GHz 或更高
> - RAM: 4GB 或更大
> - Disk: 至少50GB
## 前置条件
[注册华为账号并开通华为云](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## 镜像说明

| 镜像规格                                                                                                                     | 特性说明 | 备注 |
|--------------------------------------------------------------------------------------------------------------------------| --- | --- |
| [ArgoWorkflows-3.7.1-kunpeng](https://github.com/HuaweiCloudDeveloper/chroma-image/tree/Chroma-1.0.16-kunpeng) | 基于 鲲鹏服务器 + Huawei Cloud EulerOS 2.0 64bit 安装部署 |  |

## 获取帮助
- 更多问题可通过 [issue](当前仓库issue地址) 或 华为云云商店指定商品的服务支持 与我们取得联系
- 其他开源镜像可看 [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos)

## 如何贡献
- Fork 此存储库并提交合并请求
- 基于您的开源镜像信息同步更新 README.md
