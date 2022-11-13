# Генератор анекдотов с использование модели GPT2

В данном репозитории хранятся данные для обучения GPT2 для задачи генерации анекдотов.

> dataset.txt -  содержит все обучающие примеры из нескольких датасетов, которые прошли обработку (из jokes.csv и extract_dialogues_from_anekdots.txt)

> extract_dialogues_from_anekdots.txt -  содержит примеры шуточных диалогов, часть которых помещены в dataset.txt (взят отсюда [шуточные диалоги](https://github.com/Koziev/NLP_Datasets/blob/master/Conversations/Data/extract_dialogues_from_anekdots.tar.xz))

> ru.txt - словарь русских слов, который предоставляет LibreOffice ([LibreOffice](https://download.documentfoundation.org/libreoffice/src/7.4.2/libreoffice-dictionaries-7.4.2.3.tar.xz?idx=2)),  он был дополнен словами из датасетов

> jokes.rar - основной датасет с анекдотами [Kaggle](https://www.kaggle.com/datasets/konstantinalbul/russian-jokes)

> begin-samples.txt - начальные слова из всех примеров датасета, используется для рандомной генерации
