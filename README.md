# Projet Spring Boot avec JWT et Maven

Ce projet Spring Boot utilise JSON Web Tokens (JWT) pour l'authentification. Il nécessite une variable d'environnement `JWT_SECRET` pour fonctionner correctement, afin de signer et vérifier les JWT.

## Prérequis

- **Java 17+** doit être installé.
- **Maven 3.6+** doit être installé.

## Configuration de la variable d'environnement

Avant d'exécuter l'application, vous devez configurer une variable d'environnement nommée `JWT_SECRET` avec la clé secrète qui sera utilisée pour signer et vérifier les tokens JWT.

### Linux/MacOS

bash
export JWT_SECRET=your_secret_key_here 

### configuration sur vscode
launch.json
add 
"env":{
    "JWT_SECRET":your_secret_key
}

## Dependencies needed
It Works Only when you import spring security 

