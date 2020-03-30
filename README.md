## Ansible Icinga DB

Variables:

Defaults:
```
icingadb_db_name: icingadb
icingadb_redis_host: 127.0.0.1
icingadb_redis_port: 6380
icingadb_mysql_host: 127.0.0.1
icingadb_mysql_port: 3306
icingadb_mysql_database: icingadb
icingadb_mysql_user: icingadb
icingadb_mysql_password: icingadb
icingadb_mysql_max_open_conns: 50
icingadb_logging_level: info
icingadb_redis_config_dir: /etc/icinga-redis
icingadb_redis_user: icinga-redis
icingadb_redis_group: icinga-redis
icingadb_user: icingadb
icingadb_group: icingadb
icingadb_config_dir: /etc/icingadb
```

OS Specific Vars:
```
icingadb_db_schema: /usr/share/icingadb/schema/mysql/mysql.schema.sql
```
