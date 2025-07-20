# Radiospark

L'application Radiospark se substitue temporairementaux logiciels métiers de gestion des radiopharmaceutiques (Vénus®, PharmaManager®, ...) lors de l'indisponibilité prolongée de ces derniers (Panne, Cyberattaque, ...).

L'application est, pour le moment, uniquement disponible en français.
Radiospark est un outil et ne saurai se substituer à l'expertise et au contrôle du Préparateur en pharmacie hospitalière et du Radiopharmacien.


## 🚀 Fonctionnalités

- Gestion d'une banque de radionucléides et de MRP
- Création de MRP (Activité et volume initiaux, Activité et volume actuel, N° de Lot et date d'expiration des trousses et générateurs, N° de préparation)
- Gestion des patients (Identité, Prescription, Poids)
- Gestion des générateurs (Activité à calibration, Date d'expiration, N° de Lot, ...)
- Dispensation de seringues (Interface complète avec calculs dynamiques, Système d'alerte et génération d'étiquettes nominatives)
- Historique de seringues et des MRP préparés avec export possible au format PDF (.pdf) ou Excel® (.xls)
- Options (Modification de la taille des étiquettes et de l'ordre des onglets)
- Calculatrice de décroissance (Calcul de l'activité à une date souhaitée ou calcul de la date pour l'activité souhaitée)

## 🛠️ Technologies utilisées

- Langage : Python
- Base de données : Locale avec Pickle

## 📦 Installation

- Téléchargement de l'exécutable : https://github.com/doud176/Radiospark/tags (Pour la version MacOS, télécharger la version RadiosparkMacOS.exe)
- Avant l'exécution de l'application, ajouter un logo de trèfle radioactif ***au format PNG et nommez-le "radioactif"*** à la racine de votre lecteur C: au chemin suivant : "C:\radioactif.png. Vous pourrez en trouver à l'adresse suivante : https://www.flaticon.com/fr/chercher?word=radioactif
- Exécuter le fichier Radiospark(MacOS).exe
- Patientez environ 10 sec à 2 minutes selon les performances de votre ordinateur
- Si utilisation d'un ordinateur personnel, télécharger et installer le pilote de votre imprimante d'étiquette (Identifier la marque et le modèle de votre imprimante et rechercher le pilote directement sur votre navigateur). Au besoin, rapprochez-vous de votre DSI.
- À vous de jouer !

## 📁 Structure technique

- Architecture des fichiers : Le programme échange uniquement avec la base de données nommée *Data.pkl* qui est crée lors de la première exécution au même endroit où le programme se situe.
- Sécurité et gestion des données : Les données sont stockées et gérées sur l'ordinateur qui exécute le logiciel, en local. La sécurité des données incombe à l'utilisateur.

## 🆘 Support et maintenance

- Contact du développeur : Edouard Lefebvre (elefebvre.ph@gmail.com)
