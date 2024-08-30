# iac-postgresql

## Apply Secrets

```shell
kubectl create secret generic postgres-secrets --from-env-file=.env
```
