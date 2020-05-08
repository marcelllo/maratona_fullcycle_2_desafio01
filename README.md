# Repositório do Desafio 01 da Maratona DevFullCycle 2.0

https://github.com/codeedu/maratona2-desafios


# Desafio 01 

O primeiro passo para que você consiga acompanhar muito bem a Maratona é ter o seu ambiente de desenvolvimento pronto para conseguir simular tudo que te apresentaremos nos próximos vídeos. Nesse ponto o que você deve fazer como desafio será:

1. Instalar o Node.js em seu computador Criar um webserver que escuta na porta 3000 Ao acessar o webserver, a seguinte mesagem deverá aparecer: "Maratona Full Cycle 2.0"
2. Instalar o Docker em seu computador
3. Gerar uma imagem Docker dessa aplicação a partir da imagem node:14.1-alpine.
4. Publicar a imagem no Dockerhub
5. Quando executarmos: docker run -p 3000:3000 seu-login-docker/nome-da-sua-imagem deveremos ver a mensagem na porta 3000 de nosso browser
6. Postar nos comentários do vídeo a URL da sua imagem para que possamos executar

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