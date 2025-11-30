# DOCUMENTATION

## Функція `celsius_to_fahrenheit()`
```python
def celsius_to_fahrenheit(celsius):
    """Конвертує Цельсій у Фаренгейт"""
    return (celsius * 9/5) + 32
```

### Параметри:
- **celsius** (float): Значення температури у °C

### Повертає:
- **float**: Температура у °F

### Приклад:
```python
result = celsius_to_fahrenheit(25)
print(result)  # 77.0
```

---

## Функція `fahrenheit_to_celsius()`
```python
def fahrenheit_to_celsius(fahrenheit):
    """Конвертує Фаренгейт у Цельсій"""
    return (fahrenheit - 32) * 5/9
```

### Параметри:
- **fahrenheit** (float): Значення температури у °F

### Повертає:
- **float**: Температура у °C

### Приклад:
```python
result = fahrenheit_to_celsius(32)
print(result)  # 0.0
```

---

## Функція `celsius_to_kelvin()`
```python
def celsius_to_kelvin(celsius):
    """Конвертує Цельсій у Кельвін"""
    return celsius + 273.15
```

### Параметри:
- **celsius** (float): Значення температури у °C

### Повертає:
- **float**: Температура у K

### Приклад:
```python
result = celsius_to_kelvin(25)
print(result)  # 298.15
```

---

## Функція `kelvin_to_celsius()`
```python
def kelvin_to_celsius(kelvin):
    """Конвертує Кельвін у Цельсій"""
    return kelvin - 273.15
```

### Параметри:
- **kelvin** (float): Значення температури у K

### Повертає:
- **float**: Температура у °C

### Приклад:
```python
result = kelvin_to_celsius(300)
print(result)  # 26.85
```

---

## Функція `fahrenheit_to_kelvin()`
```python
def fahrenheit_to_kelvin(fahrenheit):
    """Конвертує Фаренгейт у Кельвін"""
    celsius = fahrenheit_to_celsius(fahrenheit)
    return celsius_to_kelvin(celsius)
```

### Параметри:
- **fahrenheit** (float): Значення температури у °F

### Повертає:
- **float**: Температура у K

### Приклад:
```python
result = fahrenheit_to_kelvin(32)
print(result)  # 273.15
```
