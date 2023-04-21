# kube-random-hash
Returns a string hash and deploys it in kubernetes pod replicas

## Steps to execute
If you clone the code start the kube like this:
```
kubectl apply -f .\manifests\deployment.yaml 
```

Otherwise link directly to this repo:
```
kubectl apply -f https://raw.githubusercontent.com/quindai/kube-random-hash/main/manifests/deployment.yaml 
```

You should get 
```bash
deployment.apps/hashgenerator-dep created
```

Delete the kube:
```
kubectl delete -f .\manifests\deployment.yaml 
```