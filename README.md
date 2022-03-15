
# PROVA PRÁTICA PARA PROGRAMADOR PHP II

### Passo a passo
Clone Repositório
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