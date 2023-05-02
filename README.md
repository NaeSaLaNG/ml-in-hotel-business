<h2 style = "text-align:center;
             font-size:30px;"> Описание задачи </h2>
    
Для привлечения клиентов на свой сайт сеть отелей добавила возможность бронирования номеров без предоплаты. Однако, если клиент отменял бронирование, компания терпела убытки. Например, сотрудники отеля могли закупить продукты для гостя, который в итоге не приехал, или не успеть найти другого клиента на забронированный номер.

Для решения этой проблемы была разработана система, которая предсказывает вероятность отказа от бронирования. Если модель показывает, что бронь может быть отменена, то клиенту предлагается внести депозит в размере 80% от стоимости номера за одни сутки и затрат на разовую уборку. Если клиент все же отменит бронь, деньги будут списаны со счета клиента.

В результате внедрения системы удалось получить прибыль в размере 73,013,814 рублей. Из этой суммы 20,622,104 рублей - это доход, принесенный именно системой, что в 50 раз больше стоимости ее внедрения. Кроме того, прибыль, которую система принесла, составляет 28% от общего дохода отеля.

Эта работа была выполнена в рамках обучения в ЯндексПрактикуме.

<h2 style = "text-align:center;
             font-size:30px;"> Описание данных </h2>

**Описание признаков:**

- id — номер записи;
- adults — количество взрослых постояльцев;
- arrival_date_year — год заезда;
- arrival_date_month — месяц заезда;
- arrival_date_week_number — неделя заезда;
- arrival_date_day_of_month — день заезда;
- babies — количество младенцев;
- booking_changes — количество изменений параметров заказа;
- children — количество детей от 3 до 14 лет;
- country — гражданство постояльца;
- customer_type — тип заказчика:
- days_in_waiting_list — сколько дней заказ ожидал подтверждения;
- distribution_channel — канал дистрибуции заказа;
- is_repeated_guest — признак того, что гость бронирует номер второй раз;
- lead_time — количество дней между датой бронирования и датой прибытия;
- meal — опции заказа:
- previous_bookings_not_canceled — количество подтверждённых заказов у клиента;
- previous_cancellations — количество отменённых заказов у клиента;
- required_car_parking_spaces — необходимость места для автомобиля;
- reserved_room_type — тип забронированной комнаты;
- stays_in_weekend_nights — количество ночей в выходные дни;
- stays_in_week_nights — количество ночей в будние дни;
- total_nights — общее количество ночей;
- total_of_special_requests — количество специальных отметок.

Целевым признаком является is_canceled — отмена заказа;

<h2 style = "text-align:center;
             font-size:30px;"> План работы </h2>
    
1. Загрузка и предобработка данных.
2. Обучение различных моделей:
- LogisticRegression;
- DecisionTreeClassifier;
- Random Forest;
3. Выбор наилучшей модели.
4. Анализ влияния различных параметров на результат.
5. Выполнение прогноза для тестовой выборки.
6. Подсчет прибыли;
7. Описание портрета «ненадёжного» клиента.
