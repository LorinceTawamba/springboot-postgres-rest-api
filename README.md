# Springboot-postgres-rest-api 

Microservice Spring Boot avec Postgres, REST API.  

## Construit avec 

* [Java 17](https://www.java.com/fr/download/) - JDK 17
* [Spring initializr](https://start.spring.io/) - 2.7.4  
* [IntelliJ IDEA Utlimate](https://www.jetbrains.com/fr-fr/idea/) - Edition 2022.2.1 
* [Docker](https://www.docker.com/) - version 20.10.17 

## Versions

- **Dernière version stable :** 1.0.0
- **Dernière version :** 1.0.0
The list of versions : [Click to display](https://github.com/LorinceTawamba/springboot-postgres-rest-api/tags) 

## A propos du service 

**Microservice Spring Boot avec Postgres, REST API** 

## Deployment

**Créer le package (Jar files)**

```bash
  mvn clean install
```

Vous devrez le faire pour les deux applications. Une fois cette commande exécutée, vous verrez le fichier jar disponible dans le dossier cible. Les noms de fichiers seront :

- springboot-postgres-rest-api-1.0.0

**Create the docker image**

```bash
  docker build -t lorincetawamba/springboot-postgres-rest-api:1.0.0 -f Dockerfile .
```

**Lister toutes les images Docker sur la machine**

```bash
  docker images 
  ou 
  docker image ls
```

**Démarre une image Docker**

```bash
  docker run -d -p 8081:8081 -t lorincetawamba/springboot-postgres-rest-api:1.0.0
```

**Lister tous les conteneurs en cour d’execution sur la machine**

```bash
  docker container ls
``` 

**Connectez-vous avec votre identifiant Docker sur DockerHub**

```bash
  docker login -u lorincetawamba -p votre-mot-de-passe-ici
```

**Pousser l’image sur le DokerHub**

```bash
  docker image push lorincetawamba/springboot-postgres-rest-api:1.0.0
```

# Authors

* **SATIC SA / Lorince TAWAMBA** _alias_ [@lorince-tawamba](https://github.com/LorinceTawamba)

Read the list of [contributors](https://github.com/LorinceTawamba/springboot-postgres-rest-api/contributors) to see who helped with the project ! 

# License

Ce document est placé sous licence CC BY-NC-SA :  [Creative Commons
Attribution - Pas d'Utilisation Commerciale - Partage dans les Mêmes Conditions](https://creativecommons.org/licenses/by-nc-sa/4.0/)

![Logo](https://licensebuttons.net/l/by-nc-sa/3.0/88x31.png)

En savoir plus sur [les licences Creative Commons](https://creativecommons.org/licenses/?lang=fr-FR)...
