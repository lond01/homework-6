Завдання 5
Опис

Перемістити файл important_data.txt з поточної робочої директорії до директорії backup.

Реалізація

Для виконання завдання використовується модуль shutil мови Python.

import shutil

shutil.move("important_data.txt", "backup/important_data.txt")

Як це працює

shutil.move() переміщує файл з одного розташування в інше.

important_data.txt — файл, який потрібно перемістити.

backup/important_data.txt — нове розташування файлу в директорії backup.

Результат

Після виконання програми файл:

important_data.txt


буде переміщено до:

backup/important_data.txt

Структура директорій

До виконання:

project/
├── important_data.txt
└── backup/


Після виконання:

project/
└── backup/
    └── important_data.txt
