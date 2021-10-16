# postgresql-commands

This repo contains usefull postgresql commands. 

### Installing Postgress.App
1. download postgress.app at https://postgresapp.com/downloads.html
2. open postgress.app -> click initialize
3. configure the $PATH -> sudo mkdir -p /etc/paths.d &&
echo /Applications/Postgres.app/Contents/Versions/latest/bin | sudo tee /etc/paths.d/postgresapp

## Commands

| Command | Description |
| ------- | ----------- |
| 'psql' | connect to postrgresql server |
| 'creatdb mydb' | creates db with name <mydb> |
| 'dropdb mydb' | deletes db |
| 'psql mydb' | activate db |

## 
| Command | Description |
| ------- | ----------- |
| 'CREATE DATABASE name' | create a database |
| '\password' | create password for access |
 
  
## Once db is activated 
| Command | Description |
| ------- | ----------- |
| '\h' | get help|
| '\q' | get out of psql|
| 'CREATE TABLE tablename (...);' | create table |
| 'DROP TABLE tablename;' | drope table |
| '\dt' | show all datatables |
| 'CREATE USER youruser WITH ENCRYPTED PASSWORD 'yourpass'; | creates user with password |
| GRANT ALL PRIVILEGES ON DATABASE yourdbname TO youruser; | grants all privilages to youruser |

