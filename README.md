# Решение поставленной задачи
1. Объявляю начальный массив.
2. Объявляю новый массив с размеров - 0 , на случай если, в первом массиве не будет элементов, удовлетворяющих условие задачи.
3. Объявляю переменную index, и с ее помощью  помещаю элементы в новый массив по корректному индексу.
4. Объявляю переменную size(Размер), и с ее помощью увеличиваю новый массив на единицу  при нахождении элемента соответствующего условию задачи.
5. Создаю цикл for, в котором перебираю все элементы массива и проверяю их на условие задачи, если условие было истинным, то я увеличивал размер нового массива на единицу, и присваиваю туда элемент из массива array по индексу i (объявленный в цикле for) с помощью переменной index.