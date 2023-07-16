# k8s

## Base

Simple kubectl 

## Hot, cold and warn for database


## Load Balancer



## use minikube

minikube implements a local Kubernetes cluster on macOS

* minikube version
* minikube start
* minikube dashboard 

## remove deployments
kubectl delete deployment deployment_name


## kubectl cmd

kubectl get deployment
kubectl get service
kubectl apply -f base/my-pv.yaml
kubectl apply -f base/mysql-deployment.yaml

kubectl apply -f laravel-deployment.yaml
kubectl apply -f laravel-service.yaml
kubectl logs -f deployment.apps/laravel-deployment
