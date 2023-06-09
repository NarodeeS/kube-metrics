Minimal Kubernetes pod monitoring using Prometheus, kube-state-metrics and Prometheus Operator<br>
Packed in Helm chart

Installation:
1. kubectl create -f ./crd/
2. helm install kube-metrics kube-metrics --values kube-metrics/values.yaml