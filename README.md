# jenkins_docker

**Criação de um volume local para persistência de dados do Jenkins:**

```sh
docker volume create jenkins_home
```

**Verificando o volume criado:**

```sh
docker volume ls | grep jenkins_home
```

**Verificando detalhes:**

```sh
docker volume inspect jenkins_home
```

**Baixar a versão LTS do Jenkins:**

```sh
docker pull jenkins/jenkins:lts
```

**Subir o container:**

```sh
docker-compose up
```

**Acessando o Jenkins no endereço:**

```sh
http://127.0.0.1:8080
```

![Screenshot](screenshot.png)
