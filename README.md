# Strøm Helm Charts

### Installing from the Chart Repository

The following command can be used to add the chart repository:

```console
helm repo add stroem https://stroem-hub.github.io/helm-charts
helm repo update
```

Once the chart has been added, install the charts:

```console
helm upgrade -i stroem-server stroem/stroem-server
helm upgrade -i stroem-worker stroem/stroem-worker
```