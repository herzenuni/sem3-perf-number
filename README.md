# sem3-perf-number
Определите, является ли заданное натуральное число совершенным, т.е. равным сумме всех своих (положительных) делителей, кроме самого этого числа (например, число 6 является совершенным числом, так как ```6=1+2+3```). 

Приведем еще несколько совершенных чисел: 28, 496, 8128, 33550336, 8589869056. 
Если сумма делителей числа больше искомого числа, то такое число называется _избыточным_, а если меньше — _дефектным_ числом.

Используйте приведенные выше совершенные числа как проверочные данные для тестов.

Оформите решение в файле main.py внутри функции:
```python

is_perfect_number(number):
    pass # ваш код располагается здесь
    
    # return True or False
```
Требования к функции и программе: 
- должна возвращать значение ```True``` или ```False``` для переданного в неё числа ```number```;
- должна поднимать исключение TypeError, если на вход ей было передано не натуральное число; 
- тесты должны содержатся в блоке кода после ```if __name__ == '__main__':```;
- функция должна содержать описание, выполненное с помощью docstring.
