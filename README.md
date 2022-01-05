# Projet-Livre-dont-vous-etes-le-heros
#Projet Nsi, Yanis, Esteban,Jilan

#Livre ou vous êtes le héros
int(input("Dialogues"))
print("Dialogues")
print("Dialogues")
print("Dialogues")
print("Dialogues")

choix = 0 

#Le vaisseau s'écrase sur une planète
print("Vous êtes le seul survivant !")
print("Vous devez survivre !")
print("Vous devez choisir un chemin !")

#Faites votre choix
while choix:
    choix = int(input("\n=>"))
 
#Choisissez votre chemin
if choix == 0:
    print("Si vous voulez rester près du vaisseau. Allez à la page 3")
elif choix == 1:
    print("Si vous voulez explorez la zone. Allez à la page 2")
    
x=int(input("aller:\n1:à droite \n2 à gauche "))
if x==1:
    print("vous allez à droite, un grand arbre se dresse devant vous")
if x==2:
    print("vous allez à gauche, vous entrez dans une caverne")
