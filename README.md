### Kustomize

Download kustomize:
- https://github.com/kubernetes-sigs/kustomize/releases
- Homebrew: brew install kustomize

### Apply to kubernetes
```
kubectl apply -k overlays/dev
kubectl apply -k overlays/prod
```

### Delete
```
kubectl delete -k overlays/dev
kubectl delete -k overlays/prod
```

Maintainer: [Adhithia Irvan Rachmawan](https://www.linkedin.com/in/adhithia/ "Adhithia Irvan Rachmawan")