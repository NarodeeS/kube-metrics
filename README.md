Minimal Kubernetes pod monitoring using Prometheus, kube-state-metrics and Prometheus Operator<br>
Packed in Helm chart

Installation:
1. kubectl create -f ./manifests/setup/
2. kubectl create -f manifests/
3. kubectl create namespace "kube-metrics" (same as "namespace" in "values.yaml")
4. helm install kube-metrics kube-metrics --values kube-metrics/values.yaml