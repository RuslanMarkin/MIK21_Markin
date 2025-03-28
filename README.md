# MIK21_Markin

1. Введение
Цель данного кода — преобразование изображений в мультяшный стиль. Это достигается путем применения билинейной фильтрации и адаптивного порогового преобразования к оригинальному изображению. Методика основана на уменьшении шума и выделении ключевых контуров изображения.
2. Описание алгоритма
Входные данные
Исходное изображение (пример: Screenshot.png)![Uploading Screenshot 2025-03-26 at 14.47.18.png…]()


Рисунок 1 - Исходное изображение
Этапы обработки
Чтение изображения: загружается исходное изображение и изменяется его размер.
Сглаживание и билинейная фильтрация: уменьшение разрешения (downsampling) и многократная билинейная фильтрация.
Преобразование в оттенки серого и медианный блюр: помогает минимизировать шум и улучшить выделение краев.
Выделение контуров: применяется адаптивное пороговое преобразование, чтобы выявить ключевые границы.
Комбинирование с цветным изображением: объединение цветного изображения с выделенными краями для создания мультяшного эффекта.
3. Результаты
Исходное изображение содержит обычные цветовые градиенты и текстуры, тогда как обработанный результат имеет стилизованные, сглаженные цвета и четкие контуры, характерные для мультяшного эффекта.
![Uploading Screenshot 2025-03-26 at 14.47.28.png…]()

Рисунок 2 - Получившееся изображение
4. Вывод
Разработанный алгоритм успешно преобразует фотографии в мультяшный стиль, улучшая визуальную выразительность изображения. Возможные улучшения включают настройку параметров билинейной фильтрации и адаптивного порога для более точного управления эффектом.
 
