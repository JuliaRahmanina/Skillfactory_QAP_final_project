# Skillfactory_QAP_final_project

33.1. Итоговый проект по автоматизации тестирования (PJ-04)

Объектом тестирования является форма авторизации сайта Ростелеком https://b2c.passport.rt.ru/

Тестирование выполнено в автоматическом режиме с использованием методов ручного тестирования.

Перед началом тестирования необходимо установить следующие библиотеки PyCharm:
selenium версия 4.9.0 ;
pytest-selenium версия 4.0.0 ;
pytest версия 6.2.5 ;
termcolor

На диске C: необходимо разместить chromedriver.exe версии 131.0.6778.204, соответствующий версии браузера Google Chrome.

Для запуска всех тестов используется команда в терминале:
python -m pytest -v --driver Chrome --driver-path C:\chromedriver.exe tests

Для запуска отдельного теста используется команда с наименованием теста, например:
python -m pytest -v --driver Chrome --driver-path C:\chromedriver.exe  tests\test_auth_page_check.py

Ссылка на чек-лист, тест-кейсы и баг-репорт:
https://docs.google.com/spreadsheets/d/1kUs-ApeqpHk4qW8a2dKcJxPah9OrftycvS6uWgdT3F4/edit?usp=sharing
