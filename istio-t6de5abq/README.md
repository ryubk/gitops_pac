> Official Chart : https://github.com/istio/istio/tree/1.20.2/manifests/charts

## ■ Prerequisites

```
kubectl create namespace istio-system
```

## ■ Install
```
helm install istio . -n istio-system
```

## ■ Components
### 1. base
### 2. istio-discovery
### 3. istio-egress
### 4. istio-ingress

<br>
Istio Official Chart does not support the installation of all components at once.
<br>
Istio provides documents only individual component installation.
<br>
SDS`s Istio Helm chart provides subcharts so that components of the istio can be installed at once.
<br>
Each component keeps the official code, and provides control with values.yaml only.