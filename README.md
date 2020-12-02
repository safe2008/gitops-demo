# gitops-demo

```bash
## https://argoproj.github.io/argo-cd/operator-manual/webhook/
❯ kubectl get secret argocd-secret -n argocd
❯ kubectl describe secrets/argocd-secret -n argocd
❯ kubectl get secret argocd-secret  -o jsonpath='{.data}' -n argocd

```