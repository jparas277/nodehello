# nodehello

BUILD IMAGE 

docker build -t jparas/nodehello -f Dockerfile.prod .
helm create nodehello
helm install nodehello nodehello -n <namespace>
kubectl apply -f argo.yaml

