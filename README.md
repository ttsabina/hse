# Исследовательский мини-проект "Аудитория English-сообществ ВК"

## Описание проекта
Данный исследовательский мини-проект посвящен анализу социально-демографических характеристик подписчиков пяти крупных сообществ по изучению английского языка в социальной сети ВКонтакте. Целью исследования является выявление особенностей аудитории таких сообществ и получение инсайтов о том, кто интересуется изучением английского языка онлайн.

## Источники данных
Данные получены через API ВКонтакте. Для исследования выбраны 5 популярных образовательных платформ:
- Skillbox
- Фоксфорд
- Яндекс Практикум
- Skyeng
- Инглекс

## Методология
1. Подключение к API ВКонтакте с использованием токена доступа
2. Получение списка участников каждого сообщества
3. Получение подробной информации о пользователях (демографические данные)
4. Объединение и преобразование данных для анализа
5. Визуализация результатов

## Используемые библиотеки
- pandas, numpy - для работы с данными
- matplotlib, seaborn - для визуализации
- requests - для API-запросов
- pickle - для сохранения промежуточных результатов
- datetime, time - для работы с датами и паузами между запросами

## Анализируемые признаки
- Пол пользователей
- Возраст
- Принадлежность к поколению (Alpha, Z, Миллениалы, X, Бумеры)
- Город проживания
- Сезон рождения
- Активность пользователя (участие в нескольких сообществах)

## Результаты исследования
- Распределение пользователей по сообществам
- Гендерный состав аудитории каждого сообщества
- Возрастные характеристики подписчиков
- Географическое распределение пользователей
- Уровень активности аудитории

## Автор
Тхамокова Сабина БМД239