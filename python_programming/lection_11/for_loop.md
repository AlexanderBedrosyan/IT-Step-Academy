# Въпроси на тема: For Loops в Python

## Въпрос 1:
Кой от следните синтаксиси е коректен `for` цикъл в Python?

```
# Избери всички верни:
a)
for i in range(5):
    print(i)

b)
for i to 5:
    print(i)

c)
for i in [1, 2, 3]:
    print(i)

d)
foreach i in range(5):
    print(i)

## Въпрос 2:
Какъв ще бъде изходът от следния код?

```
for char in "cat":
    print(char)
```

**Възможни отговори:**
- a) c a t  
- b) cat  
- c) c\n a\n t  
- d) 'c' 'a' 't' в един ред  

---

## Въпрос 3:
Колко пъти ще се изпълни тялото на този цикъл?

```
for i in range(2, 10, 2):
    print(i)
```

**Възможни отговори:**
- a) 4 пъти  
- b) 5 пъти  
- c) 3 пъти  
- d) 8 пъти  

---

## Въпрос 4:
Кой от следните кодове отпечатва всички ключове в речник `d = {"a": 1, "b": 2}`?


# Избери всички верни:
a)
for key in d:
    print(key)

b)
for key in d.keys():
    print(key)

c)
for value in d:
    print(value)

d)
for k, v in d:
    print(k)


---

## Въпрос 5:
Какъв е резултатът от следния код?

```
sum = 0
for i in [1, 2, 3]:
    sum += i
print(sum)
```

**Възможни отговори:**
- a) 6  
- b) 123  
- c) 0  
- d) 5  


## Въпрос 6:
Кой от следните кодове правилно отпечатва ключовете и стойностите в речник?

```
d = {"x": 10, "y": 20}

# Избери всички верни:
a)
for key, value in d.items():
    print(key, value)

b)
for k in d:
    print(k, d[k])

c)
for value in d:
    print(value)

d)
for x, y in d:
    print(x, y)
```

**Верни отговори:** a), b)

## Въпрос 7:
Какво ще отпечата този код?

```
for i in range(1, 6):
    print(i * "*")
```

**Възможни отговори:**
- a) * ** *** **** *****  
- b) ***** **** *** ** *  
- c) *
  \*\*
  \*\*\*
  \*\*\*\*
  \*\*\*\*\*  
- d) 1 2 3 4 5  

---

## Въпрос 8:
Коя конструкция ще обиколи всички елементи от списък с числа и ще удвои всяко число?

```
numbers = [1, 2, 3, 4]

# Избери всички верни:
a)
for num in numbers:
    print(num * 2)

b)
for num in range(numbers):
    print(num * 2)

c)
for i in range(len(numbers)):
    print(numbers[i] * 2)

d)
for x in numbers:
    print(x + x)
```

**Верни отговори:** a), c), d)

---

## Въпрос 9:
Кой от изброените примери ще обиколи само стойностите на речник?

```
d = {"a": 10, "b": 20}

# Избери всички верни:
a)
for val in d.values():
    print(val)

b)
for k in d:
    print(d[k])

c)
for val in d.items():
    print(val)

d)
for v in d:
    print(v)
```

---

## Въпрос 10:
Кой от следните кодове създава нов речник, в който стойностите от оригиналния са умножени по 10?

```
original = {"a": 1, "b": 2}
new_dict = {}

# Избери всички верни:
a)
for k, v in original.items():
    new_dict[k] = v * 10

b)
for k in original:
    new_dict[k] = original[k] * 10

c)
for v in original.values():
    new_dict[v] = v * 10

d)
for i in original:
    new_dict[i] = i * 10
```
