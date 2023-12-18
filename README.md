# ux-events-recommender
Модульное задание 2

Телеграм Бот для рекомендации необычных событий.

Облачные функции:
- back-offce - функция для запросов к бд, логирования поведения пользователей, создания .ics файлов и сохранения в Object Storage.
- events-rec-api -  функция для формирования рекомендации
- ics-to-zip - функция, вызываемая триггером при формирования файла с суффиком .zip в Object Storage. Отправляет пользователю сформированный .ics файл.
- ux-events-recommeder-bot - основная функция для общения с TG ботом.

API-gateways:
- ux-event-recommender-bot-gateway - основной API шлюз для общения с TG ботом.
- events-rec-api-gateway - API-шлюз, описывающий API-запросы. 

