<p align="center">
  <h1 align="center">Flink Stream Data Analysis Tool</h1>
  <p align="center">
    <a href="README_ZH.md"><strong>简体中文</strong></a> | <strong>English</strong>
  </p>
</p>

## Table of Contents

- [Repository Introduction](#repository-introduction)  
- [Prerequisites](#prerequisites)  
- [Image Specifications](#image-specifications)
- [Getting Help](#getting-help)
- [How to Contribute](#how-to-contribute)

## Repository Introduction  
Argo Workflows is an open source container-native workflow engine for orchestrating parallel jobs on Kubernetes. Argo Workflows is implemented as a Kubernetes CRD (Custom Resource Definition).

Define workflows where each step is a container.
Model multi-step workflows as a sequence of tasks or capture the dependencies between tasks using a directed acyclic graph (DAG).
Easily run compute intensive jobs for machine learning or data processing in a fraction of the time using Argo Workflows on Kubernetes.
Argo is a Cloud Native Computing Foundation (CNCF) graduated project.

**Core Features:**

1. Deeply integrated with K8s, each workflow step runs as a Pod.
2. Define workflows using YAML files, which are easy to version control, share, and reuse.
3. Workflows support parameterization, and tasks can be configured with timeouts and retry strategies to enhance fault tolerance.
4. Provides a Web UI for visual monitoring of workflow status and logs.
5. Supports setting resource requests and limits such as CPU and memory for tasks, and supports resource limits at the workflow level.

This project offers pre-configured [**Argo Workflows**](https://marketplace.huaweicloud.com/contents/992480da-64a3-4ba8-90cb-686d1832e96a#productid=OFFI1111485128289529856) images with Chroma and its runtime environment pre-installed, along with deployment templates. Follow the guide to enjoy an "out-of-the-box" experience.

> **System Requirements:**
> - CPU: 2GHz or higher  
> - RAM: 4GB or more  
> - Disk: At least 50GB  


## Prerequisites  
[Register a Huawei account and activate Huawei Cloud](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## Image Specifications  

| Image Version                                                                                                            | Description | Notes |  
|--------------------------------------------------------------------------------------------------------------------------|-------------|-------|  
| [ArgoWorkflows-3.7.1-kunpeng](https://github.com/HuaweiCloudDeveloper/argoWorkflows-image/tree/ArgoWorkflows-3.7.1-kunpeng)                    | Deployed on Kunpeng servers with Huawei Cloud EulerOS 2.0 64bit |  | 


## Getting Help
- Submit an [issue](https://github.com/HuaweiCloudDeveloper/flink-image/issues)
- Contact Huawei Cloud Marketplace product support

## How to Contribute
- Fork this repository and submit a merge request.
- Update README.md synchronously based on your open-source mirror information.
