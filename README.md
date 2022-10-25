# SQL-команды

    Show databases - просмотр данных
    Create database -создать базу данных
    Use - выбрать базу данных
    Source - позволяет выполнить сразу несколько команд
    Dropdatabase - удаление базы данных
    Show tables - просмотр всех таблиц из базы данных
    Create table - создание таблицы
    Describe - просмотр сведений о столбцах таблицы

    SELECT COUNT(*) FROM INFORMATION_SCHEMA.TABLES WHERE TABLE_TYPE = 'BASE TABLE'; (Было 6, стало 10)
    SELECT table_name FROM information_schema.tables WHERE table_schema = 'p518238'; (Kukina,TIMIRIUS, class, grades, mov, movi, movies, users)
    SELECT * FROM users; (261 пользователь)
    SELECT * FROM grades;(тут сложно описать)
    SELECT * FROM users, grades WHERE users.user_id = grades.user_id (Сверчков Павел КР и ЛР 5 и 4)
    SELECT * FROM users WHERE fam = 'Пергаев' (Тут Александр Пергаев)
