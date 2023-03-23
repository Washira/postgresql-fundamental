# คำสั่งเบื้องต้น ใน PostgreSQL

## Initialization

Enter into the terminal to log in if you aren't already

```
psql --username=<USERNAME> --dbname=<DB_NAME>
```

Into database name, type this for see list of all database.

### Check list of databases

```
\l
```

Result seems like this

```
                                    List of databases
+-----------------+--------------+----------+---------+---------+-----------------------+
|      Name       |    Owner     | Encoding | Collate |  Ctype  |   Access privileges   |
+-----------------+--------------+----------+---------+---------+-----------------------+
| first_database  | freecodecamp | UTF8     | C.UTF-8 | C.UTF-8 |                       |
| postgres        | postgres     | UTF8     | C.UTF-8 | C.UTF-8 |                       |
| second_database | freecodecamp | UTF8     | C.UTF-8 | C.UTF-8 |                       |
| template0       | postgres     | UTF8     | C.UTF-8 | C.UTF-8 | =c/postgres          +|
|                 |              |          |         |         | postgres=CTc/postgres |
| template1       | postgres     | UTF8     | C.UTF-8 | C.UTF-8 | =c/postgres          +|
|                 |              |          |         |         | postgres=CTc/postgres |
+-----------------+--------------+----------+---------+---------+-----------------------+
(5 rows)
```

## Create Database

```
CREATE DATABASE database_name;
```

Do not forget `semi-colon (;)` if using SQL keyword.

## Connect Other Database

```
\c other_database_name
```

## Create Table in The Database

```
CREATE TABLE table_name();
```

### Check Tables listed in The Database

```
\d
```

