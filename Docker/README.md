docker build -f ./Dockerfile . -t simple-mirror-k8s

kubectl apply -f Kubernetes/pod.yaml
kubectl apply -f Kubernetes/service.yaml