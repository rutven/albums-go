# READ ME

## Start MySQL database in docker

```bash
docker run --name albums-db --restart on-failure -p 3306:3306 -e MYSQL_ROOT_PASSWORD=albums-pass -d mysql:latest
```
## Connect to MySQL database

```bash
mysql -h localhost -P 3306 --protocol=tcp -u root -p
```
