# Deploy gitea in Kubernetes
```
kubectl delete namespace gitea
kubectl create -f https://raw.githubusercontent.com/firegen/kubernetes/master/deployments/gitea/deploy_all.yaml
```
