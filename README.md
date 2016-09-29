# docker-heapster

Deploy (Heapster+InfluxDB+Grafana) into cluster.
For docker using docker-compose

```
# deploy
cd docker-deploy/
docker-compose up -d
# un-deploy
docker-compose down
```

For k8s deploy

```
# deploy
kubectl create -f k8s-deploy/
# un-deploy
kubectl delete -f k8s-deploy/
```
