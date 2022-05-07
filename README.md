# Ohmyfood
Projet 3 de la formation Développeur Web OpenClassrooms. Objectifs :

* développer un site 100% mobile qui répertorie les menus de restaurants gastronomiques
* Mettre en place son environnement Front-End
* Assurer la cohérence graphique d'un site web
* Mettre en place une structure de navigation pour un site web
* Mettre en œuvre des effets CSS graphiques avancés
* Utiliser un système de gestion de versions pour le suivi du projet et son hébergement

Brief créatif : https://s3.eu-west-1.amazonaws.com/course.oc-static.com/projects/Front-End+V2/P3+CSS+animations/DW+P3+-+Brief+creatif+-+Ohmyfood!.pdf

* Cible :

  Classes moyennes et supérieures, connectées et souvent pressées, souhaitant déguster des produits de qualité.

* Identité graphique :

  Polices : Logo et titres: Shrikhand ; Texte: Roboto

Couleurs :

![Capture d’écran 2022-05-07 à 12 04 12](https://user-images.githubusercontent.com/102370261/167249595-af3afb8f-552a-459d-bd3a-c7a9890b980f.png)

* Objectifs :

  Phase 1 : Développer un site proposant le menu de 4 grands restaurants parisiens.

  Phase 2 : Permettre la réservation en ligne et la composition de menus.

* Technologies :

  Le développement devra se faire en CSS, sans JavaScript.

  Aucun framework ne devra être utilisé, en revanche l’utilisation de SASS serait un
plus.

  Aucun code CSS ne devra être appliqué via un attribut style dans une balise HTML.

  Tout le code doit être versionné sur GitHub et le site devra être accessible sur Github Pages une fois terminé.

* Compatibilité :

  L’ensemble du site devra être responsive sur mobile, tablette et desktop.

  Les pages devront passer la validation W3C en HTML et CSS sans erreur.

  Le site doit être parfaitement compatible avec les dernières versions desktop de
Chrome et Firefox.

* Contenu des pages :

  -Page d’accueil (x1) :

    Affichage de la localisation des restaurants. À terme il sera possible de choisir sa localisation pour trouver des restaurants proches d’un certain lieu.

    Une courte présentation de l’entreprise.

    Une section contenant les 4 menus sous forme cartes. Au clic sur la carte,
l’utilisateur est redirigé vers la page du menu.
Pages de menu (x4)

    4 pages contenant chacune le menu d’un restaurant. 
  
  -Footer

    Le footer est identique sur toutes les pages.

    Au clic sur “Contact”, un renvoi vers une adresse mail est effectué.
 
  -Header :

    Le header est présent sur toutes les pages.

    Sur la page d’accueil, il contient le logo du site.

    Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil
    
 * Effets graphiques et animations :
 
  Les effets accessibles au clic ou au survol sont visibles sur la maquette. Ils devront utiliser les animations ou transitions CSS, pas de JavaScript ni de librairie.
Boutons
    
    -Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir. L’ombre portée devra également être plus visible.
    
    -À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un bouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il devra se remplir progressivement. Pour cette première version, l’effet peut être apparaître au survol sur desktop au lieu du clic.
Page d’accueil
  
    -Quand l’application aura plus de menus, un “loading spinner” sera nécessaire. Sur cette maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à 3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini, toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte graphique du site.
Pages de menu
    
    -À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe “Entrée”, “Plat” et “Dessert”. Un exemple de l’effet attendu est fourni.
    
    -Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec des points de suspension. Un exemple de l’effet attendu est fourni.




