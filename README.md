# Адаптивная бинаризация фотографий документов
## (Adaptive Document Image Binarization)


## Адаптивность (в порядке приоритета)
    1. Отсутствие требования контрастной поверхности.
    2. Неравномерная освещённость.
        2.1. Одна часть фото освещена лучше, другая - хуже.
        2.2. Наличие тени.
    3. Слабая освещённость.
    

## Цель
    1. Алгоритм, переводящий любое (с точностью до определённых условий) изображение документа в изображение того же разрешения, но состоящего только из двух цветов: чёрного и белого.
    2. После такой бинаризации не должна пропасть информация с самого документа.
    3. Чёрным должно остаться только содержимое документа. Ни шумов, ни элементов фона, на котором было сделано фото, быть не должно.
