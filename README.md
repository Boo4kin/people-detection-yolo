# People Detection with YOLOv8

Учебный проект по детекции людей на видео с использованием YOLOv8 и OpenCV.

Модель обрабатывает видеопоток, выделяет людей bounding box'ами, добавляет confidence score и сохраняет обработанный ролик.

## Что сделано

- загрузка предобученной YOLOv8m;
- детекция класса person на каждом кадре;
- визуализация bounding boxes и confidence;
- обработка видео через OpenCV;
- сохранение результата в MP4.

## Стек

Python · Ultralytics YOLOv8 · OpenCV · PyTorch · Jupyter Notebook

## Файлы

- `CV.rar` — архив с исходным ноутбуком;
- `crowd.mp4` — тестовое видео;
- `output_crowd_yolo.mp4` — пример результата;
- `requirements.txt` — зависимости.

## Установка

```bash
pip install -r requirements.txt
```

Проект выполнен в учебных целях для практики object detection и обработки видео.
