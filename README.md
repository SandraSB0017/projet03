1 - Start docker compose stack

```bash
docker compose up -d
```

2 - install symfony project

```bash
docker-compose exec www bash
composer create-project symfony/skeleton:"7.0.*" project

```
3 create Controller :

```bash
docker-compose exec www/project bash
bin/console make:controller HomeController
```


