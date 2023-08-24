# chart-prometheus-salesforce-exporter

The helm chart for catalystsquad's [prometheus-salesforce-exporter](https://github.com/catalystsquad/prometheus-salesforce-exporter)


## Installation

```
helm repo add catalystsquad https://raw.githubusercontent.com/catalystsquad/charts/main
helm install catalystsquad/prometheus-salesforce-exporter \
  --set salesforce.baseUrl=https://myenv.salesforce.com \
  --set salesforce.clientId=abc123 \
  --set salesforce.clientSecret=ABC123 \
  --set salesforce.username=myuser@example.com \
  --set salesforce.password=securePassword
```
