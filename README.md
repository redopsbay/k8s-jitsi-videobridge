# k8s-jitsi-videobridge
Jitsi Videobridge microservice


## Deployment ##


### Create a namespace resource
```
kubectl apply -f Namespace.yaml
```

### Create a docker-secret secret resource
```
kubectl apply -f docker-secrets.yaml
```

### Create a configmap resource
```
kubectl apply -f configmap.yaml
```

### Create a PV resource
```
kubectl apply -f nfs-pv.yaml
```

### Create a PVC resource
```
kubectl apply -f nfs-pvc.yaml
```

### Create a loadbalancer svc resource
```
kubectl apply -f jvb-service.yaml
```

### Deployment
```
kubectl apply -f deployment-with-configmap.yaml
```


Author Information
------------------

- Name: Alfred Valderrama
- Email: alfred98valderrama@gmail.com
- Github Repository: https://github.com/redopsbay
- Website: https://goadminops.com
