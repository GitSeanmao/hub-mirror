---
name: hub-mirror issue template
about: 用于执行 hub-mirror workflow 的 issue 模板
title: "[hub-mirror] 请求执行任务"
labels: ["hub-mirror"]
---

{
    "platform":"",
    "hub-mirror": [
        "若对OS/ARCH无要求，platform请留空，不要加任何值，默认就是linux/amd64",
        "如需切换arm架构，请修改platform为arm64或linux/arm64/v8",
        "registry.k8s.io/kube-apiserver:v1.27.4"
    ]
}
