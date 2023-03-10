# <center> Анализ резюме из HeadHunter </center>
## Оглавление
1. [Описание проекта](#Описание-проекта)
2. [Описание данных](#Описание-данных)
3. [Зависимости](#Зависимости)
4. [Установка проекта](#Установка-проекта)
5. [Использование проекта](#Использование-проекта)
6. [Авторы](#Авторы)
7. [Выводы](#Выводы)

## Описание проекта
Проблематика: часть соискателей не указывает желаемую заработную плату, когда составляет своё резюме.
Это является помехой для рекомендательной системы HeadHunter, которая подбирает соискателям список наиболее подходящих вакансий, а работодателям — список наиболее подходящих специалистов.

> ⭐ Компания HeadHunter хочет построить модель, которая бы автоматически определяла примерный уровень заработной платы, подходящей пользователю, исходя из информации, которую он указал о себе. Но, как вы знаете, прежде чем построить модель, данные необходимо преобразовать, исследовать и очистить. В этом и состоит наша задача!

Файл с исходными данными можно скачать [здесь](https://drive.google.com/file/d/1Kb78mAWYKcYlellTGhIjPI-bCcKbGuTn/view).

### Основные этапы работы с данными:
1. Базовый анализ структуры данных
2. Преобразование данных
3. Разведывательный анализ
4. Очистка данных

**Цель предобработки данных** — избавиться от «мусора», который может помешать моделированию или исказить его результаты. Заполнить пропущенные значения. Удалить малоинформативные признаки и значения.

**Данный проект** направлен на тренировку навыков применения различных методов предобработки данных на каждом из этапов Feature Engineering на примере датасета резюме с сайта по поиску работников и работадателей HeadHunter.

**О структуре проекта:**
* [data](./data) - папка с исходными табличными данными
* [plotly](./plotly) - папка с изображениями, необходимыми для проекта
* [Project-1_Feature_Engineering_HeadHunter.ipynb](./Project-1_Feature_Engineering_HeadHunter.ipynb) - jupyter-ноутбук, содержащий основной код проекта, в котором происходят этапы Feature Engineering.

## Описание данных
В нашем распоряжении база резюме, выгруженная с сайта поиска вакансий [hh.ru](https://nn.hh.ru/?ysclid=lcqtddl6ky405210179).
Компания HeadHunter ведет датасет в формате csv о заявлениях соискателей в которых указана личная информация самих соискателей. 
Исходный датасет представляет собой набор данных из таблицы в которой содержатся 12 признаков о необходимой информации для работодателя. Некоторые столбцы таблицы имеют слишком большой объем информации.

## Используемые зависимости
* Python (3.9):
    * [numpy (1.20.3)](https://numpy.org)
    * [pandas (1.3.4)](https://pandas.pydata.org)
    * [matplotlib (3.4.3)](https://matplotlib.org)
    * [seaborn (0.11.2)](https://seaborn.pydata.org)
    * [plotly (2.13.3)](https://plotly.com/)

## Установка проекта

```
git clone https://github.com/DmitryChrome/Progect_FeatureEngineering_HeadHanter.git
```

## Использование
Вся информация о работе представлена в jupyter-ноутбуке Project-1_Feature_Engineering_HeadHunter.ipynb.

## Авторы

* [Dmitry Chuprinko](https://t.me/Dmitry_Chuprinko)

## Выводы

В результате проделанной работы мне удалось выполнить поставленные цели и задачи, а именно преобразовывать данные, создавая новые полезные признаки на основе представленной информации. Заполнять и удалять пропуски. Избавляться от неинформативных признаков и значений. Выявлять зависимости, демонстрируя это на графиках.