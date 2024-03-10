Клеточный автомат.
Эта программа симулирует каждый шаг той или иной конфигурации клеточного автомата.
программа запускается через модуль main
Требования: Python interpreter(3.10), модуль pygame (2.4.0)
Поведение можно менять, меняя значения в модуле defenition:
DELAY - задержка между шагами симуляции
NUMBER_OF_CELLS - количество столбцов и строк (квадрат)
CHANCE - шанс (%) генерации живой клетки при генерации таблицы
Birth/Survive - необходимое кол-во соседей, что мертвая клетка родилась/живая клетка продолжила жить
TYPE_NEIGHBORS - тип проверки соседей. '8' - все клетки, имеющие общую точку с данной, '4' все клетки, имеющие общую сторону с данной
