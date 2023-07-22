# Argo-cd Scifi Style


<img src="https://raw.githubusercontent.com/DaanV2/argocd-scifi-style/main/resources/preview.png" 
  style="width: 70vh; margin: 0 auto; border: 2px black solid; border-radius: 5px;"/>


## Installation

There are multiple ways to install this style.

### 1. ConfigMap
```yaml
apiVersion: v1
kind: ConfigMap
metadata:
  ...
  name: argocd-cm
data:
  ui.cssurl: "https://raw.githubusercontent.com/DaanV2/argocd-scifi-style/main/styles.css"
```

### 2. Helm values.yaml
```yaml
server:
  ...
  config:
    ...
    ui.cssurl: "https://raw.githubusercontent.com/DaanV2/argocd-scifi-style/main/styles.css"
```

### 3. Argocd Volume Mount

[documentation](https://argo-cd.readthedocs.io/en/stable/operator-manual/custom-styles/#argocd-styles-cm)