# Сезоны — прототип дашборда

Страницы: index (дашборд), sales (продажи), warehouse (склад), foodcost (фудкост)
Стили:
- app/base.css — общие (влияет на все страницы)
- app/dashboard.css / sales.css / warehouse.css / foodcost.css — свои страницы

Правишь страницу → её css; общую оболочку → base.css 
Семафор фудкоста инвертирован через .page-foodcost (рост = плохо).

Меню: Дашборд, Продажи, Склад, Закупки (purchases.html — заглушка), Фудкост.

Запуск: python3 -m http.server 8000 → http://localhost:8000/
