# 第1章 背景

KCL语言是 Kusion Configure Language的缩写，意为 Kusion 配置语言。而 Kusion 的名字是从 Kubernetes + Fusion 而来，意为 Kubernetes 融合。因此 KCL 也有同学将其理解为面向 K8S 云原生场景的配置语言，或者是叫 Kubernetes Configure Language，它是一个面向云原生场景的 DSL 语言。

Kubernetes 作为云原生平台的代表，其通过 YAML 配置来和系统交互的方式带来了配置语言生态的爆发，很多场景经常面临成千上万行 YAML 配置的管理和编写工作。为了管理急剧膨胀的 YAML 配置代码社区出现了很多方案，比如 Kustomize 通过 Base 基线加 Patch 补丁的方式灵活渲染出不同的 YAML 文件，比如Go社区诞生的 CUE 等。
