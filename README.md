### Set up database using Docker

> Docker service should running.

Add database image in docker with phpmyadmin

```sh
docker-compose -f docker-compose.dev.yml up -d
```

Remove database image in docker with phpmyadmin

```sh
docker-compose -f docker-compose.dev.yml down
```

Running phpmyadmin

```sh
http://localhost:1002
```

Credential account

```sh
username : user
password : user
```
