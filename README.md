# how to start
1. create namespace
kubectl create namespace monitoring

2. create clusterrole and clusterrolebindings
kubectl apply -f clusterRole.yaml

3. create config map(configurations for promethues will be added by mounting this files from configmap)
kubectl apply -f config-map.yaml

4. create deployment
kubectl apply -f prometheus-deployment.yaml

5. deploy kube-state-matrics
kubectl apply -f kube-state-metrics-configs/

6. deploy kube-state-matrics
kubectl apply -f kubernetes-alert-manager/

7. deploy kube-state-matrics
kubectl apply -f kubernetes-grafana/

# kubernetes prometheus Setup

https://devopscube.com/setup-prometheus-monitoring-on-kubernetes/
# kubernetes kube-state-matrics Setup

https://devopscube.com/setup-kube-state-metrics/

# kubernetes setup alert manager

https://devopscube.com/alert-manager-kubernetes-guide/
# kubernetes setup grafana

https://devopscube.com/setup-grafana-kubernetes/



