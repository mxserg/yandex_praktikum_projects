# Исследование надёжности заёмщиков

## Задача
На основе статистики о платёжеспособности клиентов исследовать влияет ли семейное положение и количество детей клиента на факт возврата кредита в срок

## Используемые библиотеки
`Pandas`, `PyMystem3`

## Основные выводы
Есть зависимость между наличием детей, семейного положения, уровнем дохода (пусть и незначительная), целью кредита и возвратом кредита в срок.

Риск по возврату кредита в срок у людей из следующих категорий:
- есть дети
- неженатые / незамужние или проживающие в гражданском браке
- кредит на автомобиль или образование

Идеальный портрет кредитора для банка - это бездетный вдовец с очень высоким уровнем дохода, приобретающий недвижимость.

**Рекомендации для платформы:**
- Устранить причины появления пропусков и выбросов. Рекомендуется добавить категории в выпадающих списках;
- Привести к соответствию типы данных параметров в столбцах;
- Автоматизировать заполнение зависимых параметров.

