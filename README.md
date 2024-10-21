# Sup de Vinci - Containers module project
*Tested with `rust v1.82.0` et `node 23.0.0`.*
## Development

### API
#### Basics
Utiliser `cargo run` pour lancer l'environnement de dev.
On peux également installer [cargo-watch](https://crates.io/crates/cargo-watch) pour surveiller les modifications de la source de votre projet et exécuter les commandes Cargo lorsqu'elles se produisent : `cargo-watch -x run`.

### Web
#### Basics
Utiliser `npm install` pour installer toutes les dépendances, et `npm run dev` pour lancer l'environement de dev.

## Production
### API
#### Basics
Exécuter `cargo build --release` pour build et compiler l'application. Cela créera un exécutable dans `/target/release/sdv-api`.

### Web
#### Basics
Exécuter `npm run build` pour lancer l'application, et executer `npm run start` pour lancer le Node.js server. 

## Application
## Prérequis
Installer `Docker` : [Lien du site de Docker pour installer Docker Desktop](https://www.docker.com/products/docker-desktop/) / Docker compose !

Installer `Git` : [Lien du site de Git pour l'installer](https://git-scm.com/) !

### Environnement standardisé
Exécuter `git clone https://github.com/Kyl35/sdv-m1do-containers-project.git` pour récupérer l'ensemble des fichiers.

Se placer dans le dossier cloné !

Exécuter `docker-compose up --build` pour lancer la construction de l'environnement.

Ouvrir `localhost:3000` dans un navigateur, pour se connecter au Front-End.

Ouvrir `localhost:80` dans un navigateur, pour se connecter à l'API.

