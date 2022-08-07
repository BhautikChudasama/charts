# charts

Repository contains necessary helm charts that deployed in kansas city VMs.

### Usages

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:
```shell
# Installation
helm repo add bhtk https://bhautikchudasama.github.io/charts

# Searching 
helm search repo bhtk

# Installation of chart
helm install bhtk-<chart-name> bhtk/<charts>

# Delete
helm delete bhtk-<chart-name>
```
