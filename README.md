# Review age script

```py
def can_buy(age)
  if age > 18:
    return("да")
```
---

# Ревьюер: Кузнецов Николай

**Замечание в логике**
  -Во второй строке в проверке if age вместо > лучше использовать =>
  -Сделать нормальные return'ы
```py
def can_buy(age)
  if age => 18:
    return("да")
```
---
**Исправленный**
```py
def can_buy(age):
    if age >= 18:
        return True
    return False
```
