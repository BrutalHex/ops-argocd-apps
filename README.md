# Introduction
The `ops-argocd-apps` repository acts as a storage location for YAML files defining ArgoCD applications.  
Application files should follow the naming pattern: `argocd-<app-name>.yaml`.  
ArgoCD continuously monitors this repository and creates applications in Kubernetes based on the files it detects.  
For more details, refer to the [ops-infra](https://github.com/BrutalHex/ops-infra) repository.
