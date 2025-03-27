
# Analyse de TP01

[[toc]]


*(je me fis ici à cette page [Page de bonne pratique](https://appweb.progwmj.ca/documentations/bonnes-pratiques/code) pour toute analyse)*

## Élément 01 - Code propre

Dans la __majorité__ du projets, peu ou pas de commentaires sont présents pour expliquer le code écris. Ensuite, beaucoup de code est très long sans nécessairement ajouté de fonction pour réduire la lourdeur du code. Par exemple, dans mon App.vue, mon script fais 75 ligne, et plusieurs fonction aurait pus être mis pour alléger cela. 

### Dans les componants

dans mon  VideoGameForm, je créer directement une liste de jeux avec leur parametre requis pour être dans ma liste. Avec cela, j'allourdi le code et **_gaspille_** 61 lignes de code dans un fichier pour lequel c'était pas pertinant qu'ils ce retrouvent là. 

Dans le VideoGameList, dans le script, j'ai encore un probleme d'organisation car je ne créer aucune autre fonction afin d'alléger le code

Étant donné que ses mes deux seules fichiers dans le dossier **_components_**, cela viens démontrer mon manque de maitrise au niveaux d'ajouter des fonctions à l'intérieur du code pour le rendre moins long à lire et pertinent dans sa position. 

## Fichiers/Code Non utilisé

  je ne vois aucun code pour deboguer, ni de code non utiliser. Le probleme est pas mal juste que je ne sépare pas le code en fonction.

# Gestion des erreurs

Dans le Tp1, il n'était pas requis de géré les erreurs pouvant être présente dans le code. Cependant, les seule erreurs que j'ai réellement vus sont ceux qui était lier au fais que j'ai mal écris du html et que sa ne compilais pas, rien étant relier à des erreurs qui __nécessitait__ des erreurs de ma part.
