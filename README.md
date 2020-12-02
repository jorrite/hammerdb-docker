[![Software License](https://goo.gl/FU2Kw1)](LICENSE)

# 🐋 Docker for HammerDB

[HammerDB](https://github.com/TPC-Council/HammerDB) is a Database Load Testing and Benchmarking Tool.

Configured and working clients for MS SQL Server, PotsgreSQL, MySQL and Redis.

```
docker run -it jorrite/hammerdb ./hammerdbcli

hammerdb>librarycheck
tdbc::odbc for MSSQLServer
mysqltcl for MySQL
Pgtcl for PostgreSQL
redis for Redis
```

## Usage

```bash
# show help
docker run jorrite/hammerdb

# access cli
docker run -it jorrite/hammerdb ./hammerdbcli
```
