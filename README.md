# -2-Python-Mathematical-Logical-and-Membership-Operators
## Арифметические операции в Python для числовых типов данных
[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=1B9C0B&width=435&lines=%23+arithmetic+;print(6+*+(2+%2B+2));c+%3D+2+**+4)](https://git.io/typing-svg)

В Python для числовых типов данных (таких как целые числа int, числа с плавающей запятой float и комплексные числа complex) доступны различные математические операции. Вот основные из них: <br> <br>
Таблица с математическими операторами: <br>
| Оператор | Описание | Пример использования |
|----------|----------|----------------------|
| `+`      | Сложение. Суммирует значения слева и справа от оператора. | 1) `5 + 5`, вывод: `10`<br>2) `a + b`, вывод зависит от значений переменных `a` и `b`. |
| `-`      | Вычитание. Вычитает значение справа от оператора из значения слева от оператора. | 1) `10 - 3`, вывод: `7`<br>2) `a - b`, вывод зависит от значений переменных `a` и `b`. |
| `*`      | Умножение. Умножает значения слева и справа от оператора. | 1) `4 * 3`, вывод: `12`<br>2) `a * b`, вывод зависит от значений переменных `a` и `b`. |
| `/`      | Деление. Делит значение слева от оператора на значение справа от оператора, результат – число с плавающей точкой. | 1) `10 / 2`, вывод: `5.0`<br>2) `a / b`, вывод зависит от значений переменных `a` и `b`. |
| `//`     | Целочисленное деление. Делит значение слева от оператора на значение справа от оператора, результат – целая часть от деления. | 1) `10 // 3`, вывод: `3`<br>2) `a // b`, вывод зависит от значений переменных `a` и `b`. |
| `%`      | Остаток от деления. Возвращает остаток от деления значения слева от оператора на значение справа от оператора. | 1) `10 % 3`, вывод: `1`<br>2) `a % b`, вывод зависит от значений переменных `a` и `b`. |
| `**`     | Возведение в степень. Возводит значение слева от оператора в степень, указанную справа от оператора. | 1) `2 ** 3`, вывод: `8`<br>2) `a ** b`, вывод зависит от значений переменных `a` и `b`. |


