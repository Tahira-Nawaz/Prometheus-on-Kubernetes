--------commands-----------
kubectl create namespace prometheus
kubectl apply -f prometheus-config.yaml -n prometheus
kubectl apply -f prometheus-deployment.yaml -n prometheus
kubectl apply -f prometheus-service.yaml -n prometheus
kubectl get service prometheus-service -n prometheus
