# MONITORING SETUP #

## INSTALLATION
- To work with prometheus in kubernetes we need to install prometheus operator.

- Click on the "Install" and follow the steps to install prometheus operator at https://operatorhub.io/operator/prometheus

- We need to create a Service account, if you already have one serviceaccount we can use it.

- Create ClusterRole and ClusterRoleBinding.


## Configuring prometheus
- Create prometheus and prometheus-service objects
- Create serviceMonitor to scrape configs for services running in kubernetes.


- Use app dir to create a nginx deployment and expose its metrics to be scraped by our serviceMonitor