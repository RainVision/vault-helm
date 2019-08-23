## Helm Template

helm template ./vault-helm --values values.yaml --output-dir ./vault-manifest --name vault --namespace vault

## Helm Install 

helm install --values values.yaml --name vault --namespace vault .


## Helm Upgrade

helm upgrade vault . --values values.yaml


## Helm Delete

helm delete vault --purge