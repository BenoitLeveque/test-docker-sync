start container :

```
docker-sync-stack start
```

Connect in ssh with:

```bash
docker exec -u www-data -it `docker ps | grep "php:7.1-fpm" | awk '{print $1}'`  /bin/bash
```
