ContactBook (книжка для хранения контактов)
===========

Доработанное тестовое задание в одну из компаний на ASP.NET разработчика.

Пользователю предлагается выбрать способ хранения контактов:
1. Оперативная память
2. XML
3. Linq to Xml
4. ADO.NET
5. Linq to Sql
6. Entity Framework
7. NHibernate

При хранении контактов в памяти данные сохраняются только в рамках одной сессии IIS.
При хранении контактов в xml в папке проекта App_Data создаетс xml файл.
Для хранения контактов в базе данных пользователю необходимо создать базу данных ContactBook на основе Sql Server.


В процессе разработки программы были реализованы следующие паттерны проектирования: 
1. Модель - Представление - Контроллер (ASP.NET)
2. Репозиторий (Наследники IContactRepository)
3. Синглтон (MemoryRepository.Instance)
