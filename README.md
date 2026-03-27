[![CI](https://github.com/Alina-botichka/health-status/actions/workflows/ci.yml/badge.svg)](https://github.com/Alina-botichka/health-status/actions/workflows/ci.yml)

# Game Health Status

Функция для определения статуса здоровья игрового персонажа.

## Описание

Функция `getHealthStatus` принимает объект персонажа с полями `name` и `health` и возвращает статус:
- `healthy` - здоровье более 50
- `wounded` - здоровье от 15 до 50 включительно
- `critical` - здоровье менее 15
