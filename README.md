

# Пергаев Александр 051
> SQL-команды

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

> Шпора ЕГЭ

$$BaCl_{2}+Na_{2}SO_{4}=BaSO_{4}\downarrow +2NaCl$$

$$\bar E_1^{2}=\sqrt{\frac{Fa^{2-x}}{(x-1)*x}}+\alpha_1^{2}+{\beta}_{1}^{2}$$

$$\ce{FeCO3 +2H2O ->[H2O] Fe(OH)2 + H2O + CO2}$$

![lagrida_latex_editor (5)](https://user-images.githubusercontent.com/114979532/200492462-bcfb893d-0efa-4ab4-806a-7f27d32cf88e.png)

![lagrida_latex_editor (4)](https://user-images.githubusercontent.com/114979532/200492475-873f9883-63ad-417a-8dff-8df5a8e31709.png)

![lagrida_latex_editor (7)](https://user-images.githubusercontent.com/114979532/200492668-06b2fd12-0568-442e-99fc-0d2ece7654e1.png)

файл test chemystry.py - викторина
