# create deployment with replicas

```
kubectl create deployment test --image=nginx

kubectl get deployments.apps

NAME          READY   UP-TO-DATE   AVAILABLE   AGE
hello-world   2/2     2            2           34d
test          0/2     2            0           2m45s


kubectl scale deployment test --replicas=2

kubectl describe deployments.apps
Replicas:               2 desired | 2 updated | 2 total | 2 available | 0 unavailable
```
