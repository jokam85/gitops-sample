# Argocd, Keycloak, Airflow, Traefik, 

```
kubectl -n argocd port-forward svc/argocd-server 444:443
```

```
kubectl -n ingress port-forward svc/traefik 80:80
```
