# Repository:# evaltrain1_grizzli

# ======== READ-ME / LISEZ-MOI ======== #

Retrouvez au sein de ce fichier tous les éléments liés au développement du site de l'association "Compagnie Grizzli".

Ce documents contient :
=> INSTRUCTIONS D'UTILISATION
=> MISES À JOUR ET BUGFIXES (antéchronologique)
=> HISTORIQUE DE DÉVELOPPEMENT (Chronologique)

# --- INSTRUCTIONS D'UTILISATION --- #

        * A LIRE ATTENTIVEMENT *

Le site de l'association "Compagnie Grizzli" présent sur ce dépot est destiné aux formateurs de Digital Campus Live (Groupe STUDI) pour évaluation, correction et suivi de développement web. La compagnie Grizzli est une association loi 1901 déclaré, par conséquent les documents présents ne peuvent être diffusés ou réutilisés dans un autre but qu'une évaluation de formation. Tout contenu présent dans ce site (images, textes, noms d'événements) a un caractère fictif (hors logotype). 


# --- MISES À JOUR ET BUGFIXES --- #
#MAJ_bugfix[210803]:
	* Modification du Responsive Design pour écran de max 700px, 900px, 1024px.
	* Gestion des bugs écrans adaptatifs 

#MAJ_bugfix[210803]:
	* Modification du Responsive Design pour écran de 400px max de largeur

#MAJ_STYLE[210803]:
	* Ajout d'un bouton sur dans la section asso de la page home.html
	* Stylisation du bouton

#MAJ_CONTENT[210803]:
	* Ajout de contenus textes pour les événements

*MAJ_STYLE[210803]:
	* Ajout d'un hover visible sur les boutons 'Réserver'

*MAJ_Bugfix[210803]:
	* Page 'event.html' : Suppression de l'espace entre le contenu de la page événements (body) et le menu
	* Ajustement de la présentation des cartes sur la page (3 par 3) -> padding 

*MAJ_STYLE[210803]:
	* Réduction du logo et du titre, puis centrage du contenu dans le header -> page event.html
	* Réglages du menu principale en corrélation avec le header -> Page event.html

*MAJ_STYLE[210801]:
	* Réglage des couleurs du menu principal

*MAJ_STYLE[210801]:
	* Lissage du fichier 'style.css' : suppression des contenus 'test' inutilisés

*MAJ_Bugfix_H01B[210801] :
	* Correction et mise en page du header sur la page event.html
	* Correction du menu de navigation principal : espace, alignement, survol

*MAJ_Bugfix_F01[210801] :
	* Correction des espaces internes dans le footer [Toutes les pages]
	* Correction de l'interlignage des éléments de navigation
	* Correction du survol sur les liens

*MAJ_Bugfixe_B02[210801] :
	* Correction de l'esthétique et de la mise en page des boutons "Réserver"
	* Amélioration de la mise en page de la section Association > page home.html

*MAJ_Bugfixe_B01[210728] :
	* Mise en page du contenus des sections "Association" et "Evenements (nouveau titre -> "A l'Affiche")
	  ->> Marges internes (hautes et basses) + Couleurs de fond + Aspect des titres (h2) + Alignements des contenus
	* Ajout des Cartes événements dans la section "Evénements /A l'Affiche"
	
*MAJ_Bugfixe_H02[210728] :
	* Ajustement des boutons Header : séparation centrale
	* Modification CSS de l'aspect des boutons (Bootstrap + réajustement perso)

*MAJ_Bugfixe_H01[210727] : 
	* Ajustement du positionnement du logo et du titre (H1) dans le header
	* Alignement des boutons sous le titre (Grid-centré)
	* Ajustement du séparateur de page : bottom header
	* Mise en page Responsive du Header (max-width:700px uniquement)

# --- HISTORIQUE DE DEVELOPPEMENT  --- #

# Création des pages : "home.html" et "event.html"
 -> Mise en place de la structure HTML des pages

# Création et ajout des dossier : "Images" et "Style"
 -> Téléchargement du "LOGO" dans le dossier "Images"

# Intégration de Bootstrap (CSS-JS)
-> Javascript non-utilisé
-> CSS pour certains boutons et les cartes événements 

# Création et ajout du dossier "Scripts"
-> Inclut js Bootstrap

# Mise à jour du dossier "Images
-> Suppression du premier fichier "LOGO" et remplacement dans une autre taille et un autre format (500px-png)

# Développement page "home.html" :
-> header : contenu et titre
-> body : contenus et titres
-> footer : contenus et menus (textes sans liens hypertextes)

# Création du fichier "style.css"
-> Développement d'une mise en page du contenu
-> Intégration des balises <link>

# Bugfix - Réajustement du header
-> Boutons des liens vers 'association' et 'événements'
-> Gestion Responsive du header pour les écrans jusqu'à 700px max de largeur

# Bugfix - Réajustement de la mise en pages de 'home.html'
->  Mise en page des sections 'association' et 'événements' dans le Header 
-> Ajustements de : boutons + couleurs de fond + Marges

# Ajout du contenu sur la page "event.html"
-> Ajout des cartes événements et de leur contenu textuel
-> Ajout du footer

# Mise en page de "event.html" 
-> Création et ajustement de Header (standard)
-> Mise en page du contenu Body
-> Correction des bugs du Footer

# MAJ : Lissage du fichier 'style.css'
 -> suppression des appels de balise inutilisés

# MAJ : Page 'event.html'
-> couleur et survol du menu principale de navigation

# MAJ : Page 'event.html'
-> Réglages et adaptation du menu et du header 
-> Réduction du logo, du titre et du menu principal

# MAJ : Page 'event.html'
-> Supression de l'espace en trop entre le contenu événements et le menu

# MAJ : Toutes les pages
-> Ajout d'un hover visible en cohérence avec les couleurs utilisés sur les boutons 'Réserver'

# MAJ : Page 'event.html
-> Ajout du contenu texte lieu et date pour les événements

# MAJ : Page 'home.html'
-> Ajout et style du bouton 'Découvrir la compagnie' > section 'association'

# Bugfix (Responsive) > Page 'home.html'
-> Adaptation des éléments de la page home.html pour les écrans de 400px de largeur

# Bugfix (Responsive) > Page 'home.html' + 'event.html'
-> Adaptation des éléments des pages pour les écrans de largeur-max : 400px, 700px, 900px, 1024px.

# MAJ : Meta description
-> Mise à jour des méta description dans les pages 'home.html' et 'event.html'

#
