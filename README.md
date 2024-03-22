# Prometheus Tutorial

```
mkdir downloads
cd downloads
VERSION="2.49.1"
wget "https://github.com/prometheus/prometheus/releases/download/v${VERSION}/prometheus-${VERSION}.linux-amd64.tar.gz"
tar -xvzf "prometheus-${VERSION}.linux-amd64.tar.gz"
cd "prometheus-${VERSION}.linux-amd64"
rm -rf \
    console_libraries \
    consoles \
    LICENSE \
    NOTICE \
    prometheus.yml
```
