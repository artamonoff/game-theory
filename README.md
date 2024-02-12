# Теория игр
Примеры решения задач по Теории игр в Python

## Необходимые библиотеки Python

|Пакет             |Использованием                              |
|------------------|--------------------------------------------|
|`numpy`           |многомерные массивы; преобразование данных  |
|`scipy.optimize` |линейное программирование                   |
|`nashpy`          |равновесие Нэша                             |

Установка `nashpy`:
* `conda install conda-forge::nashpy`
* `pip install nashpy` 

## Игры с нулевой суммой

- [Пример 1](https://nbviewer.org/github/artamonoff/game-theory/blob/main/zero-sum-game/example.ipynb): Сведение к задаче линейного программирования
- [Пример 1](https://nbviewer.org/github/artamonoff/game-theory/blob/main/zero-sum-game/example-nashpy.ipynb): использование бибиотеки `nashpy`

## Игры с ненулевой суммой

- [Пример 2](https://nbviewer.org/github/artamonoff/Game-Theory/blob/main/non-zero%20sum%20game/Example2.ipynb): Ожидаемый выгрыш и равновесие в чистых стратегиях
- [Пример 2](https://nbviewer.org/github/artamonoff/Game-Theory/blob/main/non-zero%20sum%20game/Example2Nashpy.ipynb): использование бибиотеки `nashpy` для нахождения равновесий в чистых и смешанных стратегиях
- [Пример 3](https://nbviewer.org/github/artamonoff/Game-Theory/blob/main/non-zero%20sum%20game/Example3.ipynb): Симуляции
