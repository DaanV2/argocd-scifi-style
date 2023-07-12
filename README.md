# Argo-cd Scifi Style


## Installation

```yaml
---
apiVersion: v1
kind: ConfigMap
metadata:
  ...
  name: argocd-cm
data:
  ui.cssurl: "https://raw.githubusercontent.com/DaanV2/argocd-scifi-style/main/style.css"
```