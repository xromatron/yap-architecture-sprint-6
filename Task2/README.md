# Задание 2. Динамическое масштабирование контейнеров

```shell
minikube start
```

```shell
minikube addons enable
```

```shell
kubectl get deployment metrics-server -n kube-system 
```

```shell
kubectl apply -f deployment.yaml
```

```shell
kubectl get pod
```

```shell
kubectl apply -f hpa.yaml
```

```shell
kubectl get hpa
```

```shell
kubectl expose deployment scaletestapp --type=NodePort --port=8080
```

```shell
 minikube service scaletestapp --url
```

```shell
locust
```

```shell
minikube dashboard
```