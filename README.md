# Итоговая контрольная работа по основному блоку
## Выполнила: Абдрашитова Лейла

**Урок 1. Контрольная работа**

*Данная работа необходима для проверки ваших знаний и навыков по итогу прохождения первого блока обучения на программе Разработчик. Мы должны убедится, что базовое знакомство с IT прошло успешно.*

**Задача алгоритмически не самая сложная, однако для полноценного выполнения проверочной работы необходимо:**

1. Создать репозиторий на GitHub
2. Нарисовать блок-схему алгоритма (можно обойтись блок-схемой основной содержательной части, если вы выделяете её в отдельный метод)
3. Снабдить репозиторий оформленным текстовым описанием решения (файл README.md)
4. Написать программу, решающую поставленную задачу
5. Использовать контроль версий в работе над этим небольшим проектом (не должно быть так, что всё залито одним коммитом, как минимум этапы 2, 3, и 4 должны быть расположены в разных коммитах)

**Задача: Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.**

Примеры:
[“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”]

[“1234”, “1567”, “-2”, “computer science”] → [“-2”]

[“Russia”, “Denmark”, “Kazan”] → []

![**Алгоритм решения задачи**](Диаграмма.png)

**Решение задачи было осуществлено посредством следующих методов:**

- - int CountItems(string[] array, int max) Метод подсчитывает число элементов массива, меньше или равных MAX

- - string[] NewArray(string[] array, int max) Cоздаёт новый массив и заполняем его элементами, длинна которых меньше MAX

- - void PrintArray(string[] array) Выводит массив в консоль в красивом формате

- - void Solving(string[] arr, int max) Выводит итоговый результат (исходный массив и новый массив)

## **Код программы**
![code](Скрин.png)
![code1](Скринн.png)

## **Результаты ввода:**
![Результат вывода в терминале:](Снимок.png)

## **Коммиты**
![code](screen.png)

