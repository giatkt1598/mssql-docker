# MSSQL 2019 in Docker
## Set up & run images
```bash
docker-compose up -d
```
**Username**: sa

**Password**: 1234@abcd
## Inspect volume save data
```bash
docker volume ls
docker inspect mssql-docker_storage_data
```

## Remove mssql-server container
```bash
docker-compose down
```
## Remove saved data volume
```bash
docker volume remove mssql-docker_storage_data
```


