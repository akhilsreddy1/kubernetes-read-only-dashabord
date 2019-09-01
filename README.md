# kubernetes-read-only-dashabord

Kubernetes read only dashboard which can be exposed over ingress with custom certs and Auth mechansims 

Creating secret for certs for ingress controller
``` 
kubectl create secret tls ingress-certs  --key ingress.key --cert ingress.crt  
```

Auth mechansim:
