
# 🚀 Helm Charts - sazhnov-performance

This repository hosts Helm charts for deploying various services.

---

## 📦 Installation

### Add the Helm repository:
```
helm repo add my-repo https://sazhnov-performance.github.io/helmcharts/
helm repo update
```

### Install the chart:
```
helm install openvts my-repo/openvts
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
helm upgrade openvts my-repo/openvts
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
