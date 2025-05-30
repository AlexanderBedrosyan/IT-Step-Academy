## 🧩 Изключения и работа с файлове в Python

### 🔥 Изключения (Exceptions)

**Какво е изключение?**  
Изключенията са грешки, които възникват по време на изпълнение на програмата и могат да прекъснат нейното изпълнение, ако не бъдат обработени.

**Чести типове изключения:**
- `IndexError` – опит за достъп до невалиден индекс в списък.
- `TypeError` – операция с несъвместими типове (напр. число + стринг).
- `ValueError` – грешна стойност за даден тип (напр. `int("abc")`).
- `SyntaxError` – грешен синтаксис в кода (открива се при стартиране).
- `KeyError` – липсващ ключ в речник.
- `ZeroDivisionError` – делене на нула.

---

### 🧪 Обработка на изключения: `try`, `except`

```python
try:
    number = int(input("Въведи число: "))
    print(10 / number)
except ValueError:
    print("Това не е число!")
except ZeroDivisionError:
    print("Не може да се дели на нула!")
```

**Допълнително:**
- `else:` – изпълнява се, ако няма грешка.
- `finally:` – винаги се изпълнява, независимо дали има грешка или не. *(по избор)*

---

### 🗂️ Работа с файлове в Python

```python
file = open("data.txt", "r")  # четене
content = file.read()
file.close()
```

**Режими за работа:**
- `"r"` – четене (read)
- `"w"` – запис (write), изтрива старото съдържание
- `"a"` – добавяне (append)
- `"x"` – създава нов файл, ако не съществува

**По-добра практика – с `with`:**

```python
with open("data.txt", "r") as file:
    content = file.read()
# файлът се затваря автоматично
```

---

### 💡 Добри практики:

- Винаги използвай `try-except` при работа с потребителски вход и файлове.
- При работа с файлове – предпочитай `with open(...)`.
- Не използвай `except:` без да уточниш вида на грешката – това крие реални проблеми.
- `raise` може да се използва за ръчно предизвикване на грешки при нужда.
