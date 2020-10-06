# Java #

--------------------------------
--------------------------------

## Qu'est-ce que JAVA ##



Java est un langage de programmation et une plate-forme informatique qui ont été créés par Sun Microsystems en 1995. Beaucoup d'applications et de sites Web ne fonctionnent pas si Java n'est pas installé et leur nombre ne cesse de croître chaque jour. Java est rapide, sécurisé et fiable. Des ordinateurs portables aux centres de données, des consoles de jeux aux superordinateurs scientifiques, des téléphones portables à Internet, la technologie Java est présente sur tous les fronts ! 

--------------------------------
--------------------------------

## A quoi sert JAVA ##



Cela permet de faire tourner des applications écrits dans ce langage.
La plateforme Java permet peut se soustraire du système d'exploitation, ce dernier faisant la liaison.
Ainsi une même application Java peut tourner sur Windows ou Linux.
Enfin, des applications Java peuvent être lancées depuis le navigateur WEB, on parle alors d'applet Java, à ne pas confondre avec JavaScript qui n'a rien à voir.

--------------------------------
--------------------------------

## Les notions de variables et les types de variables ##


Les variables contiennent des données réutilisables dans un programme et les associent à un nom.
Les variables sont stockées en mémoire.

* let est le moyen préféré de déclarer une variable lorsqu'elle peut être réaffectée.
* const est le moyen préféré de déclarer une variable avec une valeur constante.  

Les variables qui n'ont pas été initialisées stockent le type de données primitif non défini.  

exemple:  

  String name = "Michel";  
  int yearCreated = 1986;  

  Dans cet exemple, String et int = type de variable  
  name et yearCreated = nom de variable

-----------------------------------------
-----------------------------------------

# les opérateurs #

Les opérateurs sont des symboles qui permettent de manipuler des variables, c'est-à-dire effectuer des opérations, les évaluer, ...
On distingue plusieurs types d'opérateurs :
* les opérateurs de calcul
* les opérateurs d'assignation
* les opérateurs d'incrémentation
* les opérateurs de comparaison
* les opérateurs logiques
* (les opérateurs bit-à-bit)
* (les opérateurs de rotation de bit)

exemple: opérateurs de calcul +  

int redCar = 8;  
int blueCar = 2;  
int total car = red car + blue car;  
// 10

------------------------------------------
------------------------------------------

# les mots clefs #

Les mots-clés ou mots réservés sont les mots d'une langue utilisés pour un processus interne ou représentant des actions prédéfinies. Ces mots ne sont donc pas autorisés à être utilisés comme noms de variables ou d’objets. Cela entraînera une erreur lors de la compilation.  

exemple: Booleans ne peuvent répondre que par false ou true  

boolean int CanHoldDecimals = false;  

------------------------------------------
------------------------------------------

# Les paramètres #

Les parametres sont des variables que l'on peut passer dans une fonction ce qui permet de lui envoyer différente valeurs.

Les parametres peuvent avoir ou :
	- un nombre fixe
	- un nombre variable

Le type des parametres est défini à l'avance lors de la déclaration de la fonction.

	EX :

		int foo (int x, int y) {
		  return x + y;
		}

	  void foo (String[] args) {
		  System.out.println(args[0]);
			System.out.println(args[1]);
			System.out.println(args[n]);
		}
