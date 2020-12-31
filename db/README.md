# mysql for local environment
Simple notes for setting mysql for local environment.
This can be useful for mysql, mariadb and postgres.
## Dump schema
---
Dump schema from a server. Dump files will be used for initializing local DB
### mysql
use `mysql-client` 
```bash
# mysql 8
brew install mysql-client@8
# mysql 5
brew install mysql-client@5
```

after dump schema from the server, locate the dump file under `scripts` directory for initailizing local DB.
mysql daemon will execute schema files(`.sql`) alphabet order.



