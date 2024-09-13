# Docker Compose Templates

A collection of `docker-compose` templates.

## Database servers

1. `postgres` (with `pgadmin`)
2. `mysql`
3. `mssql` (for Windows)
4. `azure-sql-edge` (for MacOSX Apple M1 chipset)
5. `mariadb`
6. `mongodb`
7. `redis`
8. `dynamodb-local`

## Environment files

Examples of `.env` files for the database servers.

### `mariadb`

```
MYSQL_ROOT_PASSWORD=my_root_password
MYSQL_DATABASE=entwurfhaus
MYSQL_USER=db_admin
MYSQL_PASSWORD=my_password
```

### `mysql`

```
MYSQL_ROOT_PASSWORD=my_root_password
MYSQL_DATABASE=entwurfhaus
MYSQL_USER=db_admin
MYSQL_PASSWORD=my_password
```

### `mongodb`

```
MONGO_INITDB_ROOT_USERNAME=db_admin
MONGO_INITDB_ROOT_PASSWORD=my_password
```
