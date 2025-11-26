# Naming Conventions

## 📝 Python

| Tür | Format | Örnek |
|-----|--------|-------|
| Değişken | snake_case | user_name |
| Fonksiyon | snake_case | get_user_data |
| Sınıf | PascalCase | UserService |
| Sabit | UPPER_SNAKE_CASE | MAX_RETRY_COUNT |
| Modül | snake_case | user_service.py |
| Package | snake_case | data_processing |

## 📁 Dosya İsimlendirme

| Tür | Format | Örnek |
|-----|--------|-------|
| Python dosyası | snake_case | user_handler.py |
| Test dosyası | test_ prefix | test_user_handler.py |
| Config dosyası | lowercase | config.yaml |

## 🐳 Docker

| Tür | Format | Örnek |
|-----|--------|-------|
| Image | lowercase-hyphen | cv-parser-api |
| Container | lowercase-hyphen | cv-parser-api-prod |

## ☸️ Kubernetes

| Tür | Format | Örnek |
|-----|--------|-------|
| Namespace | lowercase | arge-prod |
| Deployment | lowercase-hyphen | cv-parser-deployment |
| Service | lowercase-hyphen | cv-parser-service |