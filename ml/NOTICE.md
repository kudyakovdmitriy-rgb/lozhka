# Модель распознавания блюд

`aiy_food_v1.tflite` — модель Google AIY «vision/classifier/food_V1/1» (LiteRT/TensorFlow Lite), 2023 класса блюд.
Распространяется по лицензии Apache 2.0 (см. `LICENSE-APACHE-2.0.txt`).

- Карточка модели: https://www.kaggle.com/models/google/aiy/tfLite/vision-classifier-food-v1/1
- Список меток: https://www.gstatic.com/aihub/tfhub/labelmaps/aiy_food_V1_labelmap.csv
- SHA-256: `03dd6d9129501f97be00775d9e17b5d9ad13be730149352adb8f4ca953b7a650`

Модель не изменялась. По карточке модели она лучше знает североамериканскую кухню и не определяет вес,
состав, аллергены и калорийность — Ложка использует её только как подсказку «на что похоже блюдо»;
граммы и выбор блюда подтверждает человек.
