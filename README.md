# apache flink basic demo application

## How to Run

* cluster start(docker-compose)

```code
docker-compose up -d
```

* build job

```code
cd flink-app
mvn clean package
```

* submit job(use ui)

## Run with k8s

```code
kubectl apply -f deploy-k8s.yaml
```