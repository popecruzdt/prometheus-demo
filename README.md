# prometheus-demo

Deploys Prometheus to a Kubernetes cluster with some example Prometheus Exporters.

`kubectl apply -f prometheus-namespace.yaml`
`kubectl apply -f prometheus-configmap.yaml`
`kubectl apply -f prometheus-deployment.yaml`
`kubectl apply -f prometheus-node-exporter.yaml`
`kubectl apply -f prometheus-redis.yaml`
`kubectl apply -f prometheus-redis-exporter.yaml`

If you plan to reference the yaml files directly from this repo, be sure to link to the RAW content.
`kubectl apply -f https://raw.githubusercontent.com/popecruzdt/prometheus-demo/main/prometheus-namespace.yaml`
