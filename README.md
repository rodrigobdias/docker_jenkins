# jenkins_docker

- Criar um volume local para persistência de dados do Jenkins
docker volume create jenkins_home

- Verificando o volume criado
docker volume ls |grep jenkins_home

- Verificando detalhes
docker volume inspect jenkins_home

- Para baixar a versão LTS
docker pull jenkins/jenkins:lts

- Subir 
docker-compose up

- Acesse o endereço:
http://127.0.0.1:8080

![Screenshot](screenshot.png)
