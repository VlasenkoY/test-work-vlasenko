# Итоговая проверочная работа по курсу "Знакомство с языками программирования"

## Формулировка задачи:

Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна трём символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

## Пример:

* "hello", "2", ";-)"] -> ["2", ";-)"] 

* ["1234", "1567", "-2", "computer secience"] -> ["-2"]

* ["Russia", "Denmark", "Kazan"] -> []

## Алгоритм решения:

1. Объявляем два масива одинаковой длинны;

2. Объявляем метод;

3. Вносим цикл в метод для проверки условия <=3:

  * В случае выполнения условия элемент первого массива записывается во второй массив;
  * В случае не выполенения условия, приступаем к проверки следующего элемента первого массива;
4. Проверка осуществляется до тех пор, пока счетчик не будет равен количеству элементов массива;

5. Полученный результат во втором массиве выводится на экран.

## Схема программы находится в файле:

> **sheme.drawio.png**

## Код программы на языке C# находится в файле:

> **Program.cs**

