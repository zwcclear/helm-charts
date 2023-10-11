helm-charts仓库

```
helm repo add hellok8s https://zwcclear.github.io/helm-charts/

helm install my-hello-helm hellok8s/hello-helm --version 0.1.0

helm upgrade --install my-hello-helm hellok8s/hello-helm --version 0.1.0

helm uninstall my-hello-helm

helm search repo my-hello-helm
```
