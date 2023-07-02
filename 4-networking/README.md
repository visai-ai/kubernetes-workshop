Service types:
- ClusterIP (default)
- NodePort
- LoadBalancer

Note:
```sh
kubectl apply -f service.yaml
kubectl get svc -n example
kubectl port-forward svc/my-service 8080:8080 -n example
kubectl delete svc my-service -n example
```
