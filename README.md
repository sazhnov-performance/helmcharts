
# 🚀 Helm Charts - sazhnov-performance

This repository hosts Helm charts for deploying various services.

---

## 📦 Installation

### Add the Helm repository:
```
helm repo add openvts https://sazhnov-performance.github.io/helmcharts/
helm repo update
```

### Install the chart:
```
helm install openvts openvts/openvts
```

Replace `openvts` with your desired release name if needed.

---

## 📖 Usage Example
Once installed, you can check the release:
```
helm list
```

Upgrade if needed:
```
helm upgrade openvts openvts/openvts
```

Uninstall the release:
```
helm uninstall openvts
```

---

## 📝 Contributing
Feel free to open an issue or submit a pull request if you'd like to contribute.

---

## 📚 License
MIT
