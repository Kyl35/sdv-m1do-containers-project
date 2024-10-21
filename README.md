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
Executer `cargo build --release` pour build et compiler l'application. Cela créera un exécutable dans `/target/release/sdv-api`.

### Web
#### Basics
Executer `npm run build` pour lancer l'application, et executer `npm run start` pour lancer le Node.js server. 

