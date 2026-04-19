# Линейная регрессия 📏

---

<div style="background-color: lightgray;">
  <img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original.svg" width="40"/>
  <img src="https://github.com/devicons/devicon/blob/master/icons/pandas/pandas-original.svg" width="40"/>
  <img src="https://github.com/devicons/devicon/blob/master/icons/numpy/numpy-original.svg" width="40"/>
  <img src="https://github.com/devicons/devicon/blob/master/icons/scikitlearn/scikitlearn-original.svg" width="40"/>
  <img src="https://github.com/devicons/devicon/blob/master/icons/matplotlib/matplotlib-original.svg" width="40"/>
</div>

---

Теги:

![Static Badge](https://img.shields.io/badge/Python-blue?style=flat) ![Static Badge](https://img.shields.io/badge/Machine%20Learning-red?style=flat) ![Static Badge](https://img.shields.io/badge/Linear%20Regression-green?style=flat) ![Static Badge](https://img.shields.io/badge/Prediction-purple?style=flat) ![Static Badge](https://img.shields.io/badge/Data%20Science-pink?style=flat)

## Содержание 🗒️
- [Описание проекта](#описание-проекта-)
- [Технологии](#используемые-технологии-️)
- [Структура данных](#структура-данных-)
- [Ключевые шаги в работе](#ключевые-шаги-в-работе-)
- [Запуск](#запуск-программы-)
- [Лицензия](#лицензия-)


## **Описание проекта** 📜

В работе реализуется такой метод *Машинного обучения* (Machine Learning), как **Линейная Регрессия**. Принцип данного метода заключается в поиске такой прямой, которая будет <u>ближе</u> всего находиться к точкам. А его цель заключается в минимизации ошибки - расстояния между фактическим и теоретическим (прогнозным) значениями. 

В документе [linear.ipynb](https://github.com/m0zerrr/linear-regression/blob/main/linear.ipynb) представлено два раздела:
- Простая линейная регрессия

- Множественная линейная регрессия

`❔ Их отличие заключается в количестве независимых переменных`

## **Используемые технологии** ⚙️
* `Python 3.10+`
* `Pandas`
* `SciPy`
* `Matplotlib`
* `Seaborn`
* `Scikit-Learn`
* `LinearRegression`

## **Структура данных** 💾

🗄️ ~ Для **первого** раздела данные находятся в файле `data/weight-height.csv` ([Перейти](https://github.com/m0zerrr/linear-regression/blob/main/data/weight-height.csv)) ~
  
*Описание:*<br>Набор данных содержит ***10&nbsp;000*** строк и представлен 3-мя столбцами:
+ `Gender` (Пол)
+ `Height` (Рост)
+ `Рост` (Вес)

---

🗄️ ~ Для **второго** раздела данные находятся в файле `data/nedvig.xlsx` ([Перейти](https://github.com/m0zerrr/linear-regression/blob/main/data/nedvig.xlsx)) ~
  
*Описание:*<br>Набор данных содержит ***1&nbsp;572*** строк и представлен 7-мью столбцами:
+ `Район`
+ `Число комнат`
+ `Тип дома`
+ `Общая`
+ `Жилая`
+ `Кухня`
+ `Цена, тыс. руб.`

## **Ключевые шаги в работе** 🐾
1. Загрузка данных
2. Исследование данных:

    1. Подробная информация о наборе `df.info()`
    2. Размер датасета `df.shape`
    3. Проверка на пропущенные значения `df.isna().sum()`
3. Построение визуализации исходных данных
4. Перевод категориальных данных в бинарные переменные
5. Разделение данных на обучающий и тестовый наборы `train_test_split` из библиотеки `sklearn`
6. Создание модели Линейной регрессии
7. Обучение модели на соответствующей выборке `model.fit()`
8. Прогнозирование значений по тестовому набору `model.predict(X_test)`
9. Оценка качества модели

## **Запуск программы** 🚀

1) 🖼️ _Создать виртуальное окружение;_

    ```cmd
      python -m venv .venv

      .venv\Scripts\activate.bat
    ```
2) 🪄 _Загрузить необходимые библиотеки:_
    ```cmd
      py -m pip install -r requirements.txt
    ```
3) ▶️ _Выполнить запуск:_
    - Запустить в программе Microsoft Visual Studio Code (или в другом редакторе)
    
    _Или_

    - Открыть консоль
    - Перейти в директорию с проектом
    ```cmd
      cd ./name_of_directory
    ```
    - Запустить Jupyter Notebook
    ```cmd
      jupyter notebook
    ```


## **Лицензия** 📋

В данном проекте используется лицензия [MIT](https://github.com/m0zerrr/exchange-rate/blob/main/LICENSE)