# JO-PARIS2024-APP

**JO-PARIS2024-APP** est une application de réservation de billets pour les Jeux Olympiques de Paris 2024. Ce projet est basé sur une architecture microservices et inclut les composants suivants :

## Architecture

- **Microservices** :
    - `auth-service` : Gestion de l'authentification et des utilisateurs.
    - `discovery-service` : Service de découverte (Eureka).
    - `gateway` : API Gateway pour la gestion centralisée des requêtes.
    - `event-service` : Gestion des événements sportifs.
    - `payment-service` : Gestion des paiements.
    - `notification-service` : Envoi de notifications aux utilisateurs.
    - `key-generator-service` : Génération de clés pour des identifiants uniques.

- **Frontend** :
    - Angular 17.3 avec Bootstrap 5.3.3 pour l'interface utilisateur.

- **Déploiement** :
    - Conteneurisation avec **Docker**.
    - Orchestration via **Kubernetes**.

## Prérequis

- **Java 17** ou supérieur
- **PostgreSQL**
- **Docker** et **Kubernetes**
- **Node.js** (pour le frontend)

## Installation

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/FanmoeFabrice/JO-PARIS2024-APP.git
   cd JO-PARIS2024-APP
