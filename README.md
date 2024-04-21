helm create nginx-chart #create

helm install hello-world-1 ./helm-charts-custom

kubectl get deployment

helm lint ./helm-charts-custom

helm template ./helm-charts-custom

helm install hello-world-1 ./helm-charts-custom --dry-run