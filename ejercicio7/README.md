# Ejercicio 7

## crear namespace

```shell
kubectl create ns adrian
```


## crear configmap

```shell
kubectl apply -n adrian -f configmap-env.yaml
```



## crear deploy

```shell
kubectl apply -n adrian -f deployment.yaml
```

