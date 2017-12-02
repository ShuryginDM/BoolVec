# Библиотека работы с кольцом полиномов над кольцом вычетов по модулю q

# Одновременно возможна работа только с поляризованными полиномами над кольцом вычетов только по одному модулю (переменная q - статическая переменная класса)!

## Реализованы некоторые базовые операции, такие как:

- Сложение полиномов

- Умножение полиномов

- Сравнение полиномов на равенство

- Отыскание остатка при делении (должно работать достаточно медленно (если делимое и делитель имеют наибольшую степень s и t соответственно, то сложность алгоритма - O(max(s * t, q))). Идет проверка на то, что q - простое число)

- Деление многочлена на многочлен нацело (примечание то же, что и к предыдущему)

- Вывод полинома в виде вектора (a_0, a_1, ..., a_n), где a_i - коэффициент при x^i. Выводятся (как и хранятся) и незначащие нули при высоких степенях.
