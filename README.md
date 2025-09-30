# Cahier des charges – Projet “Évaluation ludique des professeurs”

## 1. Contexte du projet

Le projet consiste à créer une application web permettant aux étudiants d’évaluer leurs professeurs de manière ludique et humoristique. L’application proposera des pages publiques et privées, des critères de notation spécifiques et un espace d’administration pour gérer le contenu et les utilisateurs.

## 2. Objectifs

* Permettre aux étudiants de consulter et d’évaluer les professeurs.
* Créer des leaderboards par catégorie pour valoriser les professeurs selon des critères humoristiques.
* Fournir un espace d’administration pour gérer les professeurs, les votes et éventuellement les messages.
* Garantir la sécurité et la confidentialité des utilisateurs et des votes.


## 3. Fonctionnalités

### 3.1 Pages publiques

1. **Page de connexion**

   * Formulaire d’identification (email/mot de passe).
   * Option “Mot de passe oublié”.
   * Redirection vers l’accueil après connexion.

2. **Page d’accueil**

   * Présentation générale du projet.
   * Accès aux pages privées après authentification.
   * Liste des fonctionnalités disponibles.

### 3.2 Pages privées (accessibles uniquement après connexion)

1. **Liste des professeurs**

   * Affichage des professeurs avec nom, matière.
   * Option pour accéder à la page individuelle du professeur.

2. **Leaderboards avec catégories**

   * Classements par critères de notation (ex. Art de la digression, Taux de survie sans café, etc.).
   * Affichage du top 3 ou top 5 des professeurs par catégorie.

3. **Pages individuelles des professeurs**

   * Informations générales (nom, matière, description courte).
   * Affichage des notes par catégorie et des votes.
   * Option pour voter selon les différents critères.

4. **Page de l’admin**

   * Gestion des professeurs : ajout, suppression, modification.
   * Gestion des votes et éventuellement des messages.
   * Suivi et statistiques des votes.
   * Option “suppression messages” si le temps le permet.

## 4. Critères de notation pour les professeurs

1. **Art de la digression** : Mesure le niveau de digression lors du cours.
2. **Taux de survie sans café** : Capacité du prof à tenir sans son café.
3. **Marathonien** : Fait les 10’000 pas dans la classe.
4. **Cuisinier royal** : Qualité de la nourriture offerte aux élèves.
5. **Phrase culte** : Une phrase emblématique du professeur.
6. **Freestyler ou maître du PPT** : Cours improvisé ou basé sur le PPT.
7. **Style vestimentaire** : Classique ou légende de la mode.

## 5. Contraintes techniques

* Langage : PHP
* Base de données : MySQL ou MariaDB.
* Gestion des droits : utilisateurs, admin.
