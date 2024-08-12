# kustomize-demo

```bash
curl -s "https://raw.githubusercontent.com/kubernetes-sigs/kustomize/master/hack/install_kustomize.sh"  | bash
```

# Applying Kustomize Configs - (Using kubectl kustomize integration)

```bash
kubectl apply -k .
kubectl apply -k overlays/dev/
kubectl apply -k overlays/prod/
```
