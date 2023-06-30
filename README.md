# Saw-Difficulty-Curve-in-Match3
Проект выполнен в рамках Тестового задания на позицию Product Analyst на матч3 проект.

ТЗ и его решение можно найти по ссылке https://voracious-gallon-829.notion.site/Product-Analyst-1e5a8500b01c4f2e8296bf65305f4faf
# **Задачи**:

- Проанализируйте пилу с точки зрения баланса хард валюты и оттока.
- Предложите а/б тест с сильной гипотезой для улучшения баланса пилы.

# Датасет:

В файле saw.csv следующие данные:

- **SawStep** :шаг пилы с уровнем, который игрок должен выиграть, чтобы
пройти далее(номер шага обозначает порядок появления уровня у игрока)
- **cry_per_user**: на каждом шаге пилы игроки тратят хард валюту
- **churn**: с каждого шага пилы уходит процент игроков
- **LRC**: каждый шаг имеет свою сложность для игрока(процент поражений от всех
стартов на шаге).

## Цель исследования

> **Наша основная цель:** балансировать между монетизацией и удержанием так , чтобы траты хард валюты увеличивались, а отток пользователей был минимальный
>
