# prometheus-monitoring-stack

<img width="549" height="382" alt="image" src="https://github.com/user-attachments/assets/5c22d83d-eef9-4df5-a0e0-045e3ccee3cb" />

## Installation

Add the Helm repository and install kube-prometheus-stack:

```sh
helm repo add prometheus-community https://prometheus-community.github.io/helm-charts
helm repo update

helm install my-kube-prometheus prometheus-community/kube-prometheus-stack -n monitoring
