TP4 R512 - Campus Cloud
======================
Prototype d'application Web responsive : HTML/CSS/JS sans dependances externes.

FONCTIONNALITES
- Interface adaptee smartphone/ordinateur
- Ajout et suppression de taches
- Sauvegarde LOCALE via localStorage (pas de base cloud)
- Indication de l'etat en ligne du navigateur (pas de mesure de disponibilite AWS)

DEPLOIEMENT AWS AMPLIFY
1. Ouvrir AWS Console > Amplify (region eu-north-1)
2. Create new app / Deploy without Git
3. Choisir un deploiement manuel par fichier ZIP
4. Televerser TP4_CampusCloud_Amplify.zip
5. Deployer et tester l'URL HTTPS depuis PC et telephone

POUR LE RAPPORT
Ce deploiement montre une application WEB adaptee aux mobiles, mais ne constitue
pas une application mobile native iOS/Android ni un service cloud backend.
Pour completer les services mobiles : ajouter une authentification Cognito
et/ou une API avec stockage cloud; surveiller ensuite avec les services adaptes.
