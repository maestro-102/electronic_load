# electronic_load | электронная нагрузка

Была собрана для проверки USB зарядников телефонов. Отлично пригодилась и для проверки настольного блока питания. Возможности довольно широкие для такой схемы, но... без фанатизма... - кратковременно.

Содержание
---


Фотографии
---
<a href="https://github.com/maestro-102/electronic_load/blob/master/image/1.jpg" target="_blank">
    <img src="https://github.com/maestro-102/electronic_load/blob/master/image/1.jpg?raw=true" width=30% alt="preview">
</a>

<a href="https://github.com/maestro-102/electronic_load/blob/master/image/2.jpg" target="_blank">
    <img src="https://github.com/maestro-102/electronic_load/blob/master/image/2.jpg?raw=true" width=30% alt="preview">
</a>

Характеристики
----
- диапазон проверяемых напряжений 5 - 35В
- удерживаемый ток нагрузки 0 - 3А

Описание
---
База устройства - операционный усилитель LM358. Источник опорного напряжения построен на TL431. Силовой ключ - IRFZ44N на хорошем радиаторе с активным обдувом.

Программы для просмотра файлов
-----
1. Sprint Layout 6.0 - для проектирования печатных плат \
Расширение: \*.lay6 \
Ссылка: https://radioaktiv.ru/loads/softf/pcb/27881-sprint-layout-60-rus.html

2. Splan 7.0 - для черчения электрических схем \
Расширение: \*.spl7 \
Ссылка: http://splansoft.ru/

Структура проекта
-----------------

Описание файловой структуры проекта:

    electronic_load
    ├── image          - папка с фотографиями устройства
    ├── pcb            - печатная плата
    ├── shemas         - схема устройства
    └── README.md          
