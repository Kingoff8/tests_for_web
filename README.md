# Page Object
Репозиторий для курса Автоматизация тестирования с помощью python и selenium.

В коде нет комментариев, так как важно была только практическая часть и решения.

Установка зависимостей:
<code>pip install -r requirements.txt</code>

Тесты для ревью запускаются командой:
<code>pytest -v --tb=line --language=en -m need_review</code>

Если при запуске ошибка импорта
<code>ImportError:</code>
Удалите точки перед <code>pages</code> в импортах файлов test_main_page.py и test_product_page.py. Это не ошибка!
Такое случается из-за несовместимости обработки путей разных ОС.

Тестировалось на:
Python 3.8.5<br>
Linux Mint 20 х64


