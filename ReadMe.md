Задача: Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.


1. Создаем блок ввода исходного массива и выводим его на экран.

2. Через цикл ищем и считаем элементы длина которых меньше либо равна 3 символам. для данной операции создаем функцию CheckArray.

3. Задаем numbers новую переменную в которую будем присваивать вычесленный элемент массива меньше либо равна 3 символа с помощью метода CheckArray

4. Задаем новый массив строк newArrayStrings, который формировуется перебором элементов массива arrayStrings, размером, равным переменной numbers

5. Формируем новый массива строк с помощью метода NewArray . Cравнением количества их элементов с переменной length и добавлением в массив newArray элемента, удовлетворяющего условию.

6. На выходе метода получается заполненный массив строк newArrayStrings, удовлетворяющий условию, что и является решением задачи. Выводим его на экран с помощью метода PrintArray.
