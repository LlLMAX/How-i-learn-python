# Vidéo #4 Liste

.pop(y) permet de retirer un élèment d'une liste 
.extend(["x,x"]) permet étendre la liste et de rajouter plusieurs valeurs
.append("x") permet de se selectionner le bout de la list 
del variable[y] permet de retirer une valeurs grâce à ça position
.remove("x")
.clear() permet de retirer toutes les valeurs de la liste
from module import fonction permet importer un module
print"Blablabla {y}" permet de afficher une valeur obtenue dans un texte
.split("délimiteur") fonction qui permet de déterminer un délimiteur dans un message 
input("x") permet d'envoyer un message à la console 
shuffle(variable) permet de mélanger les valeurs d'une liste (from random import shuffle)
print(variable[len(variable) -1]) permet de récuperer le nombre d'élement à la fin d'une liste

exercice :
text = input("Entrez sous la forme (email/pseudo/motdepasse)").split("/")
print(text)

print("Salut {}, ton email est {} et ton mot de passe est {}".format(text[1], text[0], text[2]))

# TP4
from random import shuffle
 
* Générateur de phrases
* demander en console une chaine de la forme "mot1/mot2/mot3/mot4"
text = input("Entrer une chaine de la forme mot1/mot2/mot3/mot4")
 
* transformer cette chaine en liste
mot = text.split("/")
 
* la melanger
shuffle(mot)
 
* recuperer le nombre d'elements
mot_len = len(mot)
 
* si le nombre d'élements de cette liste est inferieur à 10
if mot_len < 10:
  * afficher les deux premiers mots
  print(mot[0], mot[1])
  
* si le nombre d'élements est superieur ou égal à 10
else:
  * afficher les 3 derniers
  print(mot[mot_len - 1], mot[mpot_len - 2], mot[mot_len - 3])

# Vidéo #5 Les boucles

for....in.....: permet de crée un boucle d'une valeur de départ jusqu'a une valeur d'arrivé
range(1, 9) permet de faire un intervalle
 * création d'une boucle for in range!
for client in range(1, 9):
    print("vous êtes le client", client)
#dernière valeur exclue 

Boucle for...in...
#liste de magasin en ligne
shop = ('nike', 'shein', 'adidas', 'ok', 'fairegaffeaupoint...')

for shot in shop:
        print("Regarde c'est ", shot)







