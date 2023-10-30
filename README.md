# Gestion des Étudiants, des Marques de Machines et des Machines

Ce projet de site web a été développé pour la gestion des étudiants, des marques de machines et des machines individuelles. Il offre une interface web permettant d'effectuer des opérations CRUD (Création, Lecture, Mise à jour et Suppression) pour les étudiants et les marques de machines. Les utilisateurs ont également la possibilité de filtrer les machines par marque ou référence. En outre, l'application propose des visualisations sous forme de graphiques à barres et de camemberts pour afficher la répartition des machines par marque.

## Objectif Principal

L'objectif central de ce projet est l'apprentissage de l'utilisation d'AJAX (Asynchronous JavaScript and XML) pour améliorer l'expérience utilisateur, en particulier dans le contexte des fonctionnalités de filtrage.

## Technologies Utilisées

- Java
- JSP (JavaServer Pages)
- Hibernate
- MySQL (Base de données)
- HTML
- CSS
- JavaScript
- jQuery
- AJAX
- GlassFish (Serveur d'application)

## Fonctionnalités Clés

- Opérations CRUD pour les étudiants.
- Opérations CRUD pour les marques de machines.
- Opérations CRUD pour les machines individuelles.
- Filtrage des machines par marque ou référence.
- Représentation graphique de la distribution des machines par marque (graphiques à barres et camemberts).

## Structure du Projet

Le projet est organisé en plusieurs packages et répertoires :

- ma.school.config : Contient le fichier de configuration hibernate.cfg.xml pour Hibernate.
- ma.school.util : Inclut la classe HibernateUtil pour la gestion de la SessionFactory Hibernate.
- ma.school.service : Contient les classes qui implémentent les opérations d'accès aux données (DAO).
- ma.school.dao : Définit l'interface IDao pour les opérations CRUD.
- ma.school.beans : Contient les classes d'entités pour les étudiants, les marques de machines et les machines.
- ma.school.controller : Servlets pour la gestion des requêtes web.

## Pages Web

- etudiantForm.jsp : Interface de gestion des étudiants.
- machineForm.jsp : Interface de gestion des machines.
- marqueForm.jsp : Interface de gestion des marques de machines.
- machineByMarqueForm.jsp : Filtrage des machines par marque.
- machineByReferenceForm.jsp : Filtrage des machines par référence.
- graphe.jsp : Page de visualisation graphique.
- menu.jsp, footer.jsp, header.jsp : Composants de page communs.

## Scripts JavaScript

- machineByMarque.js : JavaScript pour le filtrage des machines par marque.
- machineByReference.js : JavaScript pour le filtrage des machines par référence.

## CSS

- css.css : Feuille de style pour les pages web.

## Configuration Système Requise

- Java 8 ou version ultérieure
- Serveur MySQL
- Serveur d'application GlassFish

## Comment Exécuter le Projet

1. Clonez le projet sur votre machine locale.
2. Configurez le fichier hibernate.cfg.xml pour qu'il se connecte à votre base de données.
3. Exécutez le projet sur un serveur GlassFish.
4. Accédez à l'application en ouvrant le lien fourni dans votre navigateur web.

## Auteurs

Ce projet a été développé par [insérer les noms des auteurs ici].
