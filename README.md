# FinalTask1

## Задача 
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами

##  Описание алгоритма
 1. объявляется два массива: изначальный и вторый такой же длины. 
 2. Пишется метод, в котором цикл соразмерный длине массива, внутри цикла проверка условия ( <=3 ), если да элемент первого массива заносится в count элемент второго массива. 
 3. Переменная count чтобы поочередно закидывать из первого массива во второй и чтобы потом не было пробелов. 
 4. После присвоения увеличивается переменная count на 1 и возвращается к циклу for в котором i увеличивается на 1. И так проверяется до конца.

### Графическое представление метода в папке "Cхема".

### Реализация алгоритма по пути taskfinal/Program.cs