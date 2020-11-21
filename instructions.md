Pour changer les noms des categories dans le Header:
1 => acceder au fichier \_includes/header.html et changer le noms
2 => il faut aussi changer href="/category/nom_de_la_categorie/"
3 => pour ajouter une categorie suivez la meme logique dans les lignes precedents
4 => acceder au dossier category et creer un fichier nom_de_la_categorie.md ou changer le nom du fichier deja existant au cas ou tu veux changer le nom
5 => suiver la meme logique dans les autres fichiers dans ce dossier

Pour changer les noms des categories dans la section au dessus de Menu:
1 => acceder au fichier \_config.yml
2 => changer le title et url sous Categorie avec le nom que vous voulez
3 => faire la meme chose dans /src/yml/site.yml

Pour changer le contenu des articles:
1 => acceder au dossier \_posts
2 => vous allez remarquer que le contenu est exactement le meme dans la page de l'article
3 => remplacer le contenu du fichier par ce que tu veux
4 => vous allez remarquer des tags comme celui la <tag/> c'est une syntaxe pour donner une forme au text qui est ecrit dedans
5 => changer le contenu dans ces tags et si tu ne comprend pas de quoi il s'agit passer le nom de la tag en recherche Google tu vas trouver l'explication sur le role du tag
6 => quand changer le nom de l'article dans \_posts faites la meme chose et changer le nom du fichier dans le dossier \_site
7 => Pour ecrire en arabe acceder au fichier \_site/nom_de_l'article/index.html et changer html tag en <html lang="ar" dir="rtl" class="no-js">
