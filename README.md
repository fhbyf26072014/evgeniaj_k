ИИ-ассистент для консультаций по Ведической астрологии
ссылка на проект: https://t.me/life_on_star_bot
Скриншот 1 https://github.com/fhbyf26072014/evgeniaj_k/blob/main/SI0dbNb0N4s.jpg
Описание проекта
Проект "ИИ-ассистент для консультаций по Ведической астрологии" представляет собой инновационное решение, которое сочетает в себе возможности искусственного интеллекта и традиционные знания ведической астрологии. Ассистент создан для помощи пользователям в получении информации о ведической астрологии, ответах на их вопросы и организации консультаций с экспертами.
Проект ИИ-ассистент для консультаций по Ведической астрологии работает через TELEGRAMM
Функционал
1. Осмысленное ведение диалога с помощью нейросети
Ассистент способен поддерживать естественный диалог с пользователем, понимая контекст и предоставляя релевантные ответы.
Благодаря использованию современных технологий обработки естественного языка, ассистент может адаптироваться к различным стилям общения и уровням знаний пользователей.
2. Ответы на вопросы по базе знаний
Ассистент использует специально подготовленную базу знаний, которая содержит информацию о ведической астрологии, включая основные принципы, планеты, дома, знаки зодиака и их влияние на жизнь человека.
Пользователи могут задавать как простые, так и сложные вопросы, связанные с ведической астрологией, и получать точные и информативные ответы.
3. Запись клиента на консультацию и добавление встречи в Google Календарь
Ассистент позволяет пользователям записываться на консультации с экспертами по ведической астрологии прямо через чат.
После записи ассистент автоматически создает событие в Google Календаре, чтобы клиент не забыл о предстоящей встрече.
Используемые сервисы
1. Qwen
Назначение : Qwen был использован для создания системного промпта и базы знаний ассистента.
Особенности :
Системный промпт определяет правила поведения ассистента, его стиль общения и границы компетенции.
База знаний содержит подробную информацию о ведической астрологии, которая используется при генерации ответов на вопросы пользователей.
2. Savvy (https://suvvy.ai/ )
Назначение : Savvy был создан для создания самого ИИ-ассистента.
Особенности :
Платформа предоставляет удобный интерфейс для настройки и управления ассистентом.
Поддерживает интеграцию с различными внешними сервисами, включая Google Календарь.
Технические детали
Архитектура
Фронтенд : Интерфейс взаимодействия с пользователем реализован через чат-платформу.
Бэкенд : Обработка запросов и управление базой знаний осуществляется с помощью API Qwen и Savvy.
Интеграция с Google Календарем : Для записи на консультации используется API Google Calendar.
Инструменты разработки
Язык программирования : Python
Библиотеки : Requests, Flask (для серверной части), Google Calendar API
СУБД : SQLite (для хранения данных о пользователях и записях)
Как начать работу
Установка зависимостей
Убедитесь, что у вас установлен Python 3.8 или выше.
Установите необходимые библиотеки, выполнив команду:
bash
Копировать
1
pip install -r requirements.txt
Настройка API ключей
Получите API ключи для Qwen и Google Calendar.
Сохраните их в файл .env в корне проекта.
Запуск сервера
Запустите сервер, выполнив команду:
bash
Копировать
1
python app.py
Тестирование
Откройте чат-интерфейс и начните общаться с ассистентом.
Документация
Дополнительная документация доступна в следующих разделах:

API Qwen
API Google Calendar
Возможности для развития
Расширение базы знаний
Добавление более специализированной информации о различных аспектах ведической астрологии.
Мультиязычность
Добавление поддержки других языков для расширения аудитории.
Интеграция с другими календарями
Возможность работы с календарями Outlook и Apple Calendar.
Аналитика
Добавление системы аналитики для отслеживания популярных вопросов и тем.
Лицензия
Этот проект распространяется под лицензией MIT. Подробности см. в файле LICENSE .
Добавление эмодзи
Добавление соответствующих хэштэгов
Авторы
Имя автора - Роль - GitHub

