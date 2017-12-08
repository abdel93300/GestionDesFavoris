# GestionDesFavoris
Application de gestion des favoris

Le choix technique utilisé pour créer cette application, est d'utiliser un serveur Jetty,
avec une base de données H2.
Cette base contiendra 2 tables :
- table des catégories 
  - une catégorie se caractèrise par un identifiant et son Nom
- une table des favoris
  - un favori se caractérise par un Identifiant, Nom, une URL, une liste de catégorie, une date de création

- Utilisation de JPA, MAVEN, un générique DAO pour les création, modification, suppression, lecture
- Utilisation de HTML pour gérer des formulaires de création des catégories et favoris.

- La mise page dynamique se fait via les SERVLETS

- la page d'accueil <welcome-page> permet de gèrer : 
  - les catégories (liste, création, suppresion)
  - les favoris (liste, création, modification, suppression)

