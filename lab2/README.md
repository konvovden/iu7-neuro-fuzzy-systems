# ЛР №2. Классификация, оценка точности классификации

Для выбранного набора данных необходимо провести сравнение результатов работы классификаторов из двух групп на выбор: 
- регрессия (линейная, нелинейная, логистическая, метод опорных векторов), k-ближайших соседей;
- деревья принятия решений (деревья, случайный лес);
- бустинг (один из методов на выбор).

Для каждого метода необходимо построить матрицу ошибок и рассчитать одну из следующих метрик: f-мера, ROC AUC, accuracy.
При обучении классификатора необходимо использовать кроссвалидацию. Необходимо визуализировать изменение точности работы метода на разных шагах кроссвалидации. Необходимо показать как меняется точность классификации при изменении гиперпараметров.

# Датасет
Banana Quality - https://www.kaggle.com/datasets/l3llff/banana

**Content**  
Tabular dataset contains numerical information about bananas of different quality (size, weight, sweetness, softness, harvest time, ripeness, acidity, quality).  

**Columns**
- Size - size of fruit
- Weight - weight of fruit
- Sweetness - sweetness of fruit
- Softness - softness of fruit
- HarvestTime - amount of time passed from harvesting of the fruit
- Ripeness - ripness of fruit
- Acidity - acidity of fruit
- Quality - quality of fruit
