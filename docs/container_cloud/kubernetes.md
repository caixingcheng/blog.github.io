# 扩展k8s
## Operator模式
[Operator 模式 | Kubernetes](https://kubernetes.io/zh-cn/docs/concepts/extend-kubernetes/operator/)

**Operator 模式** 旨在记述（正在管理一个或一组服务的）运维人员的关键目标。 这些运维人员负责一些特定的应用和 Service，他们需要清楚地知道系统应该如何运行、如何部署以及出现问题时如何处理。

在 Kubernetes 上运行工作负载的人们都喜欢通过自动化来处理重复的任务。 Operator 模式会封装你编写的（Kubernetes 本身提供功能以外的）任务自动化代码。

### kubernetes上的Operator

Kubernetes 的 [Operator 模式](https://kubernetes.io/zh-cn/docs/concepts/extend-kubernetes/operator/)概念允许你在不修改 Kubernetes 自身代码的情况下， 通过为一个或多个自定义资源关联[控制器](https://kubernetes.io/zh-cn/docs/concepts/architecture/controller/)来扩展集群的能力。 Operator 是 Kubernetes API 的客户端， 充当[自定义资源](https://kubernetes.io/zh-cn/docs/concepts/extend-kubernetes/api-extension/custom-resources/)的控制器

### 编写你自己的Operator
