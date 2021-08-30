# Ohmyfood!

Projet n°3 du parcours diplomant "Développeur Web" chez OpenClassrooms, dont L'objectif est d'intégrer et de dynamiser la maquette d'un site proposant la composition ainsi que la réservation de menus pour une selection de restaurants gastronomiques.

![Maquette](https://user.oc-static.com/upload/2020/08/24/15982605908418_Maquettes%20Ohmyfood.jpg)

### Ressources fournies

- Maquette mobile
- Exemples des animations
- Police logo et titres: Shrikhand
- Police texte: Roboto
- Les couleurs sont : violet #9356DC, rose #FF79DA et vert #99E2D0

### Contraintes techniques

- Utilisation d'un pré-compilateur CSS (Sass)
- Pas de JavaScript ni de librairie
- Mobile-first, adaptation du design aux tablettes et desktop
- L’ensemble du site devra être responsive sur mobile, tablette et desktop.
- Les pages devront passer la validation W3C en HTML et CSS sans erreur.
- Le site doit être parfaitement compatible avec les dernières versions desktop de Chrome et Firefox.

### Fonctionnalités

#### Boutons

- Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir. L’ombre portée devra également être plus visible.
- Un bouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il devra se remplir progressivement. Pour cette première version, l’effet peut être apparaître au survol.

#### Page d’accueil

- Mise en place d'un “loading spinner”. Il devra apparaître pendant 1 à 3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini, toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte graphique du site.

#### Pages de menu

- À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe “Entrée”, “Plat” et “Dessert”.
- Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec des points de suspension.

### Outils utilisés

- Edition du code depuis Visual Studio Code
- Compilation du code SCSS vers CSS via Node.js Sass
- Rendu temps réel grace au plugin Live Server
