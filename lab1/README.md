# ЛР №1. Кластеризация, снижение размерности пространства признаков

Для выбранного набора данных необходимо провести кластеризацию при помощи двух методов, взятых из следующих разных групп: метода k-средних (или альтернативного из группы, основанной на расстояниях между точками), метода DBSCAN (или альтернативного из группы, основанной на плотности точек) или одним из методов иерархической кластеризации. Для метода из первой и третьей групп необходимо выбрать количество кластеров с использованием одного из методов (метод локтя, индекс Дана, индекс Дэвиса-Болдуина, индекс Калинского-Гарабача, метод силуэта, RAND - обязателен при наличии целевой переменной, кофенетическая корреляция). Для методов из второй группы необходимо выбрать ε и другие параметры метода.  
Требуется сравнить визуализацию данных с использованием методов PCA, MDS (или альтернативного из той же группы, один метод на выбор) с t-SNE, UMAP (или альтернативного из той же группы, один метод на выбор) для случаев кластеризации до и после снижения размерности пространства с разметкой точек по полученным кластерам.

# Датасет
Orange Quality Analysis Dataset - https://www.kaggle.com/datasets/shruthiiiee/orange-quality

**Content:**

The tabular dataset contains numerical attributes describing the quality of oranges, including their size, weight, sweetness (Brix), acidity (pH), softness, harvest time, and ripeness, as well as categorical attributes such as color, variety, presence of blemishes, and overall quality.

**Columns:**
- Size: Size of orange in cm
- Weight: Weight of orange in g
- Brix: Sweetness level in Brix
- pH: Acidity level (pH)
- Softness: Softness rating (1-5)
- HarvestTime: Days since harvest
- Ripeness: Ripeness rating (1-5)
- Color: Fruit color
- Variety: Orange variety
- Blemishes: Presence of blemishes (Yes/No)
- Quality: Overall quality rating (1-5)