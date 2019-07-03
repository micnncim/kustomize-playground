# kustomize-playground

## Get started

- k8s <1.14

```
kustomize build dir/ | kubectl apply -f - 
```

- k8s >= 1.14

```
kubectl apply -k dir/
```
