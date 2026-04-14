# Статистика и кластеризация

## О проекте

Этот репозиторий объединяет несколько мини-проектов, в которых акцент сделан на статистическое мышление, анализ распределений и методы обучения без учителя.

Внутри три ноутбука:

1. **`housing_price_distribution.ipynb`** — анализ распределения цен на жилье.
2. **`robust_statistics_and_group_analysis.ipynb`** — устойчивые статистики и сравнение распределений.
3. **`hierarchical_clustering_beverages.ipynb`** — иерархическая кластеризация данных о предпочтениях напитков.

## Используемые файлы

- Ноутбуки:
  - `housing_price_distribution.ipynb`
  - `robust_statistics_and_group_analysis.ipynb`
  - `hierarchical_clustering_beverages.ipynb`
- Данные:
  - `data/ames_housing.txt`
  - `data/russian_towns_1959.csv`
  - `data/swiss_bank_notes.csv`
  - `data/beverage_ratings.csv`

## Структура папки

```text
statistics-and-clustering/
├── README.md
├── README_images.md
├── housing_price_distribution.ipynb
├── robust_statistics_and_group_analysis.ipynb
├── hierarchical_clustering_beverages.ipynb
├── data/
│   ├── ames_housing.txt
│   ├── russian_towns_1959.csv
│   ├── swiss_bank_notes.csv
│   └── beverage_ratings.csv
└── images/
    ├── ames_saleprice_distribution.png
    ├── ames_log_saleprice_distribution.png
    ├── town_population_distribution.png
    └── beverage_scatter.png
```

## Что сделано

- проанализированы распределения и их асимметрия;
- рассмотрены устойчивые статистики;
- выполнена визуализация многомерных данных;
- показан пример иерархической кластеризации.

## Какие навыки показывает проект

- статистическое мышление;
- анализ распределений;
- EDA;
- кластеризация;
- интерпретация многомерных данных.

## Визуализации

![Распределение цен домов](images/ames_saleprice_distribution.png)

![Логарифм цен домов](images/ames_log_saleprice_distribution.png)

![Распределение населения городов](images/town_population_distribution.png)

![Scatter plot по данным о напитках](images/beverage_scatter.png)
