## Initialize Flux

```yaml
flux bootstrap github \
  --owner=$GITHUB_USER \
  --repository=cluster-api-helm-chart \
  --branch=main \
  --path=./flux/capi \
  --personal
```

FYI: Flux identified changes whithin a Helm chart if the chart version is bumped. Issue [here](https://github.com/fluxcd/flux2/discussions/965).
