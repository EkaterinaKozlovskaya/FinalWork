Добрый день!
Решение итоговой задачи основного блока.
Задача: Написать программу, которая из окрашенной строки массива формирует новый массив из строки, длина которой меньше, либо равна 3 символам. Первоначальный массив можно ввести с помощью клавиатуры, либо задать начало выполнения алгоритма. При необходимости не рекомендуется использовать коллекции, лучше обойтись исключительно массивами.

Схема решения задачи:

(newPlan.png)

1. Сначала:
* массив arrayStart , из которого будет взята информация;
* список listResult , в который будут добавлены подсоединения под наши условия значения;
* переменная maxSizeWord , которая для нашей задачи равна 3 и означает размер строки, который мы добавим в список.
2. Запускаем цикл, идущий по массиву.

3. В цикле проводится проверка, если размер элемента массива равен или меньше 3, то он добавляется в наш список.

4. Создаем в начале программный метод, который выводит в терминале массив в человекочитаемом формате.

5. Превращаем список со значениями подходящими под условия нашей выборки в массиве.

6. Печатаем оба массива ранее созданным методом.