# Movie Recommender System

Рекомендательная система фильмов на датасете MovieLens 100K.
Сравнение подходов: collaborative filtering, matrix factorization, neural CF.

## Датасет
MovieLens 100K — скачать: https://files.grouplens.org/datasets/movielens/ml-100k.zip
Распаковать в папку `data/`.

## Ключевые наблюдения из EDA
- Разреженность матрицы ~93.7% (заполнено лишь ~6.3%)
- Оценки скошены вверх (rating bias): средняя ~3.5
- Long tail: активность юзеров и популярность фильмов — степенной закон
- Отсюда вызовы: sparsity и cold start

## Установка
pip install -r requirements.txt