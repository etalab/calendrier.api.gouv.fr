![Licences](https://img.shields.io/badge/Licences-MIT%2C%20Licence%20Ouverte-orange)
![CRON: build and deploy](https://github.com/etalab/calendrier.api.gouv.fr/workflows/CRON:%20build%20and%20deploy/badge.svg)

# calendrier.api.gouv.fr
Ce dépôt contient les données et API exposées sur le sous-domaine [calendrier.api.gouv.fr](https://calendrier.api.gouv.fr).

Pour le moment, seuls les jours fériés français sont mis à disposition. À l'avenir, d'autres événements notables pourraient être ajoutés.

## Jours fériés
Une API JSON des jours fériés en France est mise à disposition.

Cette API utilise l'[export des données](https://github.com/etalab/jours-feries-france-data). Rendez-vous sur [data.gouv.fr](https://www.data.gouv.fr/fr/datasets/jours-feries-en-france/) si vous souhaitez simplement un export des données.

La documentation est [accessible en ligne](https://calendrier.api.gouv.fr/jours-feries/). Un [fichier OpenAPI](openapi.yml) est mis à disposition.

## Licences
- Code sous licence MIT
- Données sous [Licence Ouverte](https://www.etalab.gouv.fr/licence-ouverte-open-licence)
