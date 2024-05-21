# ЛР №3. Обработка текстов

Необходимо провести векторизацию текстов с использованием двух методов:
- частота или tf*idf;
- статические или контекстуализированные векторные модели.  
  
Полученные векторы текстов необходимо либо кластеризовать. На полученных кластерах необходимо обучить метод классификации и проверить точность его работы. Необходимо сравнить точность работы метода с и без применения морфологического анализа.

# Датасет
BBC News - https://www.kaggle.com/datasets/gpreda/bbc-news

**Context**  
Self updating dataset. It collects RSS Feeds from BBC News using a Kernel: https://www.kaggle.com/gpreda/bbc-news-rss-feeds. The Kernel is run with a fixed frequency and the dataset is updated using the output of the Notebook.

**Content**  
BBC News RSS Feeds. The data contains the following columns:
- title
- pubDate
- guid
- link
- description