# Wordpress on Kubernetes cluster

```sh
kubectl apply -f mysql-secret.yaml
kubectl apply -f mysql-pv-pvc.yaml
kubectl apply -f mysql-statefulset.yaml
kubectl apply -f mysql-service.yaml
kubectl apply -f wordpress-deployment.yaml
```