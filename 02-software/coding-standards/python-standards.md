# Python Standards

## 📏 Genel Kurallar

- PEP 8 standartlarına uyulmalı
- Maximum satır uzunluğu: 120 karakter
- Indentation: 4 space

## 🔧 Linting

```bash
# Kullanılan araçlar
pip install flake8 black isort

# Format
black .
isort .

# Check
flake8 .
```

## 📁 Proje Yapısı

```
project/
├── src/
│   ├── __init__.py
│   ├── main.py
│   └── utils/
├── tests/
├── requirements.txt
└── README.md
```

## 📝 Docstring

```python
def example_function(param1: str, param2: int) -> bool:
    """
    Fonksiyon açıklaması.

    Args:
        param1: Parametre açıklaması
        param2: Parametre açıklaması

    Returns:
        Dönüş değeri açıklaması
    """
    pass
```

## 🔗 Kaynaklar

- [PEP 8](https://peps.python.org/pep-0008/)