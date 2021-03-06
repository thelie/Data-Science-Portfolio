# Data-Science-Portfolio:

Репозиторий для проектов, созданных в ходе изучения машинного обучения и data science.   

## [1. Кредитный скоринг:](/Credit-Scoring)

**Задача:**
Определить влияние семейного положения, количества детей и других данных на погашение кредита в срок.

**Навыки и библиотеки:**
Pandas, PyMystem3, предобработка данных, лемматизация.

**Вывод:**
Подтверждена зависимость количества детей, семейного положения и уровня дохода и целей кредита на кредитоспособность. 


## [2. Исследование рынка недвижимости в Санкт-Петербурге](/St-Petersburg-real-estate-research)

**Задача:**
По данным объявлений о продаже квартир в Санкт-Петербурге и области определить параметры влияющие на стоимость недвижимости.

**Навыки и библиотеки:**
Pandas, NumPy, Matplotlib, выявление корреляций, построение графиков.

**Вывод:**
Выявлено сколько обычно занимает продажа.  
Найдены населенные пункты с наиболее высокой и низкой стоимостью жилья в регионе,
Исследована зависимость цены от удаленности от центра.
Определены факторы влияющие на стоимость квартиры.


## [3. Анализ тарифов телеком компании](/Telecom-tariff-analysis)

**Задача:**
По небольшой выборке данных пользователей определить наиболее выгодный тариф.

**Навыки и библиотеки:**
Pandas, NumPy, Matplotlib, SciPy, статистический анализ, проверка гипотез.

**Вывод:**
В ходе анализа подтвердилось различие в выручке пользователей разных тарифов. 
Различие средней выручки абонентов Москвы и других регионов не выявлено. 


## [4. Исследование игровых платформ](/Games-platforms-analysis)

**Задача:**
Определить актуальные и наиболее прибыльные игровые платформы по историческим данным о продажах игр. 
Найти наиболее популярные жанры в различных регионах.

**Использованные библиотеки:** 
Pandas, NumPy, Matplotlib, SciPy, Requests, статистический анализ, проверка гипотез, http запросы.

**Вывод:**
По результатам анализа выявлено что для планирования игр продаж на **2017 год** стоит ориентироваться на игровые платформы **Playstation 4** и **Xbox One**. 
Они являются актуальными и наиболее прибыльными на текущих период **с 2013 года**.
Наиболее перспективным жанром являются **Action**, **Shooter** и **Sports** с возрастным рейтингом **17+**, **для всех возрастов** и **10+ лет**.

## [5. Рекомендации нового тарифа телеком компании](/Telecom-tariff-recommendation)

Анализ поведения клиентов, использующих архивные тарифы, для рекомендации новых тарифов.

**Задача:**
Построить модель классификации для рекомендации нового тарифа.

**Использованные библиотеки:** 
Pandas, NumPy, Scikit-learn, Catboost, различные модели классификации, подбор параметров, проверка моделей на вменяемость.

**Вывод:**
- Сравнение результата случайной модели с другими доказывает вменяемость всех рассмотренных моделей. 
- По результатам тестирования модели выделены две с наибольшими результатами. `RandomForestClassifier` и `CatBoostClassifier`. 
Так как разница между ними не велика и скорость обучения модели CatBoost выше, то данная модель выбрана как наиболее предпочтительная.

## [6. Прогнозирование оттока клиентов банка](/Bank-customer-churn-modelling)

**Задача:**
По историческим данным поведения клиентов и расторжении договоров спрогнозировать возможный уход клиента.

**Использованные библиотеки:** 
Pandas, NumPy, Scikit-learn, Matplotlib, Catboost, различные модели классификации, подбор параметров, балансировка классов.

**Вывод:**
По результатам тестирования модели выделены две с наибольшими результатами. 
Это случайны лес `RandomForestClassifier`с уменьшением в выборке доли отрицательных результатов и CatBoost `CatBoostClassifier`. 
Обе модели показали значение F1-меры выше требуемого значения.

## [7. Определение наиболее перспективного региона](/Search-Promising-Region)

**Задача:**
По характеристикам нефтяных скважин в различных регионах определить регион с наибольшей прибылью. 

**Использованные библиотеки:** 
Pandas, NumPy, Scikit-learn, Matplotlib, Catboost, Seaborn, различные модели классификации, подбор параметров, bootstrap.

**Вывод:**
Найдено распределение прибыли для каждого региона, риск убытков и средняя прибыль. По этим характеристикам выбран регион для разработки скважин. 
