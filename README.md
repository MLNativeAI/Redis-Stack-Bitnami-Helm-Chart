# Cloned from bitnami/redis version - 17.11.7
[Redis-Stack-Bitnami-Helm-Chart](https://github.com/kamalkraj/Redis-Stack-Bitnami-Helm-Chart)

An internal fork so that we can store the chart in a repo, instead of cloning it when needed

# Chart instructions

`helm package .`
`az acr login --name mlnative`
`helm push redis-17.11.7.tgz oci://mlnative.azurecr.io/helm`

