# Docker Commands

![docker](/images/docker.png)

### Listar imagens
```
docker images
```
```
docker image ls
```

### Adicionar imagem
```
docker pull <image>
```

### Remover imagem
```
docker image rm <image> --force
```

### Lista processos
```
docker ps
```

### Executar
```
docker run -d -p 80:80 <image>
```
```
docker run –mount type=bind,source=<source_path>,target=<path> <image>
```

### Listar portas
```
docker port <id>
```

### Remove
```
docker container rm 40c469519bd4  --force
```
```
docker container rm $(docker ps -aq) --force
```

### Build
```
docker build -t <seu-nome-de-usuario-do-docker-hub>/<app>:<versao> .
```

### Login
```
docker login -u <user>
```

### Push
```
docker push <seu-nome-de-usuario-do-docker-hub>/<app>:<versao>
```
