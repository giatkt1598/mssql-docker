# mssql-docker
## Set up & run images
```bash
docker-compose up
```
## Out terminal but no stop container
```bash
Ctrl + Z
```
**Username**: sa

**Password**: 1234@abcd

## Remove mssql-server
```bash
docker-compose down
```

## Inspect volume save data
```bash
docker volume ls
docker inspect mssql-docker_storage_data
```
