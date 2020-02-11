# jenkins_docker

- Criação de um volume local para persistência de dados do Jenkins:

docker volume create jenkins_home

- Verificando o volume criado:

docker volume ls |grep jenkins_home

- Verificando detalhes:

docker volume inspect jenkins_home

- Baixar a versão LTS do Jenkins:

docker pull jenkins/jenkins:lts

- Subir o container:

docker-compose up

- Acessando o Jenkins no endereço:

http://127.0.0.1:8080

![Screenshot](screenshot.png)
