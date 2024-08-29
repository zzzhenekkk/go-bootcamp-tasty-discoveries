# Go Bootcamp: Day 03 - Вкусные Открытия на Go

## Описание

Этот проект представляет собой серию упражнений на Go, направленных на разработку API для работы с данными о ресторанах. Утилиты включают загрузку данных, создание простейших интерфейсов, обеспечение безопасности с помощью JWT и предоставление рекомендаций по ближайшим ресторанам на основе геолокации.

## Задачи

1. **Exercise 00: Загрузка данных**
   - Реализация утилиты для загрузки данных о ресторанах в формате JSON. Эти данные будут использованы в следующих заданиях.

2. **Exercise 01: Создание простого интерфейса**
   - Разработка простейшего интерфейса для взаимодействия с загруженными данными через API, включая обработку запросов и вывод данных.

3. **Exercise 02: Правильное API**
   - Создание более сложного API с поддержкой фильтрации и сортировки ресторанов по различным критериям, включая геолокацию.

4. **Exercise 03: Ближайшие рестораны**
   - Реализация функции, которая на основе текущей геолокации пользователя предоставляет список ближайших ресторанов.

5. **Exercise 04: JWT Аутентификация**
   - Внедрение аутентификации с помощью JWT для защиты API. Пользователи должны получить токен, чтобы получить доступ к защищенным маршрутам API.

## Правила

- Программа не должна завершаться с ошибкой на корректных данных.
- Вся обработка входных данных должна быть тщательно проверена, чтобы избежать HTTP 500 и других ошибок сервера.
- Использование внешних зависимостей должно управляться с помощью Go Modules.
- Программа должна компилироваться с помощью команды `go build`.
