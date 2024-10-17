# Mémento Javascript


## Variable

### Déclaration de variable

var NOM_VARIABLE;
var resultat;

### Donner une valeur à une variable

NOM_VARIABLE = VALEUR;
prenom = "Guillaume";

Déclarer et donner une valeur peut être fait en une seule ligne :
var NOM_VARIABLE = VALEUR;
var nom = "Smith";


## Fonctions

### Déclarer une fonction

function NOM_FONCTION() {
    ...
}

### Définir des paramères

function addition(nombre1, nombre2) {
    ...
}

### Retourner une valeur

function addition(nombre1, nombre2) {
    return nombre1 + nombre2;
}

### Appeler une fonction

NOM_FONCTION();
manger();
addition(4, 6);

### Récupérer le résultat d'une fonction

var resultat = addition(4, 6);

### Fonctions déjà existantes

Demander une valeur à l'utilisateur sur une page Web : prompt("Saisissez une valeur :")
Afficher une valeur à l'utilisateur sur une page Web : alert("Message à afficher");
Afficher une valeur dans la console : console.log("Message à afficher");


## Opérateur

### Manipuler des nombres

addition : nombre1 + nombre2
soustraction : nombre1 - nombre2
multiplication : nombre1 * nombre2
division : nombre1 / nombre2

### Manipuler des chaînes de caractères

concaténation (addition) : texte1 + texte2

### Manipuler des booléens

égalité : nombre1 == nombre2
différence : nombre1 != nombre2
inférieur : nombre1 < nombre2
supérieur : nombre1 > nombre2
inférieur ou égal : nombre1 <= nombre2
supérieur ou égal : nombre1 >= nombre2
OU conditions : condition1 || condition2
ET conditions : condition1 && condition2
INVERSER condition : !condition

## Structure

### Structure conditionnelle

if (condition) {
    faireUneAction();
    eventuellementUneAutre();
}
// dans le cas contraire
else {
    faitCeQueTuVeux();
}