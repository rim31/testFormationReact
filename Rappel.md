Type d'application en dehors du web :
- node js
- react native
- apllication : mac, windows et linux :electron (slack, atom)


# Syntaxe

### dans une balise script

<script >alert('lol'); </script>  // moins lisible en partage de code, mais temps de chargement plus rapide, idéla pour les sites à fort traffic
### dans un fichier externe
<script scr="lol.js"> </script>   // s'exectute quand le script est appelé, temps de latence : temps de téléchargement plus long(requête http)

## Variables

### ecma5

var variable = "lol";

opérator : + : concaténation

== : cast sur le typ
=== : si la référence est la même


if, else, switch case

for (var key in o) {
    console.log(key, o[key]);
}


les fonctions :

fonction anonymes : qu'on peut stocjker dans une variable


### la chaine de portée : scope

cherche la porté dans la fonction cournat, puis d'autres fonctions appelante, puis le windows, sinon refError


## use strict :
pour desactiver du ES3 déprécié.
"use strict"; //possibilité de le mettre dans une fonction

exemple pour ne pas avoire des varibales de meme noms


# ECMAScript6 et les modules


## ECMAScrpit :

- c'est la specification / règle du langage
- differents autres scripts
javascript est une implémentation :
(actionscript : flash)

-  ES6 / ES2015 : 
...
- ES10 / ES2019