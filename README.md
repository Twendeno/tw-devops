# tw-devops
# Description

Ce projet sert de point central de contrôle pour l'ensemble des services déployés. <br>Il assume les rôles de reverse proxy ainsi que de répartiteur de charge, facilitant ainsi la gestion et l'acheminement des requêtes entre les différents services.

## Comment utiliser

### Prérequis

- [Docker](https://www.docker.com/) : pour creer et gérer des conteneurs
- [Docker Compose](https://docs.docker.com/compose/) : pour lancer plusieurs conteneurs en même temps
- [Git](https://git-scm.com/) : pour cloner le dépôt

### Utilisation rapide

```bash
$ git clone
$ cd tw-devops
$ npm i
$ docker-compose up -d
```

- Consulter l'api de l'application sur [https://ms-rx-trans.traefik.me/api-docs](https://ms-rx-trans.traefik.me/api-docs).
- Consulter le tableau de bord de Traefik sur [http://localhost:8080](http://localhost:8080).

