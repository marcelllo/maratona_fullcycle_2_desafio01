# Repositório do Desafio 01 da Maratona DevFullCycle 2.0

https://github.com/codeedu/maratona2-desafios

### Executando em localmente com Docker Compose

```
$ npm install
$ docker-compose up
```

### Buildando a imagem para o DockerHub
```
$ docker build -t marcellosantos/maratona-fullcycle-desafio01 .
$ docker push marcellosantos/maratona-fullcycle-desafio01
```

### Executando no server a partir da imagem do DockerHub
```
$ docker pull marcellosantos/maratona-fullcycle-desafio01
$ docker run -p 3000:3000 marcellosantos/maratona-fullcycle-desafio01

```