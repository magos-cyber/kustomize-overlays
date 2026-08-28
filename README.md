# Kustomize Overlays

Kustomize bases and overlays for Kubernetes deployments.

## Structure

```
kustomize-overlays/
├── bases/
│   ├── deployment/
│   ├── service/
│   ├── ingress/
│   ├── configmap/
│   ├── secret/
│   └── cronjob/
└── overlays/
    ├── development/
    ├── staging/
    ├── production/
    ├── testing/
    └── canary/
```

## Usage

```bash
kubectl apply -k overlays/production
kubectl apply -k overlays/canary
```

## License

MIT