**Сложение** (+): Складывает два числа. <br>
`print(5 + 3)  # 8` <br><br>
**Вычитание** (-): Вычитает одно число из другого. <br>
`print(5 - 3)  # 2` <br><br>
**Умножение** (*): Умножает два числа. <br>
`print(5 * 3  # 15)` <br><br>
**Деление** (/): Делит одно число на другое, результатом всегда будет float. <br>
`print(5 / 3 ) # 1.6666666666666667` <br><br>
**Целочисленное деление** (//): Делит два числа, возвращает только целую часть. <br>
`print(5 // 3)  # 1` <br><br>
**Остаток от деления** (%): Возвращает остаток от деления. <br>
`print(5 % 3)  # 2` <br><br>
**Возведение в степень** (**): Возводит число в степень. <br>
`print(5 ** 3)  # 125` <br>

Так можно делать и со значением в переменных, например: <br>
```
a = 7
b = 4
print(a - b)  # 3
```
Ещё пример:
```
number_1 = 13
number_2 = 2
print(number_1 / number_2)  # 6.5
print(number_1 // number_2)  # 6 
print(number_1 % number_2)  # 1
```

## Арифметические операции в Python для нечисловых типов данных

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=1B9C0B&width=435&lines=my_str+%3D+%22Hello%22;my_str+%2B%3D+%22!%22;print(%5B0%2C+1%5D+%2B+%5B2%2C+3%5D))](https://git.io/typing-svg)

Арифметические операции в Python применимы не только к числовым типам данных, но и к некоторым нечисловым типам, таким как строки (str), списки (list), кортежи (tuple) и множества (set). Вот как они работают:

**1. Конкатенация строк (str)** <br>
Сложение (+):

Оператор `+` используется для объединения (конкатенации) строк.
```
s1 = "Hello"
s2 = "World"
result = s1 + " " + s2  # result = "Hello World"
```
Умножение (*):

Оператор `*` используется для повторения строки заданное количество раз.
```
s = "Ha"
result = s * 3  # result = "HaHaHa"
```
**2. Операции со списками (list)** <br>
Сложение (+):

Оператор `+` используется для объединения двух списков в один.
```
list1 = [1, 2, 3]
list2 = [4, 5, 6]
result = list1 + list2  # result = [1, 2, 3, 4, 5, 6]
```
Умножение (*):

Оператор `*` используется для повторения элементов списка.
```
list1 = [1, 2, 3]
result = list1 * 2  # result = [1, 2, 3, 1, 2, 3]
```
**3. Операции с кортежами (tuple)** <br>
Сложение (+):

Оператор `+` используется для объединения двух кортежей в один.
```
tuple1 = (1, 2, 3)
tuple2 = (4, 5, 6)
result = tuple1 + tuple2  # result = (1, 2, 3, 4, 5, 6)
```
Умножение (*):

Оператор `*` используется для повторения элементов кортежа.
```
tuple1 = (1, 2, 3)
result = tuple1 * 2  # result = (1, 2, 3, 1, 2, 3)
```
**4. Операции с множествами (set)** <br>
Объединение (|):

Оператор `|` используется для объединения двух множеств, возвращая новое множество с уникальными элементами.
```
set1 = {1, 2, 3}
set2 = {3, 4, 5}
result = set1 | set2  # result = {1, 2, 3, 4, 5}
```
Пересечение (&):

Оператор `&` используется для нахождения пересечения двух множеств.
```
set1 = {1, 2, 3}
set2 = {3, 4, 5}
result = set1 & set2  # result = {3}
```
Разность (-):

Оператор `-` используется для нахождения разности между двумя множествами.
```
set1 = {1, 2, 3}
set2 = {3, 4, 5}
result = set1 - set2  # result = {1, 2}
```
Симметрическая разность (^):

Оператор `^` используется для нахождения элементов, которые присутствуют в одном из множеств, но не в обоих.
```
set1 = {1, 2, 3}
set2 = {3, 4, 5}
result = set1 ^ set2  # result = {1, 2, 4, 5}
```

## Оператор присвоения

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=1B9C0B&width=435&lines=variable+%3D+value;x+%3D+8;y+%3D+12;luck+%3D+%22%F0%9F%8D%80%22)](https://git.io/typing-svg)

Оператор, который уже вам знаком из предыдущего репозитория.
>Присваивание: Когда вы присваиваете значение переменной (x = 10), Python создаёт объект с значением 10 и связывает его с именем x.

Наиболее полное определение:
Оператор присвоения в Python используется для присвоения значения переменной. Основной оператор присвоения – это знак равенства =. Кроме того, существуют составные операторы присвоения, которые комбинируют операцию присвоения с арифметическими операциями.

**Основной оператор присвоения** (`=`) <br>
Присваивает значение, указанное справа, переменной слева. <br>
Пример: <br>
```
x = 10  # Переменной x присваивается значение 10
```
<br>

Но совершенно необязательно присваивать только одно значение и не изменять его. В ходе выполнения программы чиисла могут меняться.

## Составные операторы присвоения

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=1B9C0B&width=435&lines=a+%3D+7;b+%3D+3;a+%2B%3D+b)](https://git.io/typing-svg)

Составные операторы присвоения упрощают запись и выполнение арифметических операций с переменными. Они включают в себя арифметическую операцию и оператор присвоения.

`+=`: Прибавляет значение справа к переменной и присваивает результат этой же переменной.
```
x = 5
x += 3  # Эквивалентно x = x + 3, теперь x равно 8
```
`-=:` Вычитает значение справа из переменной и присваивает результат этой же переменной.
```
x = 5
x -= 2  # Эквивалентно x = x - 2, теперь x равно 3
```
`*=`: Умножает переменную на значение справа и присваивает результат этой же переменной.
```
x = 5
x *= 3  # Эквивалентно x = x * 3, теперь x равно 15
```
`/=`: Делит переменную на значение справа и присваивает результат этой же переменной.
```
x = 10
x /= 2  # Эквивалентно x = x / 2, теперь x равно 5.0
```
`//=`: Выполняет целочисленное деление переменной на значение справа и присваивает результат этой же переменной.
```
x = 10
x //= 3  # Эквивалентно x = x // 3, теперь x равно 3
```
`%=`: Делит переменную на значение справа и присваивает остаток от деления этой же переменной.
```
x = 10
x %= 3  # Эквивалентно x = x % 3, теперь x равно 1
```
`**=`: Возводит переменную в степень значения справа и присваивает результат этой же переменной.
```
x = 2
x **= 3  # Эквивалентно x = x ** 3, теперь x равно 8
```

| Краткая форма       | Полная форма           |
|---------------------|------------------------|
| `x += 1`            | `x = x + 1`            |
| `x -= 1`            | `x = x - 1`            |
| `x *= 2`            | `x = x * 2`            |
| `x /= 2`            | `x = x / 2`            |
| `x //= 2`           | `x = x // 2`           |
| `x %= 3`            | `x = x % 3`            |
| `x **= 3`           | `x = x ** 3`           |

Ещё примеры:
```
number_1 = 7
number_2 = 4
number_1 += number_2
print(number_1) 
```
👆 здесь, начиная с 3 строки кода, переменная number_1 имеет значение 11.
Стоит обратить внимание, что и тип данных тоже может поменяться, к примеру:
```
num_1 = 8
num_2 = 2.6
num_1 += num_2
print(num_1)
```
Теперь, `num_1` - это число с плавающей точкой (float).
Исходя из этого, немного дополним прошлую тему и узнаем, как ещё можно поменять тип данных.

## Изменение типов данных


В Python можно явно и неявно изменять тип данных переменной, что называется "приведением типов". Давайте рассмотрим, как это работает для различных типов данных.

**1. Из int в float**
Неявное приведение (при выполнении операций):
Когда вы выполняете арифметическую операцию между int и float, результат автоматически будет типа float.
```
x = 5   # int
y = 2.5 # float
z = x + y  # z станет float, z = 7.5
```
Явное приведение:
Для явного приведения целого числа в число с плавающей точкой используется функция float().
```
x = 5   # int
y = float(x)  # y станет float, y = 5.0
```
**2. Из float в int**
Неявное приведение:
В Python не происходит автоматического приведения float в int при выполнении операций. Если нужно преобразовать float в int, это нужно сделать явно.
Явное приведение:
Для явного приведения числа с плавающей точкой в целое используется функция int(). Это отбрасывает дробную часть.
```
x = 7.9  # float
y = int(x)  # y станет int, y = 7
```
**3. Из str в int или float**
Явное приведение:
Строка, содержащая числовое значение, может быть приведена к int или float с использованием функций int() и float().
При этом строка должна состоять только из цифр (для int) или содержать допустимый формат числа (для float), иначе произойдет ошибка.
```
s = "42"
x = int(s)  # x станет int, x = 42
```
```
s = "3.14"
y = float(s)  # y станет float, y = 3.14
```
Ошибка:
```
s = "abc"
x = int(s)  # Вызовет ValueError: invalid literal for int()
```
**4. Из int или float в str**
Явное приведение:
Для преобразования числового значения в строку используется функция str().
```
x = 42   # int
s = str(x)  # s станет str, s = "42"
```
```
y = 3.14  # float
s = str(y)  # s станет str, s = "3.14"
```
**5. Из bool в int или str**
Явное приведение:
Логическое значение True можно привести к 1, а False к 0.
```
b = True
x = int(b)  # x станет int, x = 1
```
```
b = False
s = str(b)  # s станет str, s = "False"
```
**6. Из int в bool**
Неявное приведение:
В логическом контексте (например, в условных операторах) числа автоматически приводятся к типу bool: 0 становится False, а любое ненулевое число — True.
```
x = 0
print(bool(x))  # Вывод: False
```
```
x = 42
print(bool(x))  # Вывод: True
```
Явное приведение:
Можно явно привести int к bool.
```
x = 0
b = bool(x)  # b станет False
```
```
y = 42
b = bool(y)  # b станет True
```
