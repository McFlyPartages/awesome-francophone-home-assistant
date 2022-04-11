---
title: "Awesome Francophone Home Assistant - Contribuer" # Titre article explicite
date: 2021-03-03 # Date format YYYY-MM-DD
lastmod:   # Date format YYYY-MM-DD   SI rine n'est rentré il prendra la modification GIT.
draft: false
#layout: pages 
type: awesome # Types existant : pages; news; awesome; guidedev;etc. Laisser vide pour les articles

description: "Comment contribuer a la liste des sources francophone parlant de Home Assistant." # Description du sujet.
# hero: /path/image.ext # Recherche un fichier hero.(webp;jpg;png;svg) a la racine du dossier OU si un hero est defini ici SINON il prend un hero par defaut.

# Simple ou multi auteurs, il faut remplir l'auteur principal.
author: 

# Recherche par auteurs et si multi auteurs.
authors:


#socialshare: true # Active l'option de partage
article_ha: false # Ajoute les boutton du forum et les medias des deux communautés Home Assistant (Off et HACF)

hacf:      # Liens vers le post du forum HACF.
url_off:   # Liens vers le post du forum Officiel.

categories: # Categories atuelles : domotique; home assistant; news; nodered;....

series: # En cours permet de reunir des series d'articles autour d'un meme sujet (ex : bien debuter avec HA; ou les addons essentiels pour commencer).
- guide
- 
tags: # Mettre ce qui est en relation avec l'article NE PAS REMETTRE les categories.
- awesome list

keywords: # Mettre tous les mots definissant votre article, ils sont utilisés pour le referencement. PAS de limitation.
- awesome
- liste sources fr
- home assistant
- francophone
- hacf
- communauté francophone



##################################################
##################################################

# Toutes ne sont pas a remplir (ex : pour les pages), il suffit pour cela de ne rien  mettre apres les : ou alors de commenter la ligne avec un # devant.

##################################################
##################################################

###################
# Non fonctionnel
###################
#author:
#  name: Pulpy
#  image: /images/author/pulpy.jpeg

#menu:
#  sidebar:
#    name: HA 2021.9.X
#    identifier: ha-2021-9-X
#    parent: news-home-assistant
#    weight: 10
---
---
################ A MODIFIER ###################################
Veuillez noter que ce projet est liée à un [code de conduite des contributeurs](code-of-conduct.md).
En participant à ce projet vous acceptez de respecter ses termes.
#################################################################
## Modèle pour un lien dans la liste

Utilisez le modèle : `[Nom_du_lien](url_du_lien) - Descriptif du lien.`

## Comment contribuer à la liste

Cette liste est ouverte à tous. Y contribuer est simple: vous avez besoin uniquement d'un compte [GitHub](https://github.com/).

Voici un guide pas à pas pour contribuer à cette liste:

1. Rendez vous sur le [dépôt de la liste](https://github.com/hacf-fr/awesome-francophone-home-assistant) sur GitHub
2. Cliquez sur le fichier `README.md`: ![Fichier README](img/ficher_readme.png)
3. Cliquez sur le bouton `edit`: ![Editer le fichier](img/github_edit.png)
4. Vous pouvez éditer le contenu du fichier dans votre navigateur. Assurez vous de suivre les bonnes pratiques ci-dessus. Le fichier utilise le language GitHub Flavored Markdown avec une ([introduction pour les débutant](https://learnxinyminutes.com/docs/fr-fr/markdown-fr/) et la [spécification détaillée pour un usage expert](https://github.github.com/gfm/).
5. Indiquez dans le formulaire de bas de page pourquoi vous proposez ces changements et cliquez sur "Propose file change": ![Commenter les changements](img/propose_change.png)
6. Envoyez votre Pull Request.
7. Attendez une relecture et répondez aux éventuelles demandes de modification.
8. Votre contribution est fusionnée si elle répond à toutes les exigences du projet.

Merci pour votre contribution.

## Pour tester la génération du site statique
 ######################## A MODIFIER #####################################################################
Cette Awesome list est utilisée pour générer un site web statique à l'aide de [Mkdocs](https://www.mkdocs.org/).
Pour tester en local la génération vous avez besoin d'installer [nox](https://nox.thea.codes/en/stable/)
au préalable.
Ensuite nox s'occupe d'installer toutes les dépendances nécessaires
dans un environnement virtuel:

`$ nox -s docs`

Cette commande a deux comportements:

- En mode interactif (typiquement quand vous lancez la commande dans votre terminal),
  elle génère le contenu du site statique
  et lance un serveur pour le consulter à l'aide de son navigateur en consultant l'URL `http://127.0.0.1:8000/`
- En mode non-interactif (dans un script de _Continuous Integration_ par exemple),
  elle génère le contenu du site statique dans le répertoire `site`.
