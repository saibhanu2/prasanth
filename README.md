apiVersion: v1
kind: Pod
metadata:
  name: nginx
  labels: 
    env: prod
spec:
  containers:
  - name: nginx1
    image: nginx:1.14.2
  - name: nginx2
    image: nginx:1.14.2
  - name: nginx
    image: nginx:1.14.2
