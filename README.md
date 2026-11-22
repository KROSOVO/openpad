# 🖥️ OpenPad by KROSOVO

**Le VESC Dashboard, en mode CarPlay.**

OpenPad reprend le tableau de bord de VESC Dashboard — compteurs, carte GPS, modes — et l'installe dans une interface type iPad / CarPlay : écran d'accueil, dock, applications et réglages, dans une seule page HTML/CSS/JS installable (PWA).

🌐 [**Page du projet**](https://KROSOVO.github.io/openpad/) — présentation, toutes les versions et support.

💬 [**Discord**](https://discord.com/users/809470888101543977) — support, signalement de bugs et suggestions.

## 📱 L'application principale

### 🤖 Android — Application (PWA)

L'application installable se trouve dans le dossier [`app/`](app/) :

➡️ [**Ouvrir l'application OpenPad**](https://KROSOVO.github.io/openpad/app/)

Depuis Chrome : `⋮` → **Installer l'application** (fonctionne hors ligne grâce au cache).

### 🍎 iOS — Safari (et Bluefy pour le Bluetooth)

Sur iPhone / iPad, ouvrez l'application dans Safari puis **Partager** → **Sur l'écran d'accueil**. Pour la connexion Bluetooth au VESC, utilisez le navigateur [**Bluefy**](https://apps.apple.com/app/bluefy-web-ble-browser/id1492822055) (gratuit sur l'App Store) :

➡️ [**Ouvrir l'application dans Bluefy**](https://KROSOVO.github.io/openpad/app/)

## 🕹️ Dernière version web

**Version actuelle :** V1.11.0

➡️ [**Accéder à la dernière version d'OpenPad**](https://KROSOVO.github.io/openpad/Pre-Releases/V1.11.0.html)

Les versions antérieures sont conservées dans le dossier [`Pre-Releases/`](Pre-Releases/).

## 🧭 Version de base (sans CarPlay) : VESC Dash

OpenPad est la version **CarPlay** du projet. La version de base, sans dock ni applications, c'est **VESC Dash**.

➡️ [**Page du projet VESC Dash**](https://KROSOVO.github.io/vesc-dashboard/)

➡️ [**Dernière version — V0.76**](https://KROSOVO.github.io/vesc-dashboard/Pre-Releases/V0.76.html)

➡️ [**Dépôt GitHub VESC Dash**](https://github.com/KROSOVO/vesc-dashboard)

## ✨ Fonctionnalités

### 🏎️ Compteur VESC — identique au Dashboard

- Affichage de la vitesse instantanée.
- Pourcentage et tension de batterie.
- Puissance moteur et barre d'accélération.
- **7 styles de compteur** : Classique, VARG, Halo, Flux, Race, Moto, Analog.
- Modes de conduite Eco / Sport / Race.
- Informations de conduite.

### 🗺️ Navigation GPS

- Carte interactive OpenStreetMap.
- Localisation GPS en temps réel.
- Recherche de destination et itinéraire.
- **Bouton de recentrage** de la position.

### 🖥️ Interface iPad / CarPlay

- Écran d'accueil avec icônes et dock.
- Applications intégrées (voir ci-dessous).
- Transitions et plein écran.
- **Mode sombre** sur toutes les applications.

### 📲 Applications

| Application | Contenu |
| ----------- | ------- |
| Téléphone   | Clavier, récents et contacts |
| Messages    | Conversations et chat |
| Musique     | Lecteur local, playlists et volume |
| À l'écoute  | Mix et stations |
| Plans       | Carte, itinéraire et recentrage |
| Météo       | Prévisions |
| Calendrier  | Mois et événements |
| Compteur    | Compteurs VESC et modes |
| Bilan de ride | Trajets et statistiques |
| Réglages    | Thème, fond d'écran, batterie |

## 🔧 Configuration matérielle

| Composant        | Configuration                    |
| ---------------- | -------------------------------- |
| Contrôleur       | Compatible VESC avec module BLE  |
| Firmware         | VESC                             |
| Communication    | Bluetooth                        |
| Module Bluetooth | Flipsky V6                       |

## 🖥️ Interface

Un pad accessible depuis un navigateur Android ou iOS (voir [Bluefy](https://apps.apple.com/app/bluefy-web-ble-browser/id1492822055) pour le Bluetooth sur iOS).

L'affichage est optimisé pour :

- Une utilisation en mode paysage.
- Un affichage plein écran.
- Un écran tactile.
- Une lecture rapide des informations pendant la conduite.

## 🧰 Technologies utilisées

- HTML5
- CSS3
- JavaScript
- Communication VESC
- GPS
- Cartographie avec OpenStreetMap
- Bluetooth
- PWA (manifest + service worker)

## 📊 État du développement

Le projet est actuellement en développement.

| Fonctionnalité           | État            |
| ------------------------ | --------------- |
| Interface compteur       | En développement |
| Interface iPad / CarPlay | En développement |
| Carte GPS                | En développement |
| Suivi GPS                | Terminé         |
| Bilan de ride            | Terminé         |
| Applications intégrées   | En développement |
| Gestion des modes VESC   | En développement |
| Optimisation Android     | En développement |

## 🎯 Objectif du projet

Proposer le tableau de bord VESC dans une interface familière, proche d'un iPad ou de CarPlay : toutes les informations de conduite et les applications du quotidien au même endroit, sans quitter le plein écran.

OpenPad partage sa base avec [VESC Dashboard](https://github.com/KROSOVO/vesc-dashboard) : les compteurs sont les mêmes. OpenPad ajoute l'interface autour.

## ⚠️ Avertissement

Ce projet est indépendant et n'est pas officiellement affilié à VESC ou Stark Future.

L'utilisation des fonctionnalités de modification des paramètres moteur doit être réalisée avec précaution. Une mauvaise configuration du contrôleur peut entraîner des dommages matériels ou des risques lors de la conduite.

## 📄 Licence

Projet personnel en cours de développement.
