# Игра в жанре tower defense
Необходимо обороняться от монстров, сторя башни

## Зависимости
- python 3.6
- kivy 1.10.0-1 [Актуальная инструкция по установке](https://kivy.org/#download)


## Запуск
`python3 ./main.py`

## Башни
### Маг
- **Стоимость:** 50
- Большой урон
- Медленная скорость атаки
- Замедляет монстров при попадании
- **Уровень 2: (стоимость 60)** увеличивает урон и скорость атаки

### Лучник
- **Стоимость:** 40
- Маленький урон
- Большая скорость атаки
- Поражает несколько монсров за раз
- **Уровень 2: (стоимость 50)** добавляет дополнительный снаряд при выстреле

## Монстры
### Орк
- **Скорость:** средняя
- **Урон:** 20
- **Награда за убиство:** 10
- _Маленькие злые гуманоиды без выдающихся способностей_

### Шаман
- **Скорость:** средняя
- **Урон:** 20
- **Награда за убиство:** 30
- Накладывают эффект постепенного лечения на раненых монстров
- _Племенные лекари, проводящие запрещённые обряды_

### Бандит
- **Скорость:** большая
- **Урон:** 10
- **Награда за убиство:** 5
- _Стремителен и ловок, способен молнейносно перерезать твою глотку_
