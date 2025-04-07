# first-pod-kubernetes
```yaml
apiVersion: v1
kind: Pod
metadata:
 name: webapp
 labels:
  app: v1.0.0
spec:
 containers:
  - name: webapp
    image: nginx:latest
    imagePullPolicy: IfNotPresent
```
```
kubectl apply -f first-pod.yaml
```
