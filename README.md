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
2. [Programme 1 : Force Brute](#Programme 1 : Force Brut)  
3. [Programme 2 : Attaque par dictionnaire](#programme-2--attaque-par-dictionnaire)  
4. [Programme 3 : Générateur de mot de passe sécurisé](#programme-3--générateur-de-mot-de-passe-sécurisé)  
5. [Programme 4 : Analyseur de mot de passe](#programme-4--analyseur-de-mot-de-passe)  

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

## Programme 1 : Force Brut 
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
- vous allez dans la console sur le fichier du nom de "fichier.txt"
- Les mots de passe seront ecrit selon votre nombre 
5. Le programme compare le mot de passe au dictionnaire.  
### Attention : Si vous entrer un nombre de caractere en dessus de 5 a generer sa ne marchera pas parce que sa prendra trop de temps a généré


---

## Programme 2 : Attaque par dictionnaire
### Description :  
Ce programme teste la sécurité des mots de passe en utilisant une liste prédéfinie de mots communs.  
J'ai crée un fichier ZIP ou j'ai mis un mot de passe, puis j'ai télécharger une liste de mots de passe communs sur internet oiu j'ai ajouter le mot de passe du fichier. 
### Fonctionnement :  
1. Vous pouvez revenir sur l'interface principale directement via les onglets en haut de la page
2. Vous appuyez sur le bouton programme 2 dans l'interface principale une fenetre vas s'ouvrir
3. Sur celle si il y aura une fonctionnalité
- une vous allez retrouver un bouton avec ecrit "Affichez le mot de passe"
- appuyer dessus celui ci vous affichera le mot de passe de mon fichier zip, le mot de passe que j'ai mis dans la liste
- Chaque fois que vous cliquer sur le bouton le message "bonjour :réussite !!" s'affichera dans la console


---

## Programme 3 : Générateur de mot de passe
### Description :  
Dans ce programme il y a plusieurs outils : 
- Un outil qui permet de créer des mots de passe robustes
- Un historique des 5 dernier mot de passe généres
- Affichage de conseil pour créer un mot de passe robustes
### Fonctionnement :  
1. Vous pouvez revenir sur l'interface principale directement via les onglets en haut de la page
2. Vous appuyez sur le bouton programme 3 dans l'interface principale une fenetre vas s'ouvrir
3. Sur celle si il y aura plusieurs fonctionnalité :
- Quand vous appuyez sur le bouton générer sa genere un mot de passe robuste de 12 caractere qui mélange (chiffres,Mascule,Minuscule et chiffres)
- Chaque fois que vous appuyer sur le bouton a nouveau mot de se genere
- Tous les mots de passe qui se sont afficher s'affiche dans l'historique en dessous du bouton du plus ancien au plus recent (c'est les 5 derniers mot de passe generer)
- Vous avez aussi un bouton "Afficher Conseils" qui vous affiche des conseils pour créer un bon mot de passe



---

## Programme 4 : Analyseur de mot de passe
### Description :  
Ce programme évalue la robustesse des mots de passe en fonction de plusieurs critères (longueur, complexité, caractères utilisés).
Avec trois niveau de robustesse : 
- Faible
- Moyen
- Fort 
### Fonctionnement :  
1. Vous pouvez revenir sur l'interface principale directement via les onglets en haut de la page
2. Vous appuyez sur le bouton programme 4 dans l'interface principale une fenetre vas s'ouvrir
3. Sur celle si il y aura plusieurs fonctionnalité :
- Vous pouvez entrer le mot de passe que vous souhaitez vérifier la robustesse dans le zone de saisi
- appuyer sur le bouton "Analyser", est le programme vous diras le niveau de robustesse de votre mot de passe 
- Vous avez aussi un bouton "Afficher Conseils" qui vous affiche des conseils pour créer un bon mot de passe


---


