# Vocabulaire en python

Les fonctions, les méthodes, les attributs, les instances 

Les méthodes : C'est des actions et des comportements comme add_water()

Les attributs : Ce sont des variables qui donnent des caractéristiques. 
Exemple : Class Animal et on va lui donner des attributs tels que sont type, sa taille, sa couleur.

Différents types d'attribut :
- Les attributs d'instance(propres aux instances crées)
- Les attributs de classe(propre à la classe et partagés aux instances)
- Les attributs statiques (qui sont presque indépendants de la classe)
Les variables c'est lorsque que tu donnes des paramètres à ta classe et que tu lui donnes des valeurs.

Pour les méthodes d'instances : Tu dois tjrs mettre en premier paramètre (self)

Les instances : C'et lorsque tu définis des paramètres

Le constructeur init
--> Son rôle principal est d'initialiser les attributs de l'objet nouvellement crée, elle est appelée lors de la création d'une instance.

	__init__

Utilisation d'une méthode de class ![[Screenshot from 2026-05-16 13-08-01.png]]
Qu'est-ce qu'une classe ?

	Les classes sont un moyen de réunir des données et des fonctionnalités. Créer une nouvelle classe crée un nouveau _type_ d'objet et ainsi de nouvelles _instances_ de ce type peuvent être construites. Chaque instance peut avoir ses propres attributs, ce qui définit son état. Une instance peut aussi avoir des méthodes (définies par la classe de l'instance) pour modifier son état.
Pour initier différents types de la class

	Class NameType (NameofthefirstClass)
			super()__init__(same parameters as the first)

Utilisation de Try/Except

Try : Test différentes choses
Raise : On déclenche une erreur 
Except : Tu attrapes et tu gères l'erreur
Exemple :
	try :
		raise Error()
	except Error()
	    print("*Message d'erreur*")
