# Kustomize Overlays

Kustomize bases and overlays for Kubernetes deployments.

## Structure

```
kustomize-overlays/
├── bases/
│   ├── deployment/
│   ├── service/
│   └── ingress/
└── overlays/
    ├── development/
    ├── staging/
    └── production/
```

## Usage

```bash
kubectl apply -k overlays/production
```
