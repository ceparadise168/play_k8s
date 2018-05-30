* Service detail
    * https://tachingchen.com/tw/blog/kubernetes-service/

* kubectl command

```
$ kubectl create -f secret.yaml
$ kubectl create -f pod-with-label-1.yaml
$ kubectl  describe pod nginx-pod-1
```



``` bash
$ kubectl apply -f *.yaml
$ kubectl expose pod <pod> —type=<svc type> —name=<svc name> --port <expose port> —target-port=<container port>
```
