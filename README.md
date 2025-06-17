# Прогнозирование цен закрытия акций Amazon с использованием экзогенных признаков (2019-2024 гг.)

## 🛠 Технологический стек
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-blue?logo=seaborn&logoColor=white&style=for-the-badge)
![Statsmodels](https://img.shields.io/badge/Statsmodels-8A2BE2?logo=statsmodels&logoColor=white&style=for-the-badge)
![CatBoost](https://img.shields.io/badge/CatBoost-FF6F61?logo=catboost&logoColor=white&style=for-the-badge)

## 📌 О проекте
Этот репозиторий создан как дополнение к курсовой работе по прогнозированию временных рядов. Для удобства работы код разбит на тематические Jupyter Notebook.

## 📂 Файловая структура

### Ноутбуки с анализом:
- `графики_для_теории_курсовая.ipynb` - визуализация декомпозиции временного ряда
- `EDA_analysis.ipynb` - разведочный анализ данных (корреляция, пропуски, компоненты временного ряда)
- `statistic_models.ipynb` - статистические модели (ARIMA, SARIMA, SARIMAX)
- `adaptive_models.ipynb` - адаптивные модели:
  - Экспоненциальное сглаживание
  - Линейная модель Хольта
  - Модель Хольта-Винтерса
  - Модель локального глобального тренда (LGT)
- `ml_models.ipynb` - модели машинного обучения:
  - Random Forest
  - XGBoost
  - CatBoost
  - LightGBM
  - Ансамбль моделей

### Исходные данные:
- `HistoricalData_1742404356306.xlsx` - исторические данные по ценам закрытия акций Amazon
- `For_sarimax_1.xlsx` - экзогенные признаки для SARIMAX:
  - Данные о сотрудниках
  - Расходы на лоббирование в США (основной рынок Amazon)
