# Оптимизация маркетинговых затрат в онлайн-сервисе по продаже билетов на развлекательные мероприятия

На основе данных о посещениях сайта онлайн-сервиса стояла задача изучить, как люди пользуются продуктом, когда они начинают покупать, сколько денег приносит каждый клиент, когда он окупается.

Для выполнения поставленных задач был применен когортный анализ и рассчитаны:
1. продуктовые метрики DAU, WAU, MAU, Retention rate в разрезе пользователей, использующих сенсорные и стационарные устройства;
2. метрики электронной коммерции, такие как средний чек, LTV;
3. маркетинговые метрики CAC, ROMI в разрезе источников.
Полученные результаты были визуализированы в виде графиков, тепловых карт с использованием библиотек `Seaborn` и `Matplotlib`.

Проект был выполнен в ходе обучения в Яндекс.Практикуме, профессии "Аналитик данных".

## Общие выводы исследования

1. В результатае расчета ROMI было определено, что к 6-му месяцу окупаются все маркетинговые расходы на источники трафика;
2. К 12-му месяцу лучшим образом окупаются источники 4, 5 и 1, хуже всего окупаются расходы на источник 3;
3. В среднем пользователи начинают совершать покупку через полмесяца после первого посещения сайта;
4. Пользователи стационарных устройств имеют большую пользовательскую активность, чем пользователи сенсорных устройств;
5. LTV клиента больше для стационарных устройств, чем для сенсорных;
6. Маркетинговые расходы в основном направлены на источники, связанные со стационарными устройствами.

## Исходные данные

#### В этом исследовании представлены данные онлайн-сервиса с июня 2017 по конец мая 2018 года:

* лог сервера с данными о посещениях сайта онлайн-сервиса,
* выгрузка всех заказов за этот период,
* статистика рекламных расходов.

## Используемые библиотеки

1. Pandas
2. Seaborn
3. Matplotlib
4. Numpy

