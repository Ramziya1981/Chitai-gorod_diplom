# DIPLOM_Chitai-gorod
Автоматизированные UI- и API-тесты из финальной работы по ручному тестированию "Тестирование интернет магазина книг “Читай- город”."
## Ссылка на [финальный проект по тестированию](https://skypro101-2.yonote.ru/share/d254b0c7-e725-4a9d-80fc-91219464de80)

## Шаблон для автоматизации тестирования на python

## Стек
* pytest
* selenium
* requests
* allure
* config 
* - _sqlalchemy_

## Полезные ссылки:
- [Подсказка по markdown](https://www.markdownguide.org/basic-syntax/)
- [Генератор  файла gitignore](https://www.toptal.com/developers/gitignore)

### Структура:
- ./test - тесты
- ./pages - описание страниц
- ./api - хелперы для работы с API
- ./db - хелперы для работы с БД

## Шаги
1. Склонировать проект ‘git clone https://github.com/Ramziya1981/DIPLOM_Chitai-gorod.git

2. Установить все зависимости

3. Запустить тесты ‘pytest’

* pytest - все тесты
* pytest tests/ui/ - только ui тесты
* pytest tests/api/ - только api тесты

4. Создать отчетность
* pytest --alluredir=allure-results - Запуск тестов с сбором данных для Allure
* allure generate allure-files -o allure-report - генерация отчета

5. Открыть отчет 'allure open allure-report'




## Библиотеки
* pip install pytest
* pip install selenium
* pip install webdriver-manager
* pip install allure-pytest
* pip install requests
* pip install flake8
