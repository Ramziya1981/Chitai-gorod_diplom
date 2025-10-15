# Chitai-gorod_diplom
Автоматизированные UI- и API-тесты из финальной работы по ручному тестированию "Тестирование интернет магазина книг “Читай- город”."
## Ссылка на финальный проект по тестированию: 
https://skypro101-2.yonote.ru/share/d254b0c7-e725-4a9d-80fc-91219464de80

## Шаги
1.Склонировать проект ‘git clone https://github.com/Ramziya1981/Chitai-gorod_diplom

2.Установить все зависимости

3.Запустить тесты ‘pytest’

* pytest - все тесты
* pytest tests/ui/ - только ui тесты
* pytest tests/api/ - только api тесты

4.Создать отчетность
pytest --alluredir=allure-results - Запуск тестов с сбором данных для Allure
allure generate allure-files -o allure-report - генерация отчета
5.Открыть отчет 'allure open allure-report'

## Стек
pytest
selenium
requests
allure
config

## Структура проекта
### config/ # Конфигурационные файлы
### init.py
### environment.py # Настройки окружения и URL
### pages/ # Page Object модели
### init.py
### base_page.py # Базовый класс для страниц
### main_page.py # Главная страница
### search_page.py # Страница поиска
### advanced_search_page.py # Расширенный поиск
### api/ # API тесты
### test_api_chitai_gorod.py
### ui/ # UI тесты
### init.py
### test_ui_chitai_gorod.py
### requirements.txt # Зависимости проекта
### README.md # Документация

## Библиотеки
pip install pytest
pip install selenium
pip install webdriver-manager
pip install allure-pytest
pip install requests
pip install flake8
