# 📌 Вградени функции и модули: math и random

## ✅ `ceil(x)`
Окръгля числото **нагоре** до най-близкото цяло.
```python
import math
print(math.ceil(3.1))   # 4
print(math.ceil(-1.8))  # -1
```

---

## ✅ `floor(x)`
Окръгля числото **надолу** до най-близкото цяло.
```python
print(math.floor(3.9))   # 3
print(math.floor(-1.2))  # -2
```

---

## ✅ `modf(x)`
Разделя числото на дробна и цяла част. Връща **tuple**: (дробна_част, цяла_част)
```python
print(math.modf(5.75))  # (0.75, 5.0)
```

---

## ✅ `trunc(x)`
Премахва дробната част (не закръгля, просто отрязва).
```python
print(math.trunc(4.9))   # 4
print(math.trunc(-3.7))  # -3
```

---

## ✅ `factorial(x)`
Изчислява **факториел** (x!) на цяло положително число.
```python
print(math.factorial(5))  # 120 → 5*4*3*2*1
```

---

# 🎲 Модул `random`

## ✅ `random()`
Връща произволно число между `0.0` и `1.0`.
```python
import random
print(random.random())  # 0.483921..., различно всеки път
```

---

## ✅ `randint(a, b)`
Връща произволно **цяло число** между `a` и `b` (включително).
```python
print(random.randint(1, 10))  # напр. 7
```

---

## ✅ `randrange(start, stop, step)`
Подобно на `range()`, но избира **произволен елемент** от него.
```python
print(random.randrange(0, 10, 2))  # напр. 4 или 6
```

---

## ✅ Пример за комбинирано използване:
```python
import random
import math

x = random.uniform(1, 10)
print("Число:", x)
print("Ceil:", math.ceil(x))
print("Floor:", math.floor(x))
```

---

📌 **Забележка:**  
- Функциите `ceil`, `floor`, `modf`, `trunc`, `factorial` са от модула `math`.
- За да ги ползваш: `import math`
- Функциите `random`, `randint`, `randrange` са от модула `random`.
