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

### LET :
let remplace var, mais il est scopé au niveau du bloc de code

### CONST : 
déclation de la constante :
pas possible sans lui attribuer une valeur :
scopé au niveau du bloc de code

const est mutable : modifiable 
la seule chose pas changeable est le lin mémoire (le pointeur ou ref)

S'obliger à mettre des const : plutot que des let :

Let pour des boucles for, et concaténation de chaines

### les classes :

class , extends {

    construtor

    super (parent)
}

const dragon = new Dragon('lol');


### template STRINGS

" et ' : initialement : pour les chaines decharactères

maintenant nouveau `


### Destructuring

- déclaration de variable plus sexy

fonction pour déclarer un variable et un tableau(attention à l'ordre)


### SPREAD 

Explose les paramètre d'un tableau dans un objet ou tableau

mafoncion(...variable)

concatène aussi un tableau

fusionne un objet


### REST

récupère les paramètre d'une fonction sous forme d'un tableau


function maFunction(...param){

}
maFunction('1', '2');


### Arrow functions

- déclaration de fonction simplifiés
- return implicite
- scope préservé


var add = function(a,b) {
    return a + b;
}

const add = (a,b) => a + b;


const square = x => x * x; // si un seul paramètre, pas besoin de parenthèse


### scope arrow function

dans l'exemple, c'est le link


### valeur par défaut

possibilité de mettre une valeur par défaut
ES5 

lastname = lastname || 'lol';
