# **Итоговая проверочная работа.**

**Задача.**

Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами

**Решение**

Объявляем два массива которые изначально одинаковой длинны. Затем метод - | void | в котором цикл соразмерный длине массива. Внутри цикла, проверка условия: меньше либо равна 3-м символа (<=3). Если ответ да то элемент первого массива заноситься в count элемент второго массива. Переменная count это счетчик. После присвоения count увеличивается на 1 и возвращается к циклу for в котором i увеличивается на 1. Так проверка идет по конца.