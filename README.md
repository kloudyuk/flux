# flux

GitOps repo for [Flux](https://fluxcd.io/) manifests

## Flux Bootstrap

### Dependencies

- [go-task](https://taskfile.dev/) (`brew install go-task`)

### Bootstrap

To bootstrap a new cluster, run the following, replacing `CLUSTER` with the name of your cluster:

```sh
task bootstrap -- CLUSTER
```
