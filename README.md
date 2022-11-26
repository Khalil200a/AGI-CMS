# 🚀 Rapport Strapi

## Introduction

Strapi est un CMS headless qui est été utiliser dans ce projet pour faciliter la manipulation des données statiques.</br>
Le but de ce rapport est de vous aider a comprendre tout les étapes a suivre.


## Installation

La command pour créer un projet Strapi est : 
```
yarn create strapi-app AGI-CMS --quickstart
```
Cela crée un `AGI-CMS` dossier, et ceci est notre CMS Strapi. Dans ce dossier Strapi installera les dépendances nécessaires pour le projet.

### 🎬 demo

https://user-images.githubusercontent.com/68712435/203788106-9d5a14d3-954d-4eba-9e29-9f8ef06b398a.mp4

## ⚙️ Configuration

0 - L'étape initiale sera de passer vers le dossier `AGI-CMS` 

```
cd AGI-CMS
```

1 - Après on peut démarrer le serveur en utilisant la commande  :

```
yarn strapi develop
```

Le serveur Strapi sera démarré à `localhost:1337` et l'URL [http://localhost:1337/admin](http://localhost:1337/admin) sera automatiquement chargé dans notre navigateur par Strapi;

2 - Remplissez vos coordonnées et cliquez sur le bouton `LET'S START`.  Strapi créera votre compte et l'interface utilisateur d'administration sera chargée. 

### 🎬 demo

https://user-images.githubusercontent.com/68712435/204103503-39166746-4240-49c0-8397-d5afc9ed4c50.mp4

## Construire le single type de la page statique

Notre serveur Strapi a démarré.  Maintenant, nous allons construire notre sigle type.
Notre modèle rassemblera a ceci :

```
Landing {
    believe,
    mission,
    vision
}
```

1 - Sur l'interface utilisateur d'administration. Cliquer sur `+ Create new single type`.  Un modal apparaîtra sur le modal contextuel, tapez "landing" dans la zone de saisie du nom d'affichage;

2 -  Remplir le nom avec `landing` et cliquer sur le `Continue` bouton, un modal apparaîtra. Ce sera pour sélectionner le champ pour notre model `landing`, les champs de notre modèle de landing seront un champ "Texte".  Choisissez donc le champ "Texte" sur la prochaine interface utilisateur qui affiche le type "believe" et cliquez sur `+ Add another area` pour ajouter "mission" et "vision".</br>
Au "vission", cliquez sur le champ `Finish` bouton.  Le modal disparaîtra et nous verrons le landin affiché avec les champs que nous avons ajoutés.  En haut à droite, cliquez sur "Enregistrer", cela conservera nos  sur Strapi. 

### 🎬 demo

https://user-images.githubusercontent.com/68712435/204110407-0a8d2079-147b-441f-a894-9765f0adaea8.mp4

## Ajouter les données de la page statique 

Après avoir créer le landing model, Maintenant on va le remplir.

1 - Aller au Content Manager;

2 - Remplir le formulaire

3 - Cliquer sur `enregistrer`;

4 - Cliquer sur `publier` pour faire vivre les données.

### 🎬 demo

https://user-images.githubusercontent.com/68712435/204111353-a507c9ca-ef17-49f8-9167-d64d744b6262.mp4

## Mettre le données public

Avant de tester nos terminaux, rendons-les accessibles au public.
Cliquez sur `Paramètres` dans la barre latérale, puis sur la page qui se charge, allez dans la section `PLUGIN UTILISATEURS & PERMISSIONS` et cliquez sur `Rôles` une UI apparaît à droite.  Cliquez sur `Public`.</br>
Une interface utilisateur apparaît, faites défiler jusqu'à la section `Autorisations` et cliquez sur la case à cocher `trouver`.  Cette sélection permettra à tout utilisateur de voir les données de `landing`. 

### 🎬 demo

https://user-images.githubusercontent.com/68712435/204111618-413cc73c-c934-4aa4-92b1-074493e558ad.mp4

---

📚 Learn More :

 - 
