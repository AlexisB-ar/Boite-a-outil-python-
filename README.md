# Boîte à outils Python

## **Description**
Ce projet comporte une collection de 4 programmes permettant de tester, analyser et améliorer la sécurité des mots de passe.  
Il inclut les méthodes suivantes :  
- **La Force Brute** : Test de mots de passe en essayant toutes les combinaisons possibles.  
- **Attaques par dictionnaire** : Utilisation d'une liste préexistante de mots pour tester la robustesse des mots de passe.  
- **Un générateur de mots de passe sécurisés** : Création automatique de mots de passe robustes.  
- **Un analyseur de robustesse** : Évaluation des points forts et des faiblesses des mots de passe.  

Le tout est intégré dans une interface graphique, rendant ces outils faciles à utiliser, même pour les non-experts.

---

## **Table des matières**
1. [Description](#description)  
2. [Programme 1 : Force Brute](#programme-1--force-brute)  
3. [Programme 2 : Attaque par dictionnaire](#programme-2--attaque-par-dictionnaire)  
4. [Programme 3 : Générateur de mot de passe sécurisé](#programme-3--générateur-de-mot-de-passe-sécurisé)  
5. [Programme 4 : Analyseur de mot de passe](#programme-4--analyseur-de-mot-de-passe)  
6. [Interface graphique](#interface-graphique)  
7. [Instructions d'installation](#instructions-dinstallation)  
8. [Technologies utilisées](#technologies-utilisées)  
9. [Licence](#licence)  

---

## **Interface Graphics**
### Description :  
Menu principal de l'interface graphique permettant de chosir entre les quatres programmes
### Fonctionnement :  
1. Lancement de l'interface graphique : lancer le fichier du nom de "interface_graphique"
2. Ensuite vous arriver sur l'interfece avec plusieur informations :
3. Vous avez une zone de texte avec une description de chaque programme
4. En dessous vous avez les boutons ou vous pouvez cliquez sur le bouton correspondant au programme que vous souhaitez lancer.
5. Fonctionnement des boutons :
- Programme 1 : Lance la méthode de brute force.
- Programme 2 : Lance l'attaque par dictionnaire.
- Programme 3 : Lance le générateur de mots de passe sécurisés.
- Programme 4 : Lance l'analyseur de mots de passe.
6. Chaque bouton ouvre une fenetre dans l'interface graphique avec chacune des fonctionnalité differente en fonction du programme.

---

## **Programme 1 : Force Brut **
### Description :  
Ce programme effectue une attaque par force brute, le programme vous demande de rentrer un nombre de caractere qui sera ecrit dans fichier du nom de "fichier.txt" ou sera ecrit tout les motes de passe incluent tous les types de caractères disponibles (majuscules, minuscules, chiffres, symboles). 
### Fonctionnement :  
1. Vous appuyez sur le bouton programme 1 dans l'interface principale une fenetre vas s'ouvrir
2. Vous allez etre rediriger sur la fenetre 
3. Sur celle si il y aura des fonctionnalité
- Le programme vas vous demander de saisir un nombre de cacractere
- une fois que vous avez saisi votre nombre dans la zone de saisi
- appuyer sur le bouton generer
- un message s'affichera en vous disant que "Les mots de passe sont générés dans fichier.txt"
- vous allez dans la commande sur le fichier du nom de "fichier.txt"
- Les mots de passe seront ecrit selon votre nombre 
5. Le programme compare le mot de passe au dictionnaire.  
### Objectif :  
Mettre en évidence les risques des mots de passe trop basiques.

---

## **Programme 3 : Générateur de mot de passe sécurisé**
### Description :  
Un outil rapide et fiable pour créer des mots de passe robustes.  
### Fonctionnement :  
1. Définissez les critères (longueur, types de caractères).  
2. Le programme génère un mot de passe unique et sécurisé.  
### Objectif :  
Faciliter la création de mots de passe complexes.

---

## **Programme 4 : Analyseur de mot de passe**
### Description :  
Ce programme évalue la robustesse des mots de passe en fonction de plusieurs critères (longueur, complexité, caractères utilisés).  
### Fonctionnement :  
1. Entrez un mot de passe.  
2. Le programme vous fournit une note et des conseils pour l'améliorer.  
### Objectif :  
Sensibiliser à l'importance des mots de passe forts.

---

## **Interface graphique**
### Description :  
Une interface conviviale qui centralise tous les outils en un seul endroit.  
### Fonctionnement :  
1. Lancez l'interface graphique avec le fichier principal.  
2. Naviguez entre les différents outils via les boutons de l'application.  
### Objectif :  
Simplifier l'accès et l'utilisation des programmes.

---

## **Instructions d'installation**
1. Clonez le projet depuis GitHub :  
   ```bash
   git clone [URL]
   cd [répertoire_du_projet]

