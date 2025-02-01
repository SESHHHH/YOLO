# YOLO
Тестовое задание: использование YOLOv8 для задачи детекции.

Датасет, на котором дообучалась модель: https://github.com/markblumenau/hw3_iad_dl/raw/main/cards/data.zip .
Разметка находится в xmls папке, картинки в images, в class_dict - словарь классов. Всего 6 различных классов в датасете.

Видео с демонстрацией инференса на потоке веб-камеры: https://disk.yandex.ru/i/JBXtRDnF1kLT2Q .

Для дообучения модели необходимо запустить все ячейки .ipynb ноутбука. 
Для инференса необходимо воспользоваться разделом "Инференс на потоке с веб-камеры" в файле .ipynb.

Все графики метрик и ошибок на обучении и тесте лежат в model/train/results.png .
