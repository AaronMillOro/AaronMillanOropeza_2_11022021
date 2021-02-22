# Cahier de charges pour la maquette du site web ‘RESERVIA’

Deux maquettes basées sur le principe du *Material Design* ont été mises à disposition ([Desktop](https://github.com/AaronMillOro/AaronMillanOropeza_2_11022021/blob/master/img/model/Desktop-1.png) et [mobile](https://github.com/AaronMillOro/AaronMillanOropeza_2_11022021/blob/master/img/model/iPhone8-1.png)) pour les coder sous forme de site web. Les spécifications téchniques sont indiquées ci-dessous.

## Fonctionnalités demandées

* Les usagers pourront rechercher des hébergements dans la ville de leur choix. Le **champ de recherche est un champ de saisie**, dont le texte peut être édité par l’usager. En revanche, à ce stade, le bouton de recherche n'est pas fonctionnel.
  
* **Chaque carte** d’hébergement ou d’activité est  **cliquable** dans son intégralité. Pour l’instant les liens sont vides.
  
* Les **filtres** ne sont pas fonctionnels pour cette version. Ils **changent d’apparence au survol**.
  
* Dans le menu, les **liens “Hébergements” et “Activités” sont des ancres** aux sections de la page.

## Précisions techniques

* En plus des deux maquettes disponibles (la version desktop et la version mobile), le **site** est **adapté aux tablettes**. Sur ce support, la mise en page est adaptée pour qu’**aucun élément n’est coupé et que le texte a une taille suffisante**. Les *breakpoints* établis sont: 
  * Moins de 768px pour la version **mobile**
  * Moins de 991px pour la version **tablette**
  * Moins de 1200px pour la version **desktop**

* Plusieurs tailles et formats d’image ont été proportionnées. Pour le **logo** le format **png** a été choisi et pour les **cartes d'hébergement et activités** la taille **small** a été implementée.
  
* Les **icônes** proviennent de la bibliothèque **Font Awesome** et ils sont intégrés via HTML.
   
* Les **couleurs** de la charte sont le bleu #0065FC, et sa version plus claire #DEEBFF ainsi que le gris pour le fond #F2F2F2.
  
* La police du site est **Raleway**.
  
* Le site est **codé en HTML et CSS** (sans pre-compilateur).
  
* La disposition d'éléments est possible grâce à  l’utilisation de **Flexbox et de CSS Grid**.
  
* Le site contient de **balises sémantiques**
  
* Le site ne contient pas aucune erreur ni alerte sur le **validateur W3C** [HTML](https://validator.w3.org/) et [CSS](https://validator.w3.org/unicorn/).

* Le site est **compatible** avec les dernières versions de **Chrome et Firefox**.
  
* Le code **HTML et CSS**, ainsi que les différents fichiers, sont **organisés séparément**.
  
* Le développement du code est versioné avec **Git**. La sémantique des commits est la suivante:
  * <:pencil2:> nouveux éléments / code
  * <:wrench:> modification ou amélioration du code
  * Les commits sont écrits en anglais 
  
* Le site est **déployé sur GitHub Pages**.

Profitez-en bien :shipit: !