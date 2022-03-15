
# PROVA PRÁTICA PARA PROGRAMADOR PHP II

### Clone o Repositório
```sh
git clone https://github.com/dalcero/tray-homework-laradock.git
tray-homework-laradock
```

### Crie o Arquivo .env
```sh
cd tray-homework-laradock/
cp .env.example .env
```

### Subir Containers
```
docker-compose up -d nginx mysql phpmyadmin rabbitmq
```

### Crontab
```
docker-compose exec workspace bash
```

```
crontab -e
```

```
* * * * * cd /var/www/api && php artisan schedule:run >> /dev/null 2>&1
```