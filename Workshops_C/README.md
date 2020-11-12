# Step 1: 
***
## _*#1*_ : 

```diff
Ecrivez un programme en C qui va te permettre d'afficher vos informations personnelles : Nom, prenom , Age , Sex et numero de telephone 
Les données sont saisies à partir du clavier
```

## _*#2*_ : 
```
a et b sont deux entiers saisies au clavier, calculez et affichez a+b, a-b, a*b, a/b, a%b en
format décimal, et en soignant l’interface homme/machine.
(a/b donne le quotient de la division, a%b donne le reste de la division)

```
## _*#3*_ : 
```
Ecrivez un programme en C qui déclare la variable constante pi et la variable r.
Déclarez trois variables D, P et S calculez respectivement les valeurs du diamètre, du périmètre et de la surface d’un cercle dont le rayon est r.
On affichera à l’écran le contenu de ces différentes variables selon le format suivant :
Un cercle de rayon r a pour diamètre D, pour périmetre P et pour surface S.
NB : Le rayon est une entrée du programme (entrer au clavier par l’utilisateur). 
```
## _*#4*_ : 
```
Ecrire un programme qui affiche la moyenne d'une suite d'entiers positifs entrés au clavier. On arrêtera la saisie quand le nombre -1 est entré,
comme dans l'exemple suivant :  
Entrez un entier positif : 5
Entrez un entier positif :2 
Entrez un entier positif :3 
Entrez un entier positif :-1 
La moyenne de ces 3 entiers vaut 3.333333 
```

# Step 2: 
***
## _*#1*_ : 
```
Pour une gestion du mémoire il est recommandé de creer des constantes sous forme d'expression (Macros), 
ce qui est demandé est de creer une constante qui te permet de vérifier si un nombre est superieure à un autre le resultat du retour soit 0 soit 1 ,pour formater le resultat de retour créez un constante qui permet d'afficher si 0 = False si 1 = true
Macro : MAX(a,b)
Nota bene : il faut creer votre premier type boolean afin de permettre la bonne marche du programme 
```

## _*#2*_ : 
```
Creez votre calculatrice conditionnée : 
* Ecrivez un programme qui permettra d'entrer deux nombres aux claviers et les afficher avec leur taille en Octet et en Hexadecimal.
* Maintenant Controller les signes : + , - , * , / , % comme char.
* si le signe est + on va faire l'addition des deux nombres
  si le signe est - on va faire la soustraction etc ...
 
* pour le cas de la division vérifiez si la valeur du diviseur est différente de 0 
  si oui faire la division sinon afficher erreur
  
* Affichez le resultat à l'écran.
* Créez votre arbre de décision

Refaite le meme exercice en utilisant `switch Case`
```

## _*#3*_ : 
```
Ecrivez une fonction en C qui permet de résoudre une équation du deuxieme degrés ax² + bx + c = 0 
les coefficients a,b et c sont saisi à partir du clavier 

Hint : 
Delta = b²*4*a*c, basez vous cette formule pour trouver les solutions
```

## _*#4*_ :
***
```diff

Calculez le plus grand diviseur commun de deux nombres entrez au clavier 
Affichez toutes les étapes du Calcul

+ Algorithme : On veut calculer le pgcd des nombres 21 et 15

pgcd(21,15) =>  
Step 1 : 21 = 15 * 1 + 6
Step 2 : 15 = 6 * 2 + 3 
....
On va continuer les steps  jusqu'à avoir un diviseur = 0 et un reste = 0.

Refaite le meme exercice avec la boucle while 
```
## _*#5*_ :
***
```
Ecrivez un programme en C qui va te permettre de saisir un nombre au clavier et de savoir si c'est un nombre premier ou non premier ?

Nota bene : Un nombre premier est un nombre qui est divisé par un et lui meme
```

## _*#6*_ :
***
```
Ecrire un programme qui multiplie deux entiers positifs a et b selon le principe récursif suivant : 

a * b = a * (b-1) + 1 si b est impair
a * b = (2 * a) * (b/2) si b est pair et different de 0 

Exemple : 
36 * 7 = 36 * 6 + 36 
       = 72 * 3 + 36
       = 72 * 2 + 108
       = 144 * 1 + 108 
       = 144 * 0 + 252
       = 252
       
 Soignez l'interface homme/machine en respectant l'affichage ci-dessus et selon la méthode récursif expliqué précédemment      
       
```


## _*Challenge*_ : 
***
```
Créez une table de multipilcation d'un nombre saisi au clavier .
Cette table de multiplication débute du nombre 1 et finisse à 10.
A vous de découvrir l'algorithme

```

# Step 3: 
***
## _*#1*_ :
```diff
+ Expliquez la difference entre : 

 int main()
  {
    return 0;
  }
  
  +et : 
  
 int main(int argc,char const **argv)
 
 +Justifiez votre réponse avec des exemples. 
         
```

## _*#2*_ : 
```
Créez votre premiére fonction :
 [1] Creez une fonction int howOld() qui retoune l'age, affichez l'age retournée.
 [2] Creez une fonction qui tableMultipilcation(int start,int end) qui prend en parametre deux entiers et qui affiche la table de multiplication de deux nombres.
 [3] Constatez que lorsqu'on débute un programme en C, on déclare toujours une bibliotheque de fonction qui nous permet de faire appel à des fonctions comme printf or scanf
  -- Creez un fichier function.c est mettez les deux fonctions précédemment créer dans ce fichier
  -- Appelez les fonctions dans le fichier main.
  -- Qu'est ce que vous constatez ? 'Une erreur'
  -- Trouvez la solution pour corriger cette erreur
```

## _*#3*_:
```diff
Ecrivez une fonction qui permet d'afficher une pyramide des étoiles :

+Algorithme : https://miro.com/welcomeonboard/LAeQfjZ77hMqRhJsPUsYXQhLX5w49xpyS86ZeVJqisyC2k9iCfvK2Nhrt2QN7Nno

Pour réaliser le workshop : créez deux fonctions void PrintStar(int n) pour dessiner des étoiles et void PrintSpace(int n) pour les espaces

En se basant sur la pyramide créée, Créez une fonction qui permet de visualiser un triangle des étoiles depuis la pyramide.
```

## _*Challenge*_ : 
***
```
Créez une fonction add(int a , int b) qui permet de faire l'addition des deux nombres a et b 
Créez une fonction echanger() pour echanger la valeur de a avec la valeur de b, qu'est ce que vous constatez ? affichez aussi l'etat initial des variables a et b 
Créez une fonction `bool isPremier()` pour vérifier si un nombre il est premier ou non (constatez que le type de la fonction est bool, donc vous devez créez votre type Bool)
Créez une fonction divededby(int n,int a) qui retoune la division des deux valeurs
utilisez la fonction dividedby() pour controller si le nombre est premier en retoune true, sinon on retourne false
```

:computer::computer::computer::computer::computer::computer: :computer::computer::computer: :computer::computer::computer: :computer::computer::computer: :computer::computer::computer: :computer::computer::computer: 
