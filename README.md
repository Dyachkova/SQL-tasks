# SQL-tasks
SQL tasks

Описание данных

База данных об авиаперевозках:

Таблица airports — информация об аэропортах:
airport_code — трёхбуквенный код аэропорта
airport_name — название аэропорта
city — город
timezone — временная зона

Таблица aircrafts — информация о самолётах:
aircraft_code — код модели самолёта
model — модель самолёта
range — количество самолётов

Таблица tickets — информация о билетах:
ticket_no — уникальный номер билета
passenger_id — персональный идентификатор пассажира
passenger_name — имя и фамилия пассажира

Таблица flights — информация о рейсах:
flight_id — уникальный идентификатор рейса
departure_airport — аэропорт вылета
departure_time — дата и время вылета
arrival_airport — аэропорт прилёта
arrival_time — дата и время прилёта
aircraft_code – id самолёта

Таблица ticket_flights — стыковая таблица «рейсы-билеты»
ticket_no — номер билета
flight_id — идентификатор рейса
Таблица festivals — информация о фестивалях
festival_id — уникальный номер фестиваля
festival_date — дата проведения фестиваля
festival_city — город проведения фестиваля
festival_name — название фестиваля
