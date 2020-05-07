# Repositório do Desafio 01 da Maratona DevFullCycle 2.0

https://github.com/codeedu/maratona2-desafios

### Executando em localmente com Docker Compose

```
$ npm install
$ docker-compose up
```

### Buildando a imagem para o DockerHub
```
$ docker-compose -f docker-compose.yml -f docker-compose.production.yml build
$ docker push marcellosantos/desafio1
```

### Executando no server a partir da imagem do DockerHub
```
$ docker run -p 3000:3000 marcellosantos/desafio1
```