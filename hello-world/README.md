# Hello, kustomize

### deploy

```
# deploy base
kubectl apply -k base

# deploy staging
kubectl apply -k overlays/staging

# deploy namespace
kubectl apply -k base --namespace=nstest

# read
kubectl get pods --namespace=nstest
kubectl describe pods {pod-name}
```
