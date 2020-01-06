# kubernetes-dotnet-example

## Building the image
```
docker build . -t     app: webapp
```

## Deploying Deployment on Kubernetes
If you have cloned the repository:
```
kubectl apply -f k8s/deployment.yaml
```

Otherwise:
```
kubectl apply -f https://raw.githubusercontent.com/cdemi/kubernetes-dotnet-example/master/k8s/deployment.yaml
```

## Deploying Service on Kubernetes
If you have cloned the repository:
```
kubectl apply -f k8s/service.yaml
```

Otherwise:
```
kubectl apply -f https://raw.githubusercontent.com/cdemi/kubernetes-dotnet-example/master/k8s/service.yaml
```