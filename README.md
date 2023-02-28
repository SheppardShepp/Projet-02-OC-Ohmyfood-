<h1 align="center">Projet-02-OC-Site_Ohmyfood-</h1>

<div align="center"><img height="200" src="https://i31.servimg.com/u/f31/13/52/99/79/bandea12.png"></div>

## 📝 Sommaires

- [Présentation du projet](#présentation)
- [Aperçu du projet](#projet)
- [Spécification du projet](#specification)

## 💭 Petit mot de présentation <a name = "présentation"></a>

Dans le cadre de la formation, l'étape suivante à l'utilisation du langage HTML et CSS fut d'apprendre les animations en CSS et l'emploi du préposseur Sass.

---

## :movie_camera: Scénario du projet

Je vien d’être recruté chez Ohmyfood, en tant que développeur junior.

Ohmyfood est une jeune startup qui voudrait s'imposer sur le marché de la restauration.
L'objectif est de développer un site 100% mobile qui répertorie les menus de restaurants gastronomiques. En plus des systèmes classiques de réservation, les clients pourront composer le menu de leur repas pour que les plats soient prêts à leur arrivée.

---

### Langages utilisés

- <img height="30" src="https://i31.servimg.com/u/f31/13/52/99/79/logo_h11.png"> HTML/CSS
- <img height="30" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/96/Sass_Logo_Color.svg/2560px-Sass_Logo_Color.svg.png"> Sass

---

## ⛏️ Aperçu du projet <a name = "projet"></a>

#### [Ohmyfood](https://sheppardshepp.github.io/Projet-02-OC-Ohmyfood-/) <a name = "ohmyfood"></a> : site 100% mobile qui répertorie les menus de restaurants gastronomiques

Objectif : Dynamisez une page web avec des animations CSS.

Utilisation : <img height="30" src="https://i31.servimg.com/u/f31/13/52/99/79/logo_h11.png"> <img height="30" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/96/Sass_Logo_Color.svg/2560px-Sass_Logo_Color.svg.png">

Aperçu :

<div align="center"><img height="300" src="https://i31.servimg.com/u/f31/13/52/99/79/ohmyfo15.png"> <img height="300" src="https://i31.servimg.com/u/f31/13/52/99/79/ohmyfo14.png"> <img height="300" src="https://i.servimg.com/u/f31/13/52/99/79/ohmyfo13.png"> <img height="300" src="https://i.servimg.com/u/f31/13/52/99/79/ohmyfo11.png"></div>

---

## :gear: Les Spécification du projets <a name = "specification"></a>

- Spécifications fonctionnelles :

  - Page d’accueil (x1)
    - Affichage de la localisation des restaurants. À terme il sera possible de choisir sa localisation pour trouver des restaurants proches d’un certain lieu.
    - Une section contenant les 4 menus sous forme cartes. Au clic sur la carte, l’utilisateur est redirigé vers la page du menu.
    - Quand l’application aura plus de menus, un “loading spinner” sera nécessaire. Sur cette maquette, il faut un aperçu. Il devra apparaître pendant 1 à 3 secondes à l'arrivé sur la page d'accueil, couvrir l'intégralité de l'écran, et utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini, le choix est libre tant que cela reste cohérente avec la charte graphique du site.
  - Pages de menu (x4)
    - 4 pages contenant chacune le menu d’un restaurant.
    - À l’arrivée sur la page, les plats doivent apparaître progressivement avec un léger décalage dans le temps. Ils peuvent soit apparaître un par un, soit par groupe “Entrée”, “Plat” et “Dessert”. L'animation est libre de choix.
    - Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec des points de suspension. Un exemple de l’effet attendu est fourni.
  - Footer
    - Le footer est identique sur toutes les pages.
    - Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.
  - Header
    - Le header est présent sur toutes les pages.
    - Sur la page d’accueil, il contient le logo du site.
    - Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil
  - Boutons
    - Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir. L’ombre portée devra également être plus visible.
    - À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un bouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il devra se remplir progressivement. Pour cette première version, l’effet peut être apparaître au survol sur desktop au lieu du clic.

- Spécifications techniques :

  - Le développement devra se faire en CSS, sans JavaScript.
  - Aucun framework ne devra être utilisé, en revanche l’utilisation de SASS est possible.
  - Aucun code CSS ne devra être appliqué via un attribut style dans une balise HTML.
  - Tout le code doit être versionné sur GitHub et le site devra être accessible sur Github Pages une fois terminé.
  - Le site sera développé en utilisant l’approche mobile-first. Sur tablette et desktop, le site devra s’adapter, mais ces supports n’étant pas prioritaires, leur mise en page est libre.
  - L’ensemble du site devra être responsive sur mobile, tablette et desktop.
  - Les pages devront passer la validation W3C en HTML et CSS sans erreur.
  - Le site doit être parfaitement compatible avec les dernières versions desktop de Chrome et Firefox.
  - Les effets accessibles au clic ou au survol devront utiliser les animations ou transitions CSS, pas de JavaScript ni de librairie.
