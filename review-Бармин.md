# Ревью

## Впечатления:
Неплохой интерфейс, прям понравилось что при переносе строке экран как бы зациклен и начинает рисоваться сверху, аналогично снизу
Хороший функционал, жаль ограничен числами 2**16 по модулю 


## По КОДУ:
- Не понял зачем нужен стек размера 0:  https://github.com/graphento/jackdaniels/blob/bff92f971583526512ca5383b00be6c8a654e6ab/src/Stack.jack#L8 (fixed)
- Не хватает комента здесь или над классом что такое символ 32 https://github.com/graphento/jackdaniels/blob/bff92f971583526512ca5383b00be6c8a654e6ab/src/Printer.jack#L25 (fixed)
- Тоже непонятно почему именно такие числа здесь и ниже https://github.com/graphento/jackdaniels/blob/bff92f971583526512ca5383b00be6c8a654e6ab/src/Eval.jack#L47 (fixed)
- что такое 864 и 96 ниже https://github.com/graphento/jackdaniels/blob/bff92f971583526512ca5383b00be6c8a654e6ab/src/Calculator.jack#L108
- Возможно стоит основное слово перетащить на начало названия переменной (в этой строке и ниже), а то много тех которые одинаково начинаются, легче запутаться при текущей реализации (учтено)
https://github.com/graphento/jackdaniels/blob/bff92f971583526512ca5383b00be6c8a654e6ab/src/Eval.jack#L2
- WHY? Думаю стоит разбить на пару списков https://github.com/graphento/jackdaniels/blob/bff92f971583526512ca5383b00be6c8a654e6ab/src/Calculator.jack#L2 (not needed)
- Без комментариев https://github.com/graphento/jackdaniels/blob/bff92f971583526512ca5383b00be6c8a654e6ab/src/Calculator.jack#L59 (fixed)
+ Константы большими буквами
+ Не нашел утечек памяти
+ Единый стиль форматирования

## Предложения:
Придумать как увеличить диапозон чисел

## Оценка
- **Качество кода**: 4.8 / 5
- **Функциональность**: 5 / 5
- **Рисовка**: 5 / 5
- **В общем**: 4.99 / 5
