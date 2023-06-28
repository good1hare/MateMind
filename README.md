# MateMind

MateMind - телеграмм бот, который поможет вам управлять задачами, устанавливать напоминания и создавать быстрые заметки.
Он предоставляет функции по созданию, редактированию и отслеживанию задач, а также возможность создавать заметки и
сохранять их в удобном формате. Бот позволяет быть в курсе всех своих задач и не пропустить ни одного важного события,
благодаря функции напоминаний. Начните использовать MateMind уже сегодня и станьте более продуктивным!

## Installation

Конфиги читаются из config/config.yml(для разработки локально), затем если есть перезаписываются файлом config.env(для
прода или дев на сервере)

Описание взаимодействия базы данных и таблиц [PostgreSQL](README_PostgreSQL.md)

Создание миграций
migrate create -ext sql -dir migrations table_name