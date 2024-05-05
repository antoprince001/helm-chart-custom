# Helm Chart Custom

Helm chart implementation for nginx to learn writing own helm chart

## Helm Commands

### Command to create chart template project
```helm create nginx-chart```

### Create a release from the chart template
```helm install hello-world-1 ./helm-charts-custom```

### Examine a chart for possible issues
```helm lint ./helm-charts-custom```

### Locally render chart templates
```helm template ./helm-charts-custom```

### Dry run locally to test how chart release will be
```helm install hello-world-1 ./helm-charts-custom --dry-run```