---
id: version-0.20.1-config-overview
title: Configuration Overview
original_id: config-overview
---

在本章节中，将为你详细介绍链级配置和各微服务配置的相关内容。

[链级配置](./chain-configuration)主要是指链自身的一些属性、系统合约、RPC 接口、节点间网络连接等的配置，需要用户在**起链前**进行初始化配置。 在链级配置这篇文档中，将为你详细介绍链的各个可配置项；然后通过具体的操作示例，演示如何起链前对链进行初始化配置；并带你详细了解初始化配置后文件的目录结构；最后，将通过具体示例，演示起链后如何修改个别配置。 相信阅读完此文档后，你将可以自己定制一条满足你需求的链。

[微服务配置](./microservice-configuration)主要是指各微服务的配置。CITA 将区块链节点的必要功能解耦为六个微服务：RPC，Auth，Consensus，Chain，Executor，Network，各组件之间通过消息总线交换信息相互协作。 各节点运维人员可根据系统运行情况（微服务负载情况等）进行配置调整，优化性能。 当前只有 network 微服务可以在不停链的情况下，进行配置调整，其他模块需要停链后进行操作。当修改配置后，支持自动刷新。 在[微服务配置](./microservice-configuration)这篇文档中，将为你详细介绍各个微服务的可配置项。