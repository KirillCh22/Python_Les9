# Погружение в Python (семинары)

## Задание 1. Как дела?
Вася совсем заскучал на работе и решил побаловаться с кодом проекта. Он
написал надоедливый декоратор, который при вызове декорируемой функции
спрашивает у пользователя «Как дела?», вне зависимости от ответа пишет что-то
вроде «А у меня не очень!» и только потом запускает саму функцию. Правда, после
такой выходки Васю чуть не уволили с работы.
Реализуйте такой же декоратор и проверьте его работу на нескольких функциях.



## Задание 2. Замедление кода
В программировании иногда возникает ситуация, когда работу функции нужно
замедлить. Типичный пример — функция, которая постоянно проверяет,
изменились ли данные на веб-странице или её код.
Реализуйте декоратор, который перед выполнением декорируемой функции
ждёт несколько секунд.



## Задание 3. Счётчик
Реализуйте декоратор counter, считающий и выводящий количество вызовов
декорируемой функции.
Для решения задачи нельзя использовать операторы global и nonlocal.



## Задание 4. Кэширование для ускорения вычислений
Создайте декоратор, который кэширует (сохраняет для дальнейшего использования)
результаты вызова функции и, при повторном вызове с теми же аргументами,
возвращает сохранённый результат.
Примените его к рекурсивной функции вычисления чисел Фибоначчи.
В итоге декоратор должен проверять аргументы, с которыми вызывается функция, и,
если такие аргументы уже использовались, должен вернуть сохранённый результат
вместо запуска расчёта.


