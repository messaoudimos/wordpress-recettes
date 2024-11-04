# WordPress Recettes

## Description
Ce projet est un site de recettes développé avec WordPress. Il utilise un thème enfant basé sur Divi et inclut un Custom Post Type (CPT) "Recettes" avec des champs personnalisés pour les ingrédients, le temps de cuisson, et les étapes. Le site présente une page d'accueil avec un carrousel et une ligne de trois recettes récentes, ainsi qu'une page de détail pour chaque recette.

## Installation

### Prérequis
- Un serveur local (WAMP, XAMPP, MAMP, etc.)
- WordPress installé
- Accès à phpMyAdmin pour gérer la base de données

### Étapes
1. Clonez ce dépôt dans le répertoire de votre serveur local :
   ```bash
   git clone https://github.com/messaoudimos/wordpress-recettes.git
2. Déplacez les fichiers dans le dossier de votre serveur local (C:\wamp64\www\wordpress-recettes).
3. Créez une base de données (par exemple, wordpress_recettes).
4. Importez le fichier SQL dans phpMyAdmin.
5. Configurez WordPress en connectant votre base de données.
6. Activez le thème enfant via l'administration WordPress.
7. Installez et activez les extensions suivantes :
8. Custom Post Type UI
9. Advanced Custom Fields (ACF)
10. Divi et Divi Supreme Pro


### Détails des Plugins/Librairies Utilisés

```markdown
## Plugins et Librairies Utilisés

- **Divi** : Utilisé pour la conception visuelle et la personnalisation des pages.
- **Divi Supreme Pro** : Ajoute des fonctionnalités avancées au thème Divi.
- **Custom Post Type UI** : Permet de créer et gérer le Custom Post Type "Recettes".
- **Advanced Custom Fields (ACF)** : Permet de créer des champs personnalisés pour chaque recette (image, ingrédients, temps de cuisson, étapes).

## Éléments Spécifiques au Projet

- **Thème Enfant Divi** : Permet de personnaliser le thème Divi sans affecter les mises à jour.
- **Custom Post Type "Recettes"** : Utilisé pour gérer les recettes distinctement des articles de blog classiques.
- **Mise en Page** :
  - **Page d'accueil** : Inclut un carrousel et une section avec trois recettes récentes alignées horizontalement.
  - **Page de détail de la recette** : Affiche le titre, l'image, les ingrédients, le temps de cuisson, et les étapes.

### Blocages

- **Affichage des champs personnalisés** : Une difficulté initiale a été rencontrée pour afficher correctement les champs personnalisés dans la page de détail des recettes. Cela a été résolu en utilisant Divi Theme Builder pour configurer les pages de détail.

### TODO - Améliorations Futures

1. **Filtrage des Recettes** :
   - Ajouter des filtres pour permettre aux utilisateurs de trier les recettes par catégorie, temps de cuisson, ou type de repas.
   
2. **Système de notation** :
   - Intégrer un système de notation pour que les utilisateurs puissent évaluer les recettes.

3. **Commentaires** :
   - Permettre aux utilisateurs de laisser des commentaires ou des notes sur chaque recette.

## Auteur
Mostapha MESSAOUDI

