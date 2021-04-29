## Initialize Flux

```yaml
flux bootstrap github \
  --owner=$GITHUB_USER \
  --repository=cluster-api-helm-chart \
  --branch=main \
  --path=./flux/capi \
  --personal
```

