#  Определение наиболее выгодного региона нефтедобычи
## Цель
Построить модель машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль, для определения места бурения новой скважины

## Описание
Вам предоставлены пробы нефти в трёх регионах. Характеристики для каждой скважины в регионе уже известны. Постройте модель для определения региона, где добыча принесёт наибольшую прибыль.
  
## Данные
/datasets/geo_data_0.csv  
/datasets/geo_data_1.csv  
/datasets/geo_data_2.csv  
  
- id — уникальный идентификатор скважины
- f0, f1, f2 — три признака точек (неважно, что они означают, но сами признаки значимы)
- product — объём запасов в скважине (тыс. баррелей)
  
## Используемые библиотеки
Pandas NumPy Matplotlib Seaborn Keras
  
## Вывод 
- В третьем регионе средний запас сырья и RMSE выше, чем в остальных
- С точки зрения ошибки прогноза привлекательнее второй регион
- Средний прогнозируемый объём скважен в регионах меньше, чем достаточный объём для безубыточности
- Самая высокая средняя выручка во втором регионе
- Самый низкий риск убытка у второго региона - 0.3%
- Самый высокий риск, самый большой интервал, самая низкая средняя выручка в третьем регионе
- Регион для разработки месторождения - второй регион
