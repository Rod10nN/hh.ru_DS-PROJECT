# Проект: Анализ резюме из HeadHunter

Компания HeadHunter хочет построить модель, которая бы автоматически определяла примерный уровень заработной платы, подходящей пользователю, исходя из информации, которую он указал о себе. Прежде чем построить модель, данные необходимо преобразовать, исследовать и очистить. В этом и состоит задача.

## Содержание

Проект состоит из 4 частей:

* [Базовый анализ структуры данных](https://github.com/Rod10nN/hh.ru_DS-PROJECT/blob/master/HeadHunter-Project.ipynb)

На данном этапе мы познакомились с нашии исходными данными, которые вы можете скачать [*здесь*](https://drive.google.com/file/d/1Kb78mAWYKcYlellTGhIjPI-bCcKbGuTn/view?usp=sharing).



* [Предобработка данных](https://github.com/Rod10nN/hh.ru_DS-PROJECT/blob/master/HeadHunter-Project.ipynb)

Данные очень «сырые»: признаки представлены в неудобном для анализа и очистки формате. На данном этапе идет подготовка данных. При работе с признаком «ЗП» нам понадобился еще один Dataframe - выгрузка курсов валют, которые встречаются в наших данных за период с 29.12.2017 по 05.12.2019: скачать вы можете [*здесь*](https://lms.skillfactory.ru/assets/courseware/v1/15abf80f45a2f3e93c3274101b451c67/asset-v1:SkillFactory+DST-3.0+28FEB2021+type@asset+block/ExchangeRates.zip).



* [Разведывательный анализ](https://github.com/Rod10nN/hh.ru_DS-PROJECT/blob/master/HeadHunter-Project.ipynb)

Предназначен для выявления связей между признаками, выявления закономерностей, определения распределений признаков, поиска аномалий и других дефектов данных. Для наглядности были построены интерактивные графики при помощи библиотеки plotly.express([графики в формате.png](https://github.com/Rod10nN/hh.ru_DS-PROJECT/tree/master/graph%20in%20png), [графики в формате HTML](https://github.com/Rod10nN/hh.ru_DS-PROJECT/tree/master/html_graps),  [ссылки на интерактивные графики](https://github.com/Rod10nN/hh.ru_DS-PROJECT/blob/master/%D0%A1%D1%81%D1%8B%D0%BB%D0%BA%D0%B8%20%D0%BD%D0%B0%20html%20%D0%B3%D1%80%D0%B0%D1%84%D0%B8%D0%BA%D0%B8.txt) ).

* [Очистка данных](https://github.com/Rod10nN/hh.ru_DS-PROJECT/blob/master/HeadHunter-Project.ipynb)

Когда мы проводили визуальный анализ, мы нашли несколько несостыковок в данных: пропуски, гигантские размеры желаемых заработных плат, резюме людей слишком «преклонного» возраста, опыт работы, превышающий возраст. Поэтому данные подлежат очистке.