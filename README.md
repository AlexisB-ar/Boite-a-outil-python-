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
2. [Programme 1 : Force Brut](#programme-1--force-brut)  
3. [Programme 2 : Attaque par dictionnaire](#programme-2--attaque-par-dictionnaire)  
4. [Programme 3 : Générateur de mot de passe sécurisé](#programme-3--générateur-de-mot-de-passe)  
5. [Programme 4 : Analyseur de mot de passe](#programme-4--analyseur-de-mot-de-passe)

## **Interface Graphics**
### Description :  
Menu principal de l'interface graphique permettant de chosir entre les quatres programmes
### Fonctionnement :  
1. Lancement de l'interface graphique : lancer le fichier du nom de "interface_graphique"
2. Ensuite, vous arrivez sur l'interface avec plusieurs d'informations :
3. Vous avez une zone de texte avec une description de chaque programme
4. En dessous, vous avez les boutons où vous pouvez cliquer sur le bouton correspondant au programme que vous souhaitez lancer.5. Fonctionnement des boutons :
- Programme 1 : Lance la méthode de brute force.
- Programme 2 : Lance l'attaque par dictionnaire.
- Programme 3 : Lance le générateur de mots de passe sécurisés.
- Programme 4 : Lance l'analyseur de mots de passe.
6. Chaque bouton ouvre une fenêtre dans l'interface graphique avec chacune des fonctionnalités différentes en fonction du programme.
---

## Programme 1 : Force Brut 
### Description :  
Ce programme effectue une attaque par force brute, le programme vous demande de rentrer un nombre de caractères qui sera écrit dans un fichier du nom de "fichier.txt" où seront écrits tous les mots de passe incluant tous les types de caractères disponibles (majuscules, minuscules, chiffres, symboles).
### Fonctionnement :  
1. Vous appuyez sur le bouton programme 1 dans l'interface principale, une fenêtre va s'ouvrir
2. Vous allez être redirigé sur la fenêtre
3. Sur celle-ci, il y aura des fonctionnalités
- Le programme va vous demander de saisir un nombre de caractères
- une fois que vous avez saisi votre nombre dans la zone de saisie
- appuyer sur le bouton générer
- un message s'affichera en vous disant que "Les mots de passe sont générés dans fichier.txt"
- vous allez dans la console sur le fichier du nom de "fichier.txt"
- Les mots de passe seront écrits selon votre nombre 
5. Le programme compare le mot de passe au dictionnaire.  
### Attention : Si vous entrez un nombre de caractères au-dessus de 5 à générer, ça ne marchera pas parce que ça prendra trop de temps à générer

---

## Programme 2 : Attaque par dictionnaire
### Description :  
Ce programme teste la sécurité des mots de passe en utilisant une liste prédéfinie de mots communs.  
J'ai créé un fichier ZIP où j'ai mis un mot de passe, puis j'ai téléchargé une liste de mots de passe communs sur internet où j'ai ajouté le mot de passe du fichier. 
### Fonctionnement :  
1. Vous pouvez revenir sur l'interface principale directement via les onglets en haut de la page
2. Vous appuyez sur le bouton programme 2 dans l'interface principale, une fenêtre va s'ouvrir
3. Sur celle-ci, il y aura une fonctionnalité
- une vous allez retrouver un bouton avec écrit "Affichez le mot de passe"
- appuyez dessus, celui-ci vous affichera le mot de passe de mon fichier zip, le mot de passe que j'ai mis dans la liste
- Chaque fois que vous cliquez sur le bouton, le message "bonjour : réussite!!" s'affichera dans la console

---

## Programme 3 : Générateur de mot de passe
### Description :  
Dans ce programme, il y a plusieurs outils : 
- Un outil qui permet de créer des mots de passe robustes
- Un historique des 5 derniers mots de passe générés
- Affichage de conseils pour créer un mot de passe robuste
### Fonctionnement :  
1. Vous pouvez revenir sur l'interface principale directement via les onglets en haut de la page
2. Vous appuyez sur le bouton programme 3 dans l'interface principale, une fenêtre va s'ouvrir
3. Sur celle-ci, il y aura plusieurs fonctionnalités :
- Quand vous appuyez sur le bouton générer, ça génère un mot de passe robuste de 12 caractères qui mélange (chiffres, Mascule, Minuscule et chiffres)
- Chaque fois que vous appuyez sur le bouton, un nouveau mot de passe se génère
- Tous les mots de passe qui se sont affichés s'affichent dans l'historique en dessous du bouton du plus ancien au plus récent (ce sont les 5 derniers mots de passe générés)
- Vous avez aussi un bouton "Afficher Conseils" qui vous affiche des conseils pour créer un bon mot de passe



---

## Programme 4 : Analyseur de mot de passe
### Description :  
Ce programme évalue la robustesse des mots de passe en fonction de plusieurs critères (longueur, complexité, caractères utilisés).
Avec trois niveaux de robustesse : 
- Faible
- Moyen
- Fort
### Fonctionnement :  
1. Vous pouvez revenir sur l'interface principale directement via les onglets en haut de la page
2. Vous appuyez sur le bouton programme 4 dans l'interface principale, une fenêtre va s'ouvrir
3. Sur celle-ci, il y aura plusieurs fonctionnalités :
- Vous pouvez entrer le mot de passe que vous souhaitez vérifier la robustesse dans la zone de saisie
- appuyez sur le bouton "Analyser", et le programme vous dira le niveau de robustesse de votre mot de passe 
- Vous avez aussi un bouton "Afficher Conseils" qui vous affiche des conseils pour créer un bon mot de passe

---


