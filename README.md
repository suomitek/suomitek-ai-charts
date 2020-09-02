# suomitek-ai-charts
suomitek-ai-charts

https://raw.githubusercontent.com/suomitek/helm-repo-example/master
https://raw.githubusercontent.com/suomitek/helm-repo-example/master/index.yaml

## 中文文档 
https://kubesphere.io/docs/zh-CN

## Helm uses a packaging format called charts
https://helm.sh/docs/developing_charts/

## 基于 GitHub 搭建自有应用仓库
https://kubesphere.io/docs/zh-CN/platform-settings/app-hosting-official/

## 上传应用到 KubeSphere 官方仓库
https://kubesphere.io/docs/zh-CN/platform-settings/app-hosting-official/

## 基于 Local Helm Repo 快速搭建应用仓库部署 Redis
https://kubesphere.io/docs/zh-CN/platform-settings/local-repo/

## 应用商店
https://kubesphere.io/docs/zh-CN/quick-start/app-store

## 一键部署 EMQ X
https://kubesphere.io/docs/zh-CN/quick-start/one-click-deploy/

## 系统配置修改
https://kubesphere.io/docs/zh-CN/system-settings/edit-system-settings/

https://v3-0.docs.kubesphere.io/docs/cluster-administration/platform-settings/customize-basic-information/

helm template


## Pull an Image from a Private Registry
https://kubernetes.io/docs/tasks/configure-pod-container/pull-image-private-registry/#create-a-secret-in-the-cluster-that-holds-your-authorization-token

## Helm Chart Reference
https://www.consul.io/docs/k8s/helm

https://www.kubeflow.org/docs/started/k8s/kfctl-k8s-istio/

## Kubeflow Deployment with kfctl_k8s_istio
https://www.kubeflow.org/docs/started/k8s/kfctl-k8s-istio/

## Deploy using MiniKube on Linux
https://www.kubeflow.org/docs/started/workstation/minikube-linux/

## Kubeflow 使用指南
https://yq.aliyun.com/articles/680267

## 使用 TFX、Kubeflow 流水线和 Cloud Build 的 MLOps 的架构
https://cloud.google.com/solutions/machine-learning/architecture-for-mlops-using-tfx-kubeflow-pipelines-and-cloud-build?hl=zh-cn

## TensorFlow Extended (TFX) 是一个端到端平台，用于部署生产型机器学习流水线
https://www.tensorflow.org/tfx?hl=zh-cn

## Kubeflow-K8S的机器学习工具包
https://juejin.im/post/6844904131346300941

```yaml
image:
  repository: <repo>
  tag: <version tag>
  pullPolicy: IfNotPresent
imageCredentials:
  registry: <repo>
  username: <username>
  password: <pw>
```

```yaml
spec:
  containers:
  - name: some-pod
    image: <image>
  imagePullSecrets:
  - name: <name-of your secret>
```