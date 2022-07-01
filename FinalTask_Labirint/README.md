 Финальное задание по изучению автоматизации тестирования

В качестве объекта теcтирования выбран сайт https://www.labirint.ru/ 

 Запуск тестов:

1) Установить все внешние зависимости командой   
```pip install -r requirements.txt```

2) Скачать версию Selenium WebDriver, совместимую с вашим браузером  
(тесты проводились в браузере Google Chrome на операционной системе Windows)

3) Запуск тестов командами:

```python -m pytest -v --driver Chrome --driver-path ${PATH_TO_DRIVER} tests/test_main_page_header.py```

```python -m pytest -v --driver Chrome --driver-path ${PATH_TO_DRIVER} tests/test_main_page_body.py```

```python -m pytest -v --driver Chrome --driver-path ${PATH_TO_DRIVER} tests/test_main_page_footer.py```

```python -m pytest -v --driver Chrome --driver-path ${PATH_TO_DRIVER} tests/test_search.py```

```python -m pytest -v --driver Chrome --driver-path ${PATH_TO_DRIVER} tests/test_book_page.py```

```python -m pytest -v --driver Chrome --driver-path ${PATH_TO_DRIVER} tests/test_card_page.py```

   где ${PATH_TO_DRIVER} находится путь к драйверу Selenium для текущей ОС
