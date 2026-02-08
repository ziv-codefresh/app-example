 # app-example
 
This repo is structured as an Argo CD source with two applications.
 
 - `argocd/applications/`: Argo CD `Application` manifests.
- `apps/`: Deployable Kubernetes manifests for each app.
  - Each app also includes a `values.yaml` placeholder for future Helm use.
# app-example