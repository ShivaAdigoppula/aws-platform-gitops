# aws-platform-gitops

Desired state of the Kubernetes clusters. Argo CD watches this repo and applies it.
Jenkins updates `manifests/demo-app/kustomization.yaml` (newTag) on every release of demo-app.