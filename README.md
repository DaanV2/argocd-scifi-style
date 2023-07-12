# Argo-cd Scifi Style


## Installation

**ConfigMap**
```yaml
apiVersion: v1
kind: ConfigMap
metadata:
  ...
  name: argocd-cm
data:
  ui.cssurl: "https://raw.githubusercontent.com/DaanV2/argocd-scifi-style/main/argocd-scifi-style.css"
```

**Helm values.yaml**
```yaml
config:
  ...
  styles: "https://raw.githubusercontent.com/DaanV2/argocd-scifi-style/main/argocd-scifi-style.css"
```