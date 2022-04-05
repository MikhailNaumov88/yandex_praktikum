# Портфолио проектов Яндекс.Практикум
В данном репозитории собраны проекты, которые были выполнены в ходе обучения в Яндекс.Практикуме, профессии 'Специалист по Data Science'.

 Название проекта | Статус проекта | Задачи проекта | Описание проекта | Навыки и инструменты 
----------------- |--------------- | -------------- | ---------------- | -------------------- 
[Исследование надёжности заёмщиков — анализ банковских данных]() | Готов | На основе статистики о платёжеспособности клиентов исследовать влияет ли семейное положение и количество детей клиента на факт возврата кредита в срок | Входные данные от кредитного отдела банка  — статистика о платёжеспособности клиентов. Очищены данные от выбросов, пропусков и дубликатов, а также преобразованы разные форматы данных. Заменены типы данных на соответствующие хранящимся данным. Удалены дубликаты. Выделены леммы в значениях столбца и категоризированны данные. Определена доля кредитоспособных клиентов. Проанализировано влияние семейного положения и количества детей клиента на факт возврата кредита в срок. Построена модель кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку. | `лемматизация`, `предобработка данных` , `Pandas`, `PyMystem3`
[Продажа квартир в Санкт-Петербурге — анализ рынка недвижимости]() | Готов | Используя данные сервиса Яндекс.Недвижимость, определить рыночную стоимость объектов недвижимости и типичные параметры квартир. | Проведен исследовательский анализ и предобработка данных для датасета с объявлениями о продаже квартир в Санкт-Петербурге. Выявлены, влияние площади, потолков, количества комнат, даты объявления на цены квартир всех представленных населённых пунктов и центра Санкт-Петербурга для построения автоматизированной системы определения цен во избежание мошенничества и аномалий. На основе данных сервиса Яндекс.Недвижимость определена рыночная стоимость объектов недвижимости разного типа, типичные параметры квартир, в зависимости от удаленности от центра. Проведена предобработка данных. Добавлены новые данные. Построены гистограммы, боксплоты, диаграммы рассеивания. | `исследовательский анализ данных`, `визуализация данных`, `предобработка данных`,  `Pandas`, `Seaborn`, `Matplotlib`
[Определение выгодного тарифа для телеком компании]() | Готов | На основе данных клиентов оператора сотовой связи проанализировать поведение клиентов и поиск оптимального тарифа | Проведен предварительный анализ использования тарифов на выборке клиентов, проанализировано поведение клиентов при использовании услуг оператора и рекомендованы оптимальные наборы услуг для пользователей. Проверены гипотезы о различии выручки абонентов разных тарифов и различии выручки абонентов из Москвы и других регионов. Определен выгодный тарифный план для корректировки рекламного бюджета. |  `Pandas`, `NumPy`, `Seaborn`, `Matplotlib`, `SciPy`
[Рекомендация тарифов для компании]() | В работе | На основе полученных и проанализированых ранее данных клиентов оператора сотовой связи разработать модель классификации, которая будет наиболее точно предлагать клиентам новый тариф | Разработана система, способная проанализировать поведение клиентов и предложить пользователям новый тариф. Построена модель для задачи классификации, которая выберет подходящий тариф. Построена модель с максимально большим значением accuracy. Доля правильных ответов доведена до 0.81. Проверены accuracy на тестовой выборке и оценена модель на вменяемость. |  `машинное обучение`, `Pandas`, `NumPy`, `Sklearn`
[Отток клиентов банка]() | Не начат | Анализ оттока клиентов из банка для выбор стратегии (удержание старых клиентов или привлечение новых клиентов). | Из банка стали уходить клиенты каждый месяц. Спрогнозирована вероятность ухода клиента из банка в ближайшее время. Построена модель с предельно большим значением F1-меры с последующей проверкой на тестовой выборке. Доведена метрика до 0.60. Дополнительно измерен AUC-ROC, соотнесен с F1-мерой. Построена Матрица ошибок. Обучение с учителем. Работа с несбалансированными данными. | `Pandas`, `NumPy`, `Sklearn`, `Seaborn`, `Matplotlib`, `category_encoders`, `imblearn`, `SciPy`
[Анализ рынка видеоигр]() | Не начат | Используя исторические данные о продажах компьютерных игр, оценки пользователей и экспертов, жанры и платформы, выявить закономерности, определяющие успешность игры , чтобы сделать ставку на потенциально популярный продукт и спланировать рекламные кампании. | Интернет-магазин продаёт по всему миру компьютерные игры. Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы. Выявлены параметры, определяющие успешность игры в разных регионах мира. Выявлен потенциально популярный продукт и спланированы рекламные кампании. Выбран актуальный период для анализа. Составлены портреты пользователей каждого региона. Проверены гипотезы: средние пользовательские рейтинги платформ Xbox One и PC одинаковые, средние пользовательские рейтинги жанров Action и Sports разные. При анализе использовались критерий Стьюдента для независимых выборок и bootstap-метод, основанный на многократной генерации выборок методом Монте-Карло |`описательная статистика`, `проверка статистических гипотез`, `Pandas`, `NumPy`, `Seaborn`, `Matplotlib`, `SciPy`
[Выбор локации для бурения нефтяных скважин]() | Не начат | Решить в каком регионе добывать нефть. Построить модель машинного обучения, которая поможет определить регион, где добыча принесет наибольшую прибыль с наименьшим риском убытков. | Добывающей компании «ГлавРосГосНефть» нужно решить, где бурить новую скважину. Собраны характеристики пробы нефти для скважин: качество нефти и объём её запасов по трем регионам. Характеристики для каждой скважины в регионе уже известны. Построена модель для предсказания объёма запасов в новых скважинах.Выбраны скважины с самыми высокими оценками значений. Определены регионы с максимальной суммарной прибылью отобранных скважин. Построена модель для определения региона, где добыча принесёт наибольшую прибыль. Проанализирована возможная прибыль и риски техникой Bootstrap. |  `Pandas`, `NumPy`, `Sklearn`, `Seaborn`, `Matplotlib`, `Math`
[Подготовка прототипа модели для металлообрабатывающего предприятия]() | Не начат | Разработка модели, предсказывающей коэффициент восстановления золота из золотосодержащей руды.| Компания разрабатывает решения для эффективной работы золотодобывающей отрасли. Построена модель, предсказывающая коэффициент восстановления золота из золотосодержащей руды. Проанализированы данные с параметрами добычи и очистки. Построена и обучена модель, помогающая оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками. | `Pandas`, `NumPy`, `Sklearn`
[Разработка алгоритма для защиты данных]() | Не начат | Методом преобразования данных защитить личную информацию клиентов страховой компании. | Для защиты данных клиентов страховой компании разработаны методы преобразования данных, чтобы по ним было сложно восстановить персональную информацию.  Была проведена предобработка данных. Произведена проверка работы алгоритма модели линейной регрессии при перемножении на обратимую матрицу. Произведена проверка влияния перемножения на обратимую матрицу, а затем перемножения на обратную матрицу обратимой. Произведена проверка метрики R2 Линейной регрессии на идентичных данных - сначала исходных, затем умноженных на обратимую матрицу, размер которой равен числу признаков. Метрики полностью совпали. Можно сделать вывод, что алгоритм работает. |  `Pandas`, `NumPy`, `Sklearn`
[Предсказание цены автомобиля]() | Не начат | Обучить модель для определения рыночной стоимости автомобиля. | Сервис по продаже автомобилей с пробегом разрабатывает приложение для привлечения новых клиентов. В нём можно быстро узнать рыночную стоимость своего автомобиля. Проанализированы данные: технические характеристики, комплектации и цены автомобилей. Построена модель для определения стоимости автомобиля с пробегом. Найдена оптимальная модель по качеству данных, времени обучения и времени предсказания | `Pandas`, `NumPy`, `Sklearn`, `CatBoost`, `Lasso`, '`LightGBM`
[Прогнозирование заказов такси]() | Не начат | Обучить модель для предсказания количества заказов такси на следующий час. | Проанализированы исторические данные о заказах такси в аэропортах. Спрогнозировано количество заказов такси на следующий час, чтобы привлекать больше водителей в период пиковой нагрузки. Построена модель для такого предсказания. Значение метрики RMSE на тестовой выборке должно меньше 48. Полученное значение метрики RMSE составило 40. | `Pandas`, `NumPy`, `Sklearn`, `CatBoost`, `StatsModels`, '`LightGBM`, `Matplotlib`, `Seaborn`
[Классификация комментариев]() | Не начат | Ускорить модерацию комментариев в сообществе, автоматизировав оценку их токсичности. Обучить модель классифицировать комментарии на позитивные и негативные. | Для запуска нового сервиса интернет-магазину нужен инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. Пользователи могут редактировать и дополнять описания товаров, как в вики-сообществах. То есть клиенты предлагают свои правки и комментируют изменения других. Обучена модель классифицировать комментарии на позитивные и негативные. Проанализирован набор данных с разметкой о токсичности правок. Построена модель со значением метрики качества F1 не меньше 0.75. К текстам и временным рядам применена техника feature engineering. |  `Pandas`, `NumPy`, `Sklearn`, `CatBoost`, `NLTK`, '`LightGBM`, `Matplotlib`, `Seaborn`
[Определение возраста по фото]() | Не начат | Построить модель, которая по фотографии определит приблизительный возраст человека. Есть набор фотографий людей с указанием возраста. |Сетевой супермаркет внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы и контролировать добросовестность кассиров при продаже алкоголя. Построена модель, которая по фотографии определит приблизительный возраст человека. Проанализирован набор фотографий людей с указанием возраста при помощи компьютерного зрения с привлечением готовых нейронных сетей и библиотеки Keras. | `Pandas`,`keras`, `Matplotlib`, `Seaborn`, `компьютерное зрение`
[Предсказание оттока клиентов оператора связи]() | Не начат | Обучить модель для предсказания оттока клиентов компании по услугам интернета и связи. | Проведен предварительный анализ использования услуг телеком-компании и анализ факторов влияния признаков на целевой признак, также созданы дополнительные признаки. С помощью анализа важности факторов отобраны налиучшие признаки для модели. Построена и выбрана наилучшая модель со значением метрики качества ROC-AUC 0.93 и точностью в 0.89. | `Pandas`,`СategoryEncoders`, `Matplotlib`, `Seaborn`, `Sklearn`, `CatBoost`, `LightGBM`



