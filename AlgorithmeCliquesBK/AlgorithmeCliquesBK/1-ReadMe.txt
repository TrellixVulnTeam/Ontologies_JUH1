Liste des fichiers:
DataTestAlgo ==> Tableau de valeur utilis� pour tester l'algorithme
ExempleDataClasse ==> Le fichier contient la liste des classes utilis� dans l'algorithme
ExempleDataLink ==> L'ensemble des liens d'une classe au autre selon ce format :
	[] --> toujours commencer par une liste vide
	[...] --> Les classes li�es � la permi�re classe
	[...] --> Les classes li�es � la deuxi�me classe
	ect
BronKerbosch ==> Algorithme de Coen Bron et Joep Kerbosch
PivotBronKerbosch ==> Algorithme de Coen Bron et Joep Kerbosch, opti avec un pivot
Sommet ==> Classe compos� d'une Data et un Id, Data = import et Id = image de la Data dans l'algorithme
Traducteur ==> Convertit les fichiers Data en remplacant les String des nom des classes par des Id
Reporter ==> G�re l'ensemble de l'affichage
Main ==> Appelle les fonctions

Auto_Data ==> Fichiers cr��s par la traduction de ExempleDataLink en Id
cliques_Result ==> Le fichier contenant les r�sultats