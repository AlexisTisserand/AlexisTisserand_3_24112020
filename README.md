# ohmyfood
Troisième projet du parcours "Développeur web" chez OpenClassrooms. </br>
L'objectif est d'intégrer la maquette d'un site de réservation de menus de restaurants gastronomiques intitulé "Ohmyfood" puis de la dynamiser avec des animations CSS en utilisant le préprocesseur Sass.</br>

Vous trouverez le [brief complet ici](https://s3-eu-west-1.amazonaws.com/course.oc-static.com/projects/DW_P3/Brief%20cre%CC%81atif%20-%20Ohmyfood!.pdf).


## Enjeux du projet.
Phase 1. Développer un site proposant le menu (pour l'instant) de 4 restaurants gastronomiques parisiens.</br>
Phase 2. Permettre de choisir son menu et de réserver directement en ligne.

## Livrables
► [Repository GitHub](https://github.com/AlexisTisserand/AlexisTisserand_3_24112020)</br>
► [Lien Github Page](https://alexistisserand.github.io/AlexisTisserand_3_24112020/)

## Contenu des pages

**Page d'acceuil (x1)** 
- Affichage de la localisation des restaurants
- Présentation de l'entrprise
- Section contenant les 4 menus sous formes cartes. Au clic sur la carte l'utilisateur est redirigé vers la page du menu

**Page de menu (x4)**
4 pages contenant chacune le menu d'un restaurant

**Footer**
- Footer identique sur toutes les pages
- Au clic sur "Contact", un renvoi vers une adresse mail est effectué

**Header**
- Header présent sur toutes les pages
- Accueil : logo du site
- Menus : logo du site + bouton de retour vers la page d'acceuil

## Effets graphiques et animations ##

**Boutons** 
- Au survol : la couleur de fond des boutons princpaux devra légèrement s'éclaircir + l'ombre devra être plus visible
- À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un bouton "J’aime" en forme de coeur est présent sur la maquette. Au clic, il devra se remplir progressivement. Pour cette première version, l’effet peut être apparaître au survol au lieu du clic.

**Page d’accueil**
- Quand l’application aura plus de menus, un “loading spinner” sera nécessaire. Sur cette maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à 3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini, toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte graphique du site.

**Pages de menu**
- À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe “Entrée”, “Plat” et “Dessert”. Un exemple de l’effet attendu est fourni.
- Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser dela droite vers la gauche. Pour cette première version, l’effet peut apparaître au survolau lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec des points de suspension. Un exemple de l’effet attendu est fourni

### Technologies

**Autorisées** : HTML / CSS / Sass</br>
**Interdites** : Javascript / Frameworks CSS / Inline CSS

## Notes ##

**Polices :**
- Logo & titres : Shrikhand
- Texte : Roboto

**Couleurs :**
- Primaire : #9356DC
- Secondaire : #FF79DA
- Tertiaire : #99E2D0

**Contraintes :**
- Approche mobile-first : oui
- Maquette mobile : oui
- Maquette desktop et tablette : mise en page libre
- Validation W3C HTML : sans erreurs
- Validation W3C CSS : sans erreurs
- Compatibilité : Dernières versions de Chrome, Firefox & Safari


