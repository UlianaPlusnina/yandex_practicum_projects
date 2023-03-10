# Прогнозирование оттока клиентов телеком компании
## Цель
Проанализировать поведение клиентов оператора сотовой связи для определения наиболее выгодного для оператора тарифа

## Описание
Оператор связи «Ниединогоразрыва.ком» хочет научиться прогнозировать отток клиентов. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия. Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и договорах.
  
## Данные
Данные состоят из файлов, полученных из разных источников:
- `contract.csv` — информация о договоре;
- `personal.csv` — персональные данные клиента;
- `internet.csv` — информация об интернет-услугах;
- `phone.csv` — информация об услугах телефонии.  
  
Во всех файлах столбец `customerID` содержит код клиента.  
Информация о договорах актуальна на 1 февраля 2020.


  
## Используемые библиотеки
pandas, scipy, matplotlib, sklearn, LightGBM, CatBoost
  
## Вывод 
Лучший результат показал catboost, roc_auc составил AUC-ROC = 0.86.

