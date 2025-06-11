## Base de code pour le cours HTML CSS

CSS est un autre langage qui vient compléter le HTML. Son rôle est de mettre en forme votre page web.

Pour écrire le code CSS, on crée un fichier séparé portant l'extension .css  comme style.css.

Pour lier les fichiers CSS et HTML, on rajoute une ligne dans la balise <head> </head> du fichier HTML :  <link href="style.css" rel="stylesheet">

En CSS, on sélectionne les portions de la page HTML qu'on veut modifier, et on change leur présentation avec des propriétés CSS :

balise1
{
    propriete1: valeur1;
    propriete2: valeur2;
}
Il existe plusieurs façons de sélectionner la portion de page que l'on veut mettre en forme. Par exemple, on peut viser :

toutes les balises d'un même type, en écrivant simplement leur nom (h1par exemple) ;

certaines balises spécifiques, auxquelles on a donné des noms à l'aide des attributs class ouid(.nom-classe ou #nom-id) ;

uniquement les balises qui se trouvent à l'intérieur d'autres balises (h3,em).