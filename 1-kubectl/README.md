Note:
```sh
kubectl config view --raw --minify
kubectl get nodes
kubectl get pods -A

kubectl create namespace example
kubectl run my-pod-1 --image nginx:latest -n example
kubectl run my-pod-2 --image nginx:1.20 -n example
kubectl get pods -n example
kubectl describe pods my-pod-1 -n example
kubectl logs my-pod-2 -n example

kubectl delete pods my-pod-1 -n example
kubectl delete pods --all -n example
kubectl delete ns example
```
