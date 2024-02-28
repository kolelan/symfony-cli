# Проект для консольного приложения на Symfony Console
Здесь инфраструктура для работы с приложением написанным на symfony console.  
Здесь будет конфигурационные файлы, контейнер внедрения, подготовка тестов, подключение базы данных.  
Вся инфраструктура будет на контейнерах Docker, возможно в отдельной ветке на LXC.
Я хочу обслуживать в консоли небольшой api для микросервиса, по этому планирую добавить Slim. 
## Структура проекта
- app - приложение
- data - папка, данные из которой попадут в контейнер консольного приложения как дополнительный том
- database - папка для подключения базы данных
- db - раздел с контейнером для работы базы данных (mysql, postgres)

# Реализовано
[Что готово](./Readme_ready.md)
[Что будет сделано](./Readme_comming.md)
