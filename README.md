# gitops-demo

```bash
## https://argoproj.github.io/argo-cd/operator-manual/webhook/
❯ kubectl get secret argocd-secret -n argocd
❯ kubectl describe secrets/argocd-secret -n argocd
❯ kubectl get secret argocd-secret  -o jsonpath='{.data}' -n argocd

## https://argoproj.github.io/argo-cd/operator-manual/declarative-setup/#app-of-apps
❯ kubectl apply -n argocd -f argo-resource/dev-nginx.yaml

```

![nginx](images/2020-12-02-16-45-47.png)