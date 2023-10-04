# Math Formulas
## Area
- _Circle: S = πR²_
- _Rectangle: S = ab_
- _Square: S = a²_

## Perimeter
- _Circle: P = 2πR_
- _Rectangle: P = 2a + 2b_
- _Square: P = 4a_

# General Description of the Solution
- Прокомментировал функции в файлах
- Сделал коммит с сообщением о комментировании
- Отредактировал README.md
- Сделал коммит с сообщением о редактировании

# Functions
## Circle
```py
def area(r):
    '''Принимает значение радиуса окружности,
       возвращает площадь окружности.'''
    return math.pi * r * r
```
- _Input: 5_
- _Output: 25π_
```py
def perimeter(r):
    '''Принимает значение радиуса окружности,
       возвращает периметр окружности.'''
    return 2 * math.pi * r
```
- _Input: 4_
- _Output: 8π_
## Rectangle
```py
def area(a, b):
    '''Принимает значения двух соседних сторон прямоугольника,
       возвращает площадь прямоугольника.'''
    return a * b
```
- _Input: 6, 3_
- _Output: 18_
```py
def perimeter(a, b):
    '''Принимает значения двух соседних сторон прямоугольника,
       возвращает периметр прямоугольника.'''
    return 2 * (a + b)
```
- _Input: 7, 5_
- _Output: 24_
## Square
```py
def area(a):
    '''Принимает значение стороны квадрата,
       возвращает площадь квадрата.'''
    return a * a
```
- _Input: 9_
- _Output: 81_
```py
def perimeter(a):
    '''Принимает значение стороны квадрата,
       возвращает периметр квадрата.'''
    return 4 * a
```
- _Input: 8_
- _Output: 32_
## Triangle
```py
def area(a, h):
    '''Принимает значения стороны треугольника и высоты, проведенной к ней,
       возвращает площадь треугольника.'''
    return a * h / 2
```
- _Input: 4, 6_
- _Output: 12_
```py
def perimeter(a, b, c):
    '''Принимает значения всех сторон треугольника,
       возвращает периметр треугольника.'''
    return a + b + c
```
- _Input: 7, 9, 3_
- _Output: 19_

# Project History
```
commit 8ba9aeb3cea847b63a91ac378a2a6db758682460
Author: smartiqa <info@smartiqa.ru>
Date:   Thu Mar 4 14:54:08 2021 +0300

    L-03: Circle and square added

```
```
commit d078c8d9ee6155f3cb0e577d28d337b791de28e2 (upstream/main, upstream/HEAD)
Author: smartiqa <info@smartiqa.ru>
Date:   Thu Mar 4 14:55:29 2021 +0300

    L-03: Docs added

```
```
commit 34b1811f552a301f0a0636ee91468cc4a952736d
Author: sugarvanya <vanyalovesugar@gmail.com>
Date:   Wed Oct 4 03:06:19 2023 +0300

    added rectangle.py

```
```
commit 23836e2b0329ef3d75259ff79f92a7e1aa23e768
Author: sugarvanya <vanyalovesugar@gmail.com>
Date:   Wed Oct 4 03:11:27 2023 +0300

    added triangle.py and edited rectangle.py

```