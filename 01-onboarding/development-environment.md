# Geliştirme Ortamı Kurulumu

## 🐍 Python Ortamı

```bash
# Python 3.10+ kurulumu
# pyenv veya sistem python kullanabilirsin

# Virtual environment
python -m venv venv
source venv/bin/activate  # Linux/Mac
.\venv\Scripts\activate   # Windows
```

## 🐳 Docker

```bash
# Docker Desktop kurulumu
# https://www.docker.com/products/docker-desktop

# Kurulum kontrolü
docker --version
docker-compose --version
```

## ☸️ Kubernetes

```bash
# kubectl kurulumu
# https://kubernetes.io/docs/tasks/tools/

# Cluster bağlantısı için Can Demir ile iletişime geç
```

## 📦 Gerekli Araçlar

| Araç | Açıklama | Kurulum |
|------|----------|---------|
| VS Code | IDE | https://code.visualstudio.com/ |
| Git | Versiyon kontrolü | https://git-scm.com/ |
| Azure CLI | Azure işlemleri | https://docs.microsoft.com/cli/azure/install-azure-cli |

## 🔧 VS Code Extensions

- Python
- Docker
- Remote - Containers
- GitLens
- YAML

## ❓ Sorun mu var?

→ [Troubleshooting](../07-troubleshooting/)