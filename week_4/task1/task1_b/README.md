# Задание 1, пункт б

Написать программу, которая реализует алгоритм расчета энтропии по Шеннону. Вывод ограничьте до двух знаков после запятой.

# Описание: 

Программа состоит из двух файлов: `ShanonEntropy` и `Main`. Для запуска программы воспользуйтесь файлом `Main`.

В файле `ShanonEntropy` находится одноимённый класс, в котором расчитывает энтропию. Для этого сначала расчитывается частота появления каждого символа в сообщении. Затем высчитыввается вероятность появления каждого символа и расчитывается энтропия по методу Шенона. После выполнения вычислений значение энтропии возвращается в класс `Main`.

Также в программе были учтены граничные условия, а именно:
1. Пустая строка: Если пользователь вводит пустую строку, программа выводит сообщение об ошибке и завершает выполнение.
2. Строки с уникальными символами: Если строка содержит только уникальные символы, энтропия будет максимальной.
3. Строки с повторяющимися символами: Программа корректно вычисляет энтропию, основываясь на частоте символов в строке.

В файле `Main` осуществляется ввод исследуемой строки, вызов метода для анализа введённого значения, а также вывод значения энтропии.