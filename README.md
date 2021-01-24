# Page Object
Установка зависимостей:
<code>pip install -r requirements.txt</code>

Тесты для ревью запускаются командой:
<code>pytest -v --tb=line --language=en -m need_review</code>

Если при запуске ошибка импорта
<code>ImportError:</code>
убедитесь, что в корне проекта есть файл:
<code>__init__.py</code>
и удалите точки перед <code>pages</code> в импортах файлов test_main_page.py и test_product_page.py. Это не ошибка!
Такое случается из-за несовместимости обработки путей разных ОС.

Тестировалось на:
Python 3.8.5<br>
Linux Mint 20 х64 
