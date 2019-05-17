Dev Environment:
```
kubectl apply -f .
helm init --service-account tiller
helm install stable/minio --name argo-artifacts --set defaultBucket.enabled=true
```
