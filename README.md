Решение тестового задания: Excel (Power Query), SQL (SQLite) и Python (pandas).

Структура репозитория:
.
├── README.md                          # этот файл
├── Тестовое задание.docx              # оригинал задания
├── Part1_Excel.xlsx                   # Excel-часть: витрина, сводные таблицы, графики
├── Part2_SQL.txt                      # SQL-часть: 6 запросов с ответами
├── Part3_PyPandas.ipynb               # Python-часть: анализ в pandas
├── python/                            # исходные данные для Python-части
│   ├── orders.csv                     # заказы
│   └── product_info.csv               # справочник товаров
├── db/                                # исходные данные для SQL-части
│   └── test.db                        # база SQLite с таблицами orders и customers
└── excel/                             # исходные данные для Excel-части
    ├── customers.csv                  # клиенты
    ├── orderitems.csv                 # позиции заказов
    ├── orders.csv                     # заказы
    └── products.csv                   # товары

Установка зависимостей для Python-части:
pip install pandas numpy holidays

Запуск Python-части:
Ноутбук Part3_PyPandas.ipynb ожидает файлы orders.csv и product_info.csv в папке python/ рядом с ноутбуком:
Part3_PyPandas.ipynb
python/orders.csv
python/product_info.csv
