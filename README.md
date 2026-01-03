# Helm Charts

Custom Helm charts repository hosted via GitHub Pages.

## Usage

```bash
helm repo add winsonsou https://winsonsou.github.io/helm-charts
helm repo update
```

## Available Charts

| Chart | Description |
|-------|-------------|
| istio-bookinfo | Istio Bookinfo sample application (images from registry.ntnxlab.local/library) |

### Install istio-bookinfo

```bash
helm install istio-bookinfo winsonsou/istio-bookinfo
```

See [charts/istio-bookinfo/README.md](charts/istio-bookinfo/README.md) for configuration options.
