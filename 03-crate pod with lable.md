# create pod with lable

```
kubectl run  test02 --image=nginx -l lable=lable1
pod/test02 created

kubectl get pod test02
NAME     READY   STATUS    RESTARTS   AGE
test02   1/1     Running   0          14s

kubectl describe pod test02  | grep lable
Labels:           lable=lable1
```
