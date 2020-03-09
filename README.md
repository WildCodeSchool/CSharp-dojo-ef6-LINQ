# CSharp-dojo-ef6-LINQ

Durant ce dojo, aucune requête SQL ne doit être écrite. Tout doit être réalisé à l'aide de Entity Framework et de LINQ To Entities

## Création du schéma
Dans ce dojo tu devras créer le schéma de base de données suivant en utilisant l'approche Code-First de Entity Framework:
![https://github.com/WildCodeSchool/CSharp-dojo-ef6-LINQ/blob/master/dbdiagram.png]

## Le jeu de données de test

Un jeu de données de test doit être crée à l'aide d'Entity Framework. Il doit contenir:
* Trois structures
* Une adresse différent par structure
* Trois salles par structure
* Cinq employés par structure
* Entre 10 et 15 rendez-vous à venir par structure
* Entre 10 et 15 rendez-vous effectués par structure
* Un employé a au moins un rendez-vous passé et un rendez-vous futur

## Les fonctionnalités à fournir
Avec ce code, j'aimerais que tu crées une classe `StatisticsCalculator` qui réalise différentes opérations mathématiques pour obtenir des statistiques:

* Le nombre d'employés ayant eu ou allant avoir un rendez-vous
* Le nombre de rendez-vous à venir pour un employé
* Le nombre de rendez-vous par structure
* Le nombre de rendez-vous ayant déjà eu lieu dans une salle
