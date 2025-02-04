# weather_bot

Этот проект представляет собой телеграм-бота, который использует нейросеть для предсказания погоды на следующий день. Бот построен на Python и интегрируется с Telegram API. Модель нейросети анализирует исторические данные о погоде для более точных прогнозов.

## Функции
- Прогнозирует погоду на следующий день, используя исторические данные.
- Предоставляет пользователям информацию о температуре.
- Бот обучается каждый день в 12:00, обновляя модель на основе новых данных.
- Бот отправляет прогноз погоды всем пользователям каждый день в 18:00.
- Удобное взаимодействие через интерфейс Telegram.
- Использует нейросеть для повышения точности предсказаний.

## Используемые технологии
- Python 3.x
- TensorFlow
- Telegram Bot API
- numpy
- meteostat
- schedule
- threading

## Планы
На данный момент бот предсказывает погоду только по средней температуре за последние дни, но вскоре будут добавленны функции по получению данных о других метеорологических изменениях, что улучшит качество и достоверность прогнозов

## Использование
### Скачивание
Перейдите к файлу weather_bot.py и скачайте его
### Установка библиотек
Установите библиотеки(команды для их скачивания есть в начале кода)
### Подготовка данных
Отредактируйте данные согласно комментариям из к строкам из кода
### Запуск
Запустите код
