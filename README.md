1. Создать репозиторий на GitHub
2. Нарисовать блок-схему алгоритма (можно обойтись блок-схемой основной содержательной части, если вы выделяете её в отдельный метод)
3. Снабдить репозиторий оформленным текстовым описанием решения (файл README.md)
4. Написать программу, решающую поставленную задачу
5. Использовать контроль версий в работе над этим небольшим проектом (не должно быть так, что всё залито одним коммитом, как минимум этапы 2, 3, и 4 должны быть расположены в разных коммитах)

**Описание решения задачи**

Создаём метод PrintArray для вывода значений массива
Путем ввода значения volume, задаём размер массива
Объявляем массив Array
Циклом for (int i = 0; i < volume; i++) наполняем массив значениями, которые вводим с клавиатуры:
Объявляем массив NewArray, такой же длины как и Array
Объявляем две переменные length и count. length - количество символов в элементе, count - счетчик для определения длины финльного массива
Выполняем цикл for (int i = 0; i < volume; i++) Цикл выполняется столько раз, сколько элементов в массиве, при этом, при каждой итерации проверяется условие: if (Array[i].Length <= length) в котором проверяется сколько символов в текущем элементе массива, и если количество символов меньше или равно заданному количеству length, то значение записывается в элемент массива.
Делаем отступ строки Console.WriteLine() и методом PrintArray выводим массив NewArray на экран.