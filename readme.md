# Exercice 5 : Le réseau social


## Objectif

Modéliser un système complexe avec diverses relations pour un réseau social thématique.

## Contexte

Vous êtes chargé(e) de concevoir la base de données pour un réseau social spécialisé autour d'une thématique de votre choix (jeux vidéo, cuisine, sports, musique, littérature, cinéma, animaux, voyage, art, etc.). Cette plateforme permettra aux passionnés de partager leurs expériences, de se connecter et d'interagir autour de leur centre d'intérêt commun.

## Consigne principale

Créez un modèle de données complet pour ce réseau social thématique en incluant au minimum :

- Des utilisateurs (membres)
- Des publications (posts)
- Des commentaires sur les publications
- Des groupes/communautés auxquels les utilisateurs peuvent appartenir
- Des relations d'amitié/connexion entre utilisateurs (relation réflexive)
- N'hésitez pas à en ajouter si nécessaire


## Travail demandé

1. **Choix de thématique** : Définissez clairement la thématique de votre réseau social et ses spécificités
2. **Définition des règles métier** : Établissez les règles de fonctionnement spécifiques à votre réseau social, notamment :
    - Les conditions d'inscription et de participation
    - Les droits et restrictions des différents types d'utilisateurs
    - Les règles de publication et d'interaction
    - Les mécanismes de modération et de gestion de contenu
    - Les fonctionnalités spécifiques liées à votre thématique
3. **Préparation** : Listez toutes les entités nécessaires et leurs attributs
4. **Dictionnaire de données** : Créez un dictionnaire de données détaillé comprenant pour chaque attribut

5. **Conception** : Créez un Modèle Conceptuel des Données (MCD) illustrant les entités et leurs relations
6. **Implémentation** : Transformez le MCD en Modèle Logique des Données (MLD) avec les clés primaires et étrangères
7. Créer le diagramme en DBML associé et générer le SQL
8. **Documentation** : Justifiez vos choix de conception, notamment pour les relations complexes

## Règles métier de base à respecter et à compléter

1. **Utilisateurs**
    - Chaque utilisateur doit avoir un profil avec des informations de base et spécifiques à la thématique choisie
    - Les utilisateurs doivent pouvoir définir un statut ou niveau d'expertise dans le domaine
    - Les utilisateurs doivent pouvoir exprimer leurs préférences liées à la thématique
2. **Publications**
    - Les publications peuvent contenir différents types de contenus
    - Les publications doivent pouvoir être catégorisées selon la thématique choisie
    - Un système de visibilité des publications doit être prévu

3. **Commentaires**
    - Un système de réponses aux commentaires doit être possible
    - Les interactions avec les commentaires doivent être prévues (likes, etc.)
4. **Groupes/Communautés**
    - Différents niveaux d'accès et de confidentialité doivent être prévus
    - Une hiérarchie de rôles au sein des groupes doit être définie
    - Les groupes doivent pouvoir organiser des activités spécifiques à la thématique
5. **Relations entre utilisateurs**
    - Différents types de connexions entre utilisateurs doivent être possibles
    - Un mécanisme de demande/acceptation doit être prévu
6. **Fonctionnalités supplémentaires**
    - Ajoutez au moins deux fonctionnalités spécifiques à votre thématique

> Note : Les entités suggérées sont un minimum. Vous êtes encouragé(e) à enrichir votre modèle avec d'autres entités pertinentes pour le contexte que vous avez choisi.
>## Livrables attendus

1. Description de la thématique choisie et des règles métier spécifiques
2. Dictionnaire de données complet
3. Liste détaillée des entités avec leurs attributs
4. Schéma du MCD (avec les cardinalités)
5. Schéma du MLD avec les clés
6. Documentation expliquant vos choix de conception
