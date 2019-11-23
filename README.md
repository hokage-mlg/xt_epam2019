# xt_net_web
This repository made for xt_net_web tasks

## Task 00
DEADLINE: 18.11.19, 18:00

### 0.1. SEQUENCE
Написать функцию, формирующую и возвращающую строку вида 1, 2, 3, … N (положительное число).
Значение N передаётся в функцию в качестве аргумента.

### 0.2. SIMPLE
Число считается простым, если его можно разделить без остатка только на единицу и на само себя (например, 7).
Необходимо написать функцию, определяющую, является ли заданное число N (положительное целое) простым.
Значение N передаётся в функцию в качестве аргумента.

### 0.3. SQUARE
Написать функцию, выводящую на экран квадрат из звёздочек со стороной равной N (положительное нечётное целое число). Центральная звёздочка должна отсутствовать.
Значение N передаётся в функцию в качестве аргумента.

### 0.4. ARRAY (TASK 0.5)
Написать программу, которая заполняет и сортирует многомерный массив. Постановка задачи: Пользователь вводит с клавиатуры число N (размерность массива), затем последовательно вводит N чисел – число элементов по каждой размерности. Программа должна: 1. Создать массив заданной размерности и указанной по размерностям длины. 2. Заполнить данный массив случайными числами из диапазона 0..100 (массив считаем целочисленным). 3. Вывести его на экран. 4. Отсортировать полученный массив. 5. Вывести на экран отсортированный массив.

## Task 01
DEADLINE: 22.11.19, 21:00

### 1.1. RECTANGLE
Написать программу, которая определяет площадь прямоугольника со сторонами a и b. Если пользователь вводит некорректные значения (отрицательные или ноль), должно выдаваться сообщение об ошибке. Возможность ввода пользователем строки вида «абвгд» или нецелых чисел игнорировать.

### 1.2. TRIANGLE
Написать программу, которая запрашивает с клавиатуры число N и выводит на экран следующее «изображение», состоящее из N строк:

### 1.3. ANOTHER TRIANGLE
Написать программу, которая запрашивает с клавиатуры число N и выводит на экран следующее «изображение», состоящее из N строк:

### 1.4. X-MAS TREE
Написать программу, которая запрашивает с клавиатуры число N и выводит на экран следующее «изображение», состоящее из N треугольников:

### 1.5. SUM OF NUMBERS
Если выписать все натуральные числа меньше 10, кратные 3 или 5, то получим 3, 5, 6 и 9. Сумма этих чисел будет равна 23. Напишите программу, которая выводит на экран сумму всех чисел меньше 1000, кратных 3 или 5.

### 1.6. FONT ADJUSTMENT
Для форматирования текста надписи можно использовать различные начертания: полужирное, курсивное и подчёркнутое, а также их сочетания. Предложите способ хранения информации о форматировании текста надписи и напишите программу, которая позволяет устанавливать и изменять начертание:

### 1.7. ARRAY PROCESSING
Написать программу, которая генерирует случайным образом элементы массива (число элементов в массиве и их тип определяются разработчиком), определяет для него максимальное и минимальное значения, сортирует массив и выводит полученный результат на экран.

### 1.8. NO POSITIVE
Написать программу, которая заменяет все положительные элементы в трёхмерном массиве на нули. Число элементов в массиве и их тип определяются разработчиком.

### 1.9. NON-NEGATIVE SUM
Написать программу, которая определяет сумму неотрицательных элементов в одномерном массиве. Число элементов в массиве и их тип определяются разработчиком.

### 1.10. 2D ARRAY
Элемент двумерного массива считается стоящим на чётной позиции, если сумма номеров его позиций по обеим размерностям является чётным числом (например, [1,1] — чётная позиция, а [1,2] — нет). Определить сумму элементов массива, стоящих на чётных позициях.

### 1.11. AVERAGE STRING LENGTH
Написать программу, которая определяет среднюю длину слова во введённой текстовой строке. Учесть, что символы пунктуации на длину слов влиять не должны. Регулярные выражения не использовать. И не пытайтесь прописать все символы-разделители ручками. Используйте стандартные методы классов String и Char.

### 1.12. CHAR DOUBLER
Написать программу, которая удваивает в первой введённой строке все символы, принадлежащие второй введённой строке.

## Task 02
DEADLINE: 29.09, пятница, 18:00

### 2.1.ROUND
Написать класс Round, задающий круг с указанными координатами центра, радиусом, а также свойствами, позволяющими узнать длину описанной окружности и площадь круга. Обеспечить нахождение объекта в заведомо корректном состоянии. Написать программу, демонстрирующую использование данного круга.

### 2.2.TRIANGLE
Написать класс Triangle, описывающий треугольник со сторонами a, b, cи позволяющий осуществить расчёт его площади и периметра. Написать программу, демонстрирующую использование данного треугольника.

### 2.3.USER
Написать класс User, описывающий человека (Фамилия, Имя, Отчество, Дата рождения, Возраст). Написать программу, демонстрирующую использование этого класса.

### 2.4.MY STRING
Написать свой собственный класс MyString, описывающий строку как массив символов. Реализовать для этого класса типовые операции (сравнение, конкатенация, поиск символов, конвертация из/в массив символов, ...).

### 2.5.EMPLOYEE
На основе класса User(см. задание 2.3) создать класс Employee, описывающий сотрудника фирмы. Дополнить класссвойствами«стаж работы» и «должность». Обеспечить нахождение класса в заведомо корректном состоянии.

### 2.6.RING
Создать класс Ring, описывающий кольцо, заданноекоординатами центра, внешним и внутренним радиусами, а также свойствами, позволяющими узнать площадь кольца и суммарную длину внешней и внутренней окружностей.Обеспечить нахождение класса в заведомо корректном состоянии.

### 2.7.VECTOR GRAPHICS EDITOR
Напишите заготовку для векторного графического редактора. Полная версия редактора должна позволять создавать и выводить на экран такие фигуры каклиния, окружность, прямоугольник, круг, кольцо. Заготовка, для упрощения, должна представлять собой консольное приложение со следующимфункционалом:
Создать фигуру выбранного типа по произвольным координатам;
Вывести фигуры на экран (для каждой фигуры вывести на консоль её тип и значения параметров).

### 2.8.GAME
Создайте иерархию классов и пропишите ключевые методы для компьютерной игры (без реализации функционала). Суть игры:
•Игрок может передвигаться попрямоугольному полю размером Widthна Height;
•На поле располагаются бонусы (яблоко, вишня и т.д.), которые игрок может подобрать для поднятия каких-либо характеристик;
•За игроком охотятся монстры (волки, медведи и т.д.), которые могут передвигаться покарте по какому-либо алгоритму;
•На поле располагаются препятствия разных типов (камни, деревья и т.д.), которые игрок и монстры должны обходить.
Цель игры —собрать все бонусы и не быть «съеденным» монстрами.
