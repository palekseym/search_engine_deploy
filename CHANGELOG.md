# Changelog

## 2019-04-28

### Добавлено
- Развернул сервис мониторинга в kubernetes c использованием helm
- Добавил сущьность service для приложения crawler

## 2019-04-24

### Добавлено
- Сущности kubernetes: deployment, services для:
  - mongodb - база данных приложения
  - rabbitmq - очередь обработки для приложения
  - ui - web интерфейс приложения

- Сущности kubernetes: deployment для:
  - crawler - приложение обрабатывающее сайты
