Введение

Этот документ предоставляет информацию о том, как использовать программу-компилятор комплексных чисел, разработанную на языке C#. Программа позволяет вычислять значения выражений, содержащих комплексные числа и основные арифметические операции. 

 

Установка и запуск

Требования: Для работы программы требуется установленная среда выполнения .NET.

Запуск: Запустите исполняемый файл программы.

 

Пользовательский интерфейс

Основное окно программы содержит: Поле ввода: Текстовое поле для ввода выражения с комплексными числами. Кнопка "пуск”: Запускает процесс компиляции и вычисления выражения. Поле вывода: Текстовое поле для отображения результата вычисления или сообщения об ошибке. 

Формат ввода выражений Программа поддерживает следующие форматы записи комплексных чисел: Декартова форма (a + bi): - действительная часть (действительное число). мнимая часть (действительное число). i - мнимая единица.\r\nПримеры: 2 + 3i, -1 - 0.5i, 0 + 1i, 5 + i (когда мнимая часть равна 1). Полярная форма (r * e^(iθ) или r(cos(θ) + i*sin(θ)) ): - модуль (действительное число). θ - аргумент в радианах или градусах (действительное число). Укажите, что поддерживается. Примеры: 5 * e^(i*pi/2), 2(cos(pi/4) + i*sin(pi/4)). (Требуется указать, как конкретно реализуется ввод полярной формы, если она есть.) Поддерживаемые операции: Сложение: + Вычитание: -Умножение: Деление: Примеры выражений:2 + 3i + 1 - i(4 + 2i) * (1 - i)\2
