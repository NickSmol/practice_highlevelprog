# Задание 2, пункт а

Написать программу, которая на вход получает высоту пирамиды и выводит ее псевдосимволами в консоль.

# Описание: 

Программа состоит из двух файлов: `DaysInMonth` и `Main`. Для запуска программы воспользуйтесь файлом `Main`.

В файле `HollowPyramid` находится одноимённый класс, который генерирует и выводит пирамиду из псевдосимволов с помощью метода `printPyramid`.

Для этого в методе анализируется строка, длинной в высоту пирамиды `height`.Cначала выводится левая часть пирамиды. Для этого печатаются пустые символы для того, чтобы пирамида была ровная, затем выводит количество псевдосимволов, соответствующее ярусу(например, в первом ярусе - 1 символ и т.д). 

Далее печатается пустое пространство, заданное переменной `spaceBetween`. 

И в самом конце печатается правая часть пирамиды аналогии с левой частью, однако пустые символы уже не печатаются из-за ненадобности.

В файле `Main` осуществляется ввод высоты пирамиды и ширины пустого пространства между половинами пирамиды, а также вызов класса для анализа введённого значения.