# kube-job-demo
# Steps
```
docker build -t dmilan/mytestpython:v3 .
docker push dmilan/mytestpython:v3 
docker run dmilan/mytestpython:v3 
kubectl apply -f k8s/
```