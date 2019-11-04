# Baza danych

- Skrypt do utworzenia bazy danych
https://github.com/sulmar/sakila/blob/master/sql-server-sakila-db/sql-server-sakila-schema.sql

- Skrypt z przykładami danych
https://github.com/sulmar/sakila/blob/master/sql-server-sakila-db/sql-server-sakila-insert-data.sql

- Uruchomienie bazy danych SQL Server w dockerze
~~~ bash
docker run -e "ACCEPT_EULA=Y" -e "SA_PASSWORD=YourStrong@Passw0rd" -p 1401:1433 --name sql1 -d microsoft/mssql-server-linux:2017-latest
~~~
