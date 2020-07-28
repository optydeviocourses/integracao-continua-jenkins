# UDEMY
# INTEGRAÇÃO CONTINUA COM TESTES UTILIZANDO O JENKINS 

## PREPARANDO O AMBIENTE

### Posrgres e Sonarqube

```
cd /Volumes/ROBERTO-CD1/Dev/udemy.com/
cd ci-cd/integracao-continua-jenkins/devops/
docker-compose up -d
```
### Jenkins

```
java -jar jenkins.war --httpPort=8000
```

### Tomcat

- Iniciar Tomcat
```
cd /Volumes/ROBERTO-CD1/Dev/udemy.com/
cd ci-cd/integracao-continua-jenkins/devops/apache-tomcat-9.0.36/bin   
./startup.sh
```
- Baixar o Tomcat
```
./shutdown.sh
```