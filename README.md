# AdsPublisher
<table><tr><td>
<b>Resume</b>
<br>I have developed my website using PrestaShop and am exploring additional sales channels. To this end, I created AdsPublisher. This tool retrieves products from my website and displays them in a web interface, allowing me to construct a list of ads for publication on Leboncoin. After configuring the target website and preparing the ads, AdsPublisher posts each ad individually, mimicking human behavior.
<br>
<b>Keywords:</b> <i>Python, Django, Selenium, Prestashop API</i>
</td></tr></table>

## Context
Que ce soit les nouveaux commerces en ligne ou même les commerces bien établis, cherchent à avoir plus de canaux de vente à part leur site principal. Gérer des annonces sur plusieurs plateformes n'est pas chose facile et consomme beaucoup de temps. Ayant sa base de données sur son site principal, on aimerait la récupérer et choisir quelles annonces republier sur une autre plateforme, ic en l'occurence _Leboncoin_ pour moi.

## Comment ça fonctionne
Dans une utilisation classique de *AdsPublisher*, il suit les étapes suivantes:
- Télécharger les annonces depuis le site principal (source);
- Enregistre chaque annonce dans un dossier, avec un fichier json contennat tous les informations nécessaires avec les images du produit;
- Construire la liste des annonces à publier sur le site cible;
- Éditer le fichier de configuration du compte utilisateur sur le site cible;
- Lancer la publication des annonces.

![image](https://github.com/elho2007/AdsPublisher/assets/34011591/0f3c14b5-b814-4349-9239-2f0aed119338)

**Remarque:**
L'utilisateur a l'accès aux différentes fonctions du script, il n'est obliger de les exécuter dans l'ordre.

## Fonctionnalités
- Les annonces 

ensuite il regarde les nouvelles annonces en se basant sur l'historique de sa surveillance. Il fait ensuite un filtrage et élémination des annonces non pertinantes en se basant sur des mots clés configurés. Il détermine également les annonces urgentes à voir en se basant sur des critères définis par l'utilisateur. S'il y a des annonces susceptible d'intéresser l'utilisateur, une alerte est envoyé sur télégram contenant les informations essentielles de ces annonces et un lien vers une page web qui détaille.

![image](https://github.com/elho2007/AdsCrawler/assets/34011591/24573946-f815-464c-8178-076dd7201d9b)


### À venir
- Une vidéo démonstratif,
- Plus de détails sur le développement de *AdsCrawler*,
- Personalisation (alerts, sites, mots clées, etc..),
- Possibilités et idées d'utilisation.
