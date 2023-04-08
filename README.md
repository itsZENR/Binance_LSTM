# Binance_LSTM

# Тестовое задание:
Цель: разработать скрипт для сбора и обработки данных с использованием API Binance и прогнозирования временных рядов с помощью LSTM-модели.

Этапы выполнения задания:

1. Изучить документацию RESTful API Binance (https://binance-docs.github.io/apidocs/spot/en/) и написать скрипт на Python с использованием библиотеки Requests, чтобы получить данные о котировках криптовалют. Сохранить полученные данные в формате CSV.

2. Загрузить полученный CSV-файл с данными в Python с использованием библиотеки Pandas и выполнить предварительную обработку данных (например, удаление пропусков, преобразование даты и времени, масштабирование).

3. С использованием библиотеки NumPy, разделить данные на обучающую и тестовую выборки.

4. Создать и обучить LSTM-модель с использованием библиотеки Keras или TensorFlow на основе подготовленных данных. Подобрать архитектуру и гиперпараметры модели, чтобы достичь наилучшего качества прогнозирования.

5. Оценить качество модели на тестовой выборке, используя подходящие метрики, такие как среднеквадратичная ошибка (MSE) или средняя абсолютная ошибка (MAE).

6. Визуализировать предсказания модели для тестовой выборки на графике с помощью библиотеки Matplotlib или Plotly. Вывести график с предсказанием на час вперед от последних полученных данных.

# Требования к выполнению задания:
Использовать Python 3.x и стандартные библиотеки, такие как Requests, для работы с API Binance

В качестве хранилища данных использовать файлы в формате CSV

Для обработки и подготовки данных использовать библиотеки Pandas и NumPy

Для создания и обучения LSTM-модели использовать библиотеку Keras или TensorFlow

В качестве инструмента для визуализации результатов использовать библиотеку Matplotlib или Plotly

Качество/точность предсказания не является основным критерием оценки выполнения задания, но стажер должен стремиться к наилучшему результату

Стараться уложиться в 200 строк кода.

# Полученные результаты:
Среднеквадратичная ошибка на обучающей выборке: 3599.52

Среднеквадратичная ошибка на тестовой выборке: 1099.03

![image](https://user-images.githubusercontent.com/24351126/230729160-db576ac5-0d08-4d74-a7e1-5d2544125723.png)

