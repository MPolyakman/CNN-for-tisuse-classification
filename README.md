# CNN-for-tisuse-classification
репозиторий для спецкурса про нейронные сети в обработке изображений

Реализованна сверточная нейросеть encoder -> full connection 

- [X] Валидация на части обучающей выборки
- [X] чекпоинты во время обучения
- [X] загрузка с чекпоинта если сломался колаб
- [X] на каждой эпохе показываются метрики
- [X] После обучения строятся графики функции потерь и метрик
- [X] Логирование каждого цикла обучения в новый текстовый файлик и сохранение весов модели
- [X] Аугментация набора данных
- [X] Загрузка весов по ссылке

## Все файлы pdf ipynb pth png txt с лучшего прогона лежат в папке alt_model

Ноутбук в коллабе
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github.com/MPolyakman/CNN-for-tisuse-classification/blob/main/solution_notebook.ipynb)

также по ссылкам можно скачать или запустить в ноутбуке в колабе 2 моих лучших веса


best_model.pth: https://drive.google.com/uc?id=1TbWEVsH8iy_Rb_HTuRsSgyjvXO6LzN9L

best_model_alt.pth: https://drive.google.com/uc?id=1Vi_uEOSUdOg6Rwl16ggzVADMWV3jSYyQ

**ниже показаны графики обучения alt модели**

![alt text](https://github.com/MPolyakman/CNN-for-tisuse-classification/blob/main/alt_model/training_curve_alt.png)
