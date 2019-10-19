# Play with Dapr
A Dapr Demo using minikube 

for full documentation and demos please see (https://dapr.io)

## How to install minikube
Please see (https://minikube.sigs.k8s.io/docs/start/)
## Installing & configure Dapr
For installing and configuring dapr please see (https://github.com/dapr/docs/blob/master/getting-started/environment-setup.md)

### configure minikube
start minikube
```shell
minikube start --cpus=4 --memory=4096 --kubernetes-version=1.16.0 --extra-config=apiserver.authorization-mode=RBAC
```
enable dashboard and ingress 

```shell
minikube addons enable dashboard
minikube addons enable ingress
```

dapr init --kubernetes
