# Знакомство с языком Python (семинары)
## ОГЛАВЛЕНИЕ
## Урок 1. Ввод-Вывод, операторы ветвления
## Урок 3. Списки и словари
## Урок 5. Рекурсия и алгоритмы

Решение данных домашних заданий выполнено сервисом автоматической проверки написанного кода.

### [ https://github.com/AlexeyYuzh19/PY_seminar_1_3_5.git ]( "Переход в репозиторий GitHub - https://github.com/AlexeyYuzh19/PY_seminar_1_3_5.git")

## Урок 2. Циклы (for, while)
### Практическое задание 2. «Циклы(for, while)»

### [ https://github.com/AlexeyYuzh19/PY_seminar_2.git ]( "Переход в репозиторий GitHub - https://github.com/AlexeyYuzh19/PY_seminar_2.git")

## Урок 4. Словари, множества и профилирование
### Практическое задание 4. «Словари, множества и профилирование»

### [ https://github.com/AlexeyYuzh19/PY_seminar_4.git ]( "Переход в репозиторий GitHub - https://github.com/AlexeyYuzh19/PY_seminar_4.git")

## Урок 6. Повторение списков
### Практическое задание 6. «Повторение списков»

### [ https://github.com/AlexeyYuzh19/PY_seminar_6.git ]( "Переход в репозиторий GitHub - https://github.com/AlexeyYuzh19/PY_seminar_6.git")

## Урок 7. Функции высшего порядка
### Практическое задание 7. «Функции высшего порядка»

### [ https://github.com/AlexeyYuzh19/PY_seminar_7.git ]( "Переход в репозиторий GitHub - https://github.com/AlexeyYuzh19/PY_seminar_7.git")

## Урок 8. Работа с файлами
### Практическое задание 8. «Работа с файлами»

### [ https://github.com/AlexeyYuzh19/PY_seminar_8.git ]( "Переход в репозиторий GitHub - https://github.com/AlexeyYuzh19/PY_seminar_8.git")

## Урок 9. Урок 9. Работа с табличными данными
### Практическое задание 9. «Работа с табличными данными»

**9.1[40]**: Работа в Google Colab.<br>
Файл california_housing_train.csv, который находится в папке sample_data<br>
Для домов, где кол-во людей от 0 до 500 (population) вывести информацию о цене дома(median_house_value):<br>
максимальное значение<br>
минимальное значение<br>
среднее<br>
медиану<br>
**9.2[42]**: Работа в Google Colab.<br>
Файл california_housing_train.csv, который находится в папке sample_data<br>
Узнать какая максимальная households в зоне минимального значения population<br>

### [ https://colab.research.google.com/drive/1tQX-XH6hOA6SU1iIWDAm1HHvhs1MHRgV?usp=sharing ]( "Переход в блокнот Google Colab - https://colab.research.google.com/drive/1tQX-XH6hOA6SU1iIWDAm1HHvhs1MHRgV?usp=sharing")

## Урок 10. Построение графиков
### Промежуточная аттестация

**Задача 44**: В ячейке ниже представлен код генерирующий DataFrame, которая состоит всего из 1 столбца.<br>Ваша задача перевести его в one hot вид.<br>Сможете ли вы это сделать без get_dummies?<br>

import random<br>
lst = ['robot'] * 10<br>
lst += ['human'] * 10<br>
random.shuffle(lst)<br>
data = pd.DataFrame({'whoAmI':lst})<br>
data.head()

### [ https://colab.research.google.com/drive/1X9KrivG6gZrCIY5l0zt5O8xwLcs1TQ4K?usp=sharing ]( "Переход в блокнот Google Colab - https://colab.research.google.com/drive/1X9KrivG6gZrCIY5l0zt5O8xwLcs1TQ4K?usp=sharing")