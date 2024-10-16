
Описание коллекции тестов

В этой коллекции тестов мы проверяем различные API, связанные с данными о геолокации, финансовых организациях, курсах валют и другими справочными данными. Коллекция включает в себя тесты для следующих API:

Поиск по телефону: Проверка формата телефона, валидности номера и наличия данных о стране и городе.
Проверка электронного адреса: Валидация формата email, проверки наличия локальной и доменной частей.
Поиск организаций по ИНН: Проверка наличия всех необходимых данных, таких как ИНН, название, данные о руководстве и статусе.
Получение курсов валют: Проверка наличия данных о валюте, включая коды, названия и страны.
Поиск по станциям метро: Проверка наличия данных о станциях, включая названия, координаты и линии.
Поиск города по IP: Проверка данных о местоположении, включая почтовый код, страну, регион и координаты.
Поиск компаний по названию: Проверка данных о компании, включая ИНН, данные о руководстве, статус и тип.
Тестовые кейсы

Каждый тест включает в себя проверку на:

Статус кода ответа
Структуру ответа
Наличие необходимых данных
Валидность форматов (например, телефон, email)
Содержимое ключевых полей (например, название, коды, статус)

In this collection of tests, we validate various APIs related to geolocation data, financial organizations, currency exchange rates, and other reference data. The collection includes tests for the following APIs:

Phone Lookup: Validation of phone number format, number validity, and presence of country and city data.
Email Validation: Validation of email format, checking the presence of local and domain parts.
Organization Lookup by INN: Verification of all necessary data, such as INN, name, management details, and status.
Currency Exchange Rates: Checking for currency data, including codes, names, and countries.
Metro Station Lookup: Verification of station data, including names, coordinates, and lines.
City Lookup by IP: Checking location data, including postal code, country, region, and coordinates.
Company Name Lookup: Validation of company data, including INN, management details, status, and type.
Test Cases

Each test includes checks for:

Response status code
Response structure
Presence of required data
Format validity (e.g., phone, email)
Content of key fields (e.g., names, codes, status)

baseUrl = https://suggestions.dadata.ru/suggestions/api/4_1/rs/suggest/
token = your api key
S_token = your secret key
you will receive these keys when you sign up for dadata.ru . They are located in the profile settings
