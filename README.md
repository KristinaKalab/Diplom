# Diplom
Дипломная работа по автоматизации UI и API тестов для сайта Читай-город

### Шаги
1. Склонировать проект 'git clone https://github.com/KristinaKalab/Diplom.git
2. Установить зависимости
3. Запустить тесты 'pytest'
4. Необходимо выполнить команду: pytest --alluredir results (создание папки с результатами тестов)
5. Затем выполнить команду: allure generate final-report (отчет с файлами тестирования)
6. Для автоматического запуска тестов выполнить команду в консоли ./run.sh Отчет автоматически откроется в вашем браузере

### Стек:
- pytest
- selenium
- requests
- allure

### Струткура:
- ./test - тесты
- ./pages - описание страниц

### Библиотеки (!)
- pyp install pytest
- pip install selenium
- pip install webdriver-manager
- pip install allure-pytest