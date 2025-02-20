# MySQlCommands
Описание структуры таблицы
Чтобы посмотреть структуру новой таблицы введите:

DESCRIBE users;
Результат:
Структура новой таблицы

После создания таблиц их можно изменять, вот несколько полезных команд для изменения их структуры:

Переименование таблицы
ALTER TABLE имя_таблицы RENAME новое_имя_таблицы
Добавление столбца
ALTER TABLE имя_таблицы ADD имя_столбца тип_данных
Переименование столбца
ALTER TABLE имя_таблицы RENAME COLUMN старое_имя_столбца TO новое_имя_столбца;
Удаление столбца
ALTER TABLE имя_таблицы DROP имя_столбца
Удаление всей таблицы
DROP TABLE имя таблицы;
