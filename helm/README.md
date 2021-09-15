# Helm Chart

Helm chart called 'kube2ram' is provided in the charts directory to help deploy and install **kube2ram** into your cluster.

## Usage
Deploy with the standard Helm install command:

```
helm upgrade --install  kube2ram ./charts -n your-namespace -f example-values.yaml
```
