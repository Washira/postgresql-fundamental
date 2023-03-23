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

