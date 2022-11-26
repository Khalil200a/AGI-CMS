# 🚀 Rapport Strapi

## Introduction

Strapi est un CMS headless qui est été utiliser dans ce projet pour faciliter la manipulation des données statiques.
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

Le serveur Strapi sera démarré à `localhost:1337` et l'URL [http://localhost:1337/admin](http://localhost:1337/admin) sera automatiquement chargé dans notre navigateur par Strapi. 

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

1 - Sur l'interface utilisateur d'administration. Cliquer sur `+ Create new single type`.  Un modal apparaîtra sur le modal contextuel, tapez "landing" dans la zone de saisie du nom d'affichage.

2 -  Remplir le nom avec `landing` et cliquer sur le `Continue` bouton, un modal apparaîtra. Ce sera pour sélectionner le champ pour notre model `landing`, les champs de notre modèle de landing seront un champ "Texte".  Choisissez donc le champ "Texte" sur la prochaine interface utilisateur qui affiche le type "believe" et cliquez sur `+ Add another area` pour ajouter "mission" et "vision".

### 🎬 demo

https://user-images.githubusercontent.com/68712435/204109107-ac97a0f9-7b5a-4767-93c4-e1611eff80ae.mp4

---

<sub>🤫 Psst! [Strapi is hiring](https://strapi.io/careers).</sub>
