# Comandos Docker

Listar containers ativos

```$ docker ps```

Listar todos os containers

```$ docker ps -a```

Rodar um container
```$ docker run <image_name>```

Exemplo:

```$ docker run hello-world```
```$ docker run ubuntu```

Rodar um container e interagir com ele

```$ docker run -it ubuntu bash```

Parar a execução de um container

```$ docker stop <container_id>```

Interagir com um container parado

```$ docker exec -iti <container_id> bash```

Listar imagens

```$ docker images```

Removar uma imagem

```$ docker rmi <image_id>```

# Dockerfile

Criar uma imagem a partir de um Dockerfile

```$ docker build -t satc-devops-site:1.0 .```

Rodar um container a partir de uma imagem criada

```$ docker run satc-devops-site:1.0```

Rodar um container e redirecionando portas

```$ docker run -p 80:80 satc-devops-site:1.0```

# Dockerhub

Fazer login no dockerhub

```$ docker login```

Enviar uma imagem local para o dockerhub

```$ docker push paegle/satc-devops-site:1.0```

# Docker compose

Buildar um arquivo docker-compose.yml

```$ docker push paegle/satc-devops-site:1.0```
