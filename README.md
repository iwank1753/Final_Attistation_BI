### Итоговая аттестация

## Описание бизнес кейса

Авто дилер Премиум Авто хочет проанализировать эффективность маркетинговых кампаний в интернете. Так как у самой компании не хватает компетенций для такого анализа, то она наняла консалтинговую IT компанию, которая должна помочь ему в этом проекте. В ходе пресейла консультанты договорились с клиентом, что сделают пилотный проект на основании ограниченных данных за 1,5 месяца и по двум маркам: BMW и Mercedes. Если результаты пилотного проекта устроят заказчика, то будет заключен полноценный контракт на внедрение проекта, который будет позволять отслеживать эффективность маркетинга на постоянно основе.

В рамках пилотного проекта, мы решили объединить данные из Google analytics и CRM системы, для того, чтобы посмотреть какие кампании приводят не только к заявкам, но и к продажам. Наши коллеги внедрили Client ID, который пробрасывается из web аналитики в CRM, данные были накоплены за несколько месяцев и параллельно были созданы коннекторы к Google analytics и CRM. Текущая наша задача заключается в том, чтобы забрать данные из систем, объединить их, вывести недостающие данные и на их основе выдать клиенту дашборд, который ответить на его вопросы.

Описание датасета и инструментария:

* Данные из 2 систем
* 2 рабочие таблицы
* 1 справочник
* 1 источник внешний из интернета
Проект можно выполнить по-разному, поэтому вы можете сами выбирать инструмент, в котором выполняете задание: Excel, Power BI или Python. Однако вы должны использовать все три инструмента на разных этапах работы.

# Подготовка данных

Ссылка на данные
Выделите в Маркетинговых данных признак марки и модели автомобиля
Загрузите данные по курсам валют на дату с сайта ЦБ РФ
Объедините все 4 получившиеся таблицы
Добавьте недостающие показатели в Справочник: Итоговую стоимость в рублях и маржу в рублях
Добавьте недостающие данные: цепочки касаний, сумма конверсий по цепочкам, признак конверсии по цепочкам, сумма касаний для каждой цепочки и соответственно каждого пользователя.
# Аналитика

Рассчитайте следующие показатели:

Из каких регионов больше всего заявок
Какой средний процент отказов (Bounce)
С каких устройств чаще заходят на сайты
Какие источники наиболее конвертируемые
Рассчитайте ROMI (при расчете придумайте методологию расчета средней стоимость проданного автомобиля)
Посчитайте выручку в рублях только по долларовым позициям
Определите, какой источник трафика наиболее выгоден для компании по текущим данным
Ответьте на вопрос: каких показателей не хватает, чтобы посчитать чистую прибыль?
Сделать прогноз до конца февраля по количеству конверсий на каждый день
Какая будет выручка за первый квартал, если средняя стоимость авто останется неизменной, а продажи будут пропорциональны текущим данным?
# Визуализация

Настройте цветовую тему и оформите дашборд, который содержит следующую информацию:

Цепочки касаний с дополнительными полезными характеристиками и с раскраской в зависимости от того, была ли продажа у цепочки
Карту продаж по регионам и городам
Матрицу с воронкой продаж по каждой модели и марке
Количество продаж по источникам трафика с линией отсечки в 230
Декомпозицию продаж по источникам трафика (Source, Medium, Keyword, Campaign)
Продажи за каждый день с раскраской по выполнению целевых показателей (их выберете сами)
Фильтр по количеству касаний и признаку конверсии + любые другие полезные фильтры, которые посчитаете нужным (от 5 до 7 фильтров всего)
Среднее количество касаний в цепочке
Всего нужно выполнить 24 пункта по всем направлениям, в зависимости от того, сколкьо пунктов удалось выполнить будет ставиться оценка:

Менее 60% пунктов (15 п) - не сдано 60 - 74% (15-18) - Удовлетворительно 75 - 89% (18-22) - Хорошо 90 - 100% (22-24) - Отлично
