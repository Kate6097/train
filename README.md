Задача в первую очередь стоит такая - с помощью текстового промпта (1 промпт определяет статус изначальных загруженных/сгенерированных фотографий, 2 промпт указывает направление изменения этих фотографий) осуществить переход изображения в новый домен, на котором модель изначально не обучалась.

Структура: 2 ветви main и important functions
В ветви main:
1) README.md
2) Валидация.ipynb с валидационным ноутбуком
3) Ноутбук с обучением.ipynb
4) Список библиотек.ipynb - отмечу, что должно быть gpu, без него на этапе загрузки возникают трудности

В ветви important functions:
1) analyze_and_set_layers.ipynb
2) Direction_loss.ipynb

Фотографии результатов:
https://drive.google.com/drive/folders/1ewITqGylWNXWShqgKu0SHdZaC2-QeABt?usp=sharing

Веса модели лежат в этой папке:
https://drive.google.com/drive/folders/1I-GjG8qNiNQg43yI8DiwMTgXrigD-KEg?usp=sharing

Отчет: https://github.com/Kate6097/train/issues/3
