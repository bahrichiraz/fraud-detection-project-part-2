# Analyse des fraudes 

## Description du Projet

Ce projet vise à analyser les fraudes dans les contrats d'assurances à travers un tableau de bord interactif. 
Il explore l'impact de divers facteurs tels que le Prime Moyen des affaires, Chiffre d’affaires frauduleux ... \
Le tableau de bord permet d'obtenir des insights en temps réel et facilite la prise de décisions stratégiques.

## Fonctionnalités principales
- **Analyse des ventes par compagnies, quantités des contrats frauduleux et types des fraudes.**
- **Calcul et suivi des KPIs :** Total des contrats frauduleux, chiffre d'affaire, et autres indicateurs clés de performance.
- **Filtres dynamiques** pour explorer les données selon les critères : ville, age, type de client, produit, types des fraudes, compagnies etc.
- **Visualisations interactives** avec Power BI pour une prise de décision rapide.

## Objectifs
- Analyser les contrats frauduleux par rapport aux contrats legales
- Les fraudes et le nombre des fraudes par ville, courtier, type de fraude, par date, gamme, état dossier, Prospect...

## Technologies utilisées
- **Power BI** pour la création de tableaux de bord interactifs.
- **DAX** pour les calculs avancés et KPIs.
- **Power Query** pour l'extraction et la transformation des données.
- **Postgresql** pour le prétraitement et l'analyse des données.

## Pages du Tableau de Bord
### Page 1: Page d’accueil : La première page du rapport est une page d’accueil qui présente desinformations générales des affaires totales et des affaires frauduleux \
\
![1](https://github.com/user-attachments/assets/d17e1869-2962-4439-b7fd-0e81fb3f7f3f) \
\
### Page 2 et 3: Ces deux tableaux décrits les KPIs des fraudes et des visuels de nombre des fraudes par ville, courtier, type de fraude, par date, gamme, état dossier, Prospect... \
\
![2](https://github.com/user-attachments/assets/03dd7fe5-54e5-4397-b16f-e51b80e4d8a5) \
![3](https://github.com/user-attachments/assets/051d3575-5d45-48e5-9e60-c34550915919) \
\
### Page 4 et 5: Ces deux tableaux décrits les KPIs des affaires et des visuels de nombre des affaires par ville, courtier, par date, gamme, état dossier, Prospect... \
\
![4](https://github.com/user-attachments/assets/64beb329-79bb-4627-95e7-08ac222b1864)
![5](https://github.com/user-attachments/assets/b73d110d-734e-4adb-95cd-bc580eecabef)
\
### Page 6: Ce tableau de bord comprend des segments de filtrage pour la date (mois et année), le nom de la gamme, et un filtre pour sélectionner l’organisme
\
![6](https://github.com/user-attachments/assets/feaf2fc4-5e42-4dc0-8a02-649c0d493f97)
### Page 7: Ce tableau de bord comprend des segments de filtrage pour la date (mois et année), le nom de la gamme, et un filtre pour sélectionner l’organisme et l’utilisateur. \
\
![7](https://github.com/user-attachments/assets/1d43c07c-38dd-41e0-814a-283f397bf4e7)

### Developpement de la plateforme : 
Cette application assure un accès fiable et sécurisé aux tableaux de bord, tout en offrant des fonctionnalités avancées telles qu’un système CRUD pour les comptes utilisateurs. De plus, elle intègre une analyse spécialisée pour la détection de fraudes dans les contrats PDF, renforçant ainsi la gestion proactive des risques et des données.
** Description existe dans la premiere partie de projet **
