# MySQL Docker Quickstart   

A simple repo to start up a quick MySQL server and some helpers for
development purposes.

# URLS

- Adminer - localhost:8081
- PHPMyadmin - localhost:8082

# Setup

- Host: mysql
- Username: root
- Password: password

# MySQL Entry Point Database Setup

You can setup your initial database by dumping it and adding the SQL dump file to the
entry point folder in the repo.

```bash
mysql-data/*.sql
```

## References
- https://hub.docker.com/_/mysql
- https://hub.docker.com/_/phpmyadmin
- https://hub.docker.com/_/adminer