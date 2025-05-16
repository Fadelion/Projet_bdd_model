# Projet_bdd_model

Ce projet est une application Ruby on Rails permettant de gérer des films via une base de données relationnelle. Il s'agit d'un exemple pédagogique pour illustrer la création, la manipulation et l'affichage de données dans un contexte web.

## Prérequis

- **Ruby** : version 3.0 ou supérieure recommandée
- **Rails** : version 7 ou supérieure
- **Bundler** : pour la gestion des gems
- **SQLite3** (par défaut, ou adapter la configuration pour un autre SGBD)

## Installation

1. Clonez le dépôt :
   ```bash
   git clone <url-du-repo>
   cd Projet_bdd_model
   ```

2. Installez les dépendances :
   ```bash
   bundle install
   ```

3. Créez et initialisez la base de données :
   ```bash
   rails db:create db:migrate db:seed
   ```

## Lancement de l'application

Démarrez le serveur Rails :
```bash
rails server
```
L'application sera accessible sur [http://localhost:3000](http://localhost:3000).

## Structure du projet

- `app/models` : modèles ActiveRecord (ex : `movie.rb`)
- `app/controllers` : contrôleurs Rails
- `app/views` : vues HTML/ERB
- `db/migrate` : migrations de la base de données
- `config` : configuration de l'application

## Tests

Pour exécuter la suite de tests :
```bash
rails test
```

## Déploiement

Pour déployer l'application, adaptez la configuration de la base de données et des variables d'environnement selon votre hébergeur (Heroku, Render, etc.).

## Fonctionnalités

- CRUD complet sur les films (`Movie`)
- Interface web simple et responsive
- Utilisation des conventions Rails

## Contribution

Les contributions sont les bienvenues ! Merci de forker le projet et de proposer une Pull Request.

## Auteurs
- [THIAM](https://github.com/thaliou)
- [ASSY](https://github.com/AssyaJalo)
- [SOUARE](https://github.com/bbkouty)
- [FANAR](https://github.com/fanarbandia)
- [MAIGA](https://github.com/Fadelion)

## Licence

Ce projet est sous licence MIT.
