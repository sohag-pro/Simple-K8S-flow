# Kubernetes Deployment with load balancer

# K8S

## Install kubectl

```bash
brew install kubectl
```

## Set up CONFIG

```bash
export KUBECONFIG=configPath/config.yaml
```

## Apply the deployment

```bash
kubectl apply -f js-deployment.yaml
```

## Apply the service

```bash
kubectl apply -f js-service.yaml
```

### Some useful commands

```bash
kubectl get pods
kubectl get services
kubectl get deployments
kubectl get all
kubectl describe pod <pod-name>
kubectl describe service <service-name>
kubectl describe deployment <deployment-name>
kubectl delete pod <pod-name>
kubectl delete service <service-name>
kubectl delete deployment <deployment-name>
```