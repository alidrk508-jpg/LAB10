# NavigationDrawerDemo

<img src="./demo/demo.gif" width="300">

Cette application Android est une démonstration de l'utilisation d'un **Navigation Drawer** (tiroir de navigation) avec le composant **Jetpack Navigation**.

## Fonctionnalités

- **Navigation Drawer** : Permet de basculer entre différentes sections de l'application.
- **Jetpack Navigation** : Utilisation de `NavController` et `NavHostFragment` pour gérer les transitions entre les fragments.
- **Fragments inclus** :
    - `BlankFragment` : Un fragment de base.
    - `BlankFragment2` : Un deuxième fragment de base.
    - `FragmentList` : Un `ListFragment` affichant une liste d'éléments (LAB1, LAB2, ..., LAB10).

## Structure du Projet

- `MainActivity.java` : L'activité principale qui configure la barre d'outils, le tiroir de navigation et le contrôleur de navigation.
- `mobile_navigation.xml` : Définit le graphe de navigation de l'application.
- `content_main.xml` : Contient le `FragmentContainerView` qui héberge les fragments.
- `FragmentList.java` : Gère l'affichage de la liste des travaux pratiques (LABs).

## Configuration Requise

- Android Studio
- SDK Android (niveau d'API minimum supporté à vérifier dans `build.gradle`)

## Installation

1. Cloner le dépôt.
2. Ouvrir le projet dans Android Studio.
3. Synchroniser le projet avec les fichiers Gradle.
4. Lancer l'application sur un émulateur ou un appareil physique.
