# :biking_man:  BlaBlaBike (nom pas encore défini ) : Location de vélo entre particuliers  :biking_woman:

## 1. Présentation :film_projector:

À notre époque, l’environnement est devenu un des sujets cruciaux de débats dans notre société. 
En effet, les conséquences de notre activité sur la vie de la planète sont de plus en plus désastreuses et en particulier d’un point de vue de la  surconsommation et de la quantité d’émission de CO2 . 
De ce constat, deux questions nous sont venus : Comment contribuer à la réduction d’émission de CO2 par nos transport au quotidien ?
Et comment éviter de multiplier la production et la consommation de nouveaux moyens de transport ?

### C'est ici que :biking_man: BlaBlaBike :biking_woman: intervient en proposant à toute personne possédante déjà un vélo mais ne l'utilisant pas h 24 de louer à d'autres personnes pour un petit prix.
### Résultat : moins de CO2 :no_entry_sign: , moins de consommation :recycle: = une planète plus propre !!!:earth_americas:

## 2. Parcours utilisateur :raising_hand:

* Parcours simple d'utilisation . 

  * L'utilisateur peut soit proposer son vélo à la location, soit louer un vélo proposé.

  * L'utilisateur doit créer un compte utilisateur pour louer ou proposer un 	vélo.

  * L'utilisateur qui loue doit rentrer les informations classiques d'identité(nom, prénom....),des infos de sécurité obligatoire (mail, password, téléphone), télécharger sa pièce d'identité, numéro de série du vélo.

  * L'utilisateur qui loue un vélo doit rentrer les informations classiques d'identités(nom, prénom.....),des infos de sécurités obligatoires (mail, password, téléphone), télécharger sa pièce d'identité.	

  * On peut consulter les offres sans compte utilisateur.	

  * Possibilités de souscription rapide d'assurance chez JeanHuss Assurance.	

  * L’utilisateur voit ses locations proposées ou prises.

  * Les utilisateurs peuvent communiquer entre eux par messages privés.

  * Les utilisateurs peuvent noter les autres utilisateurs.

## 3. Concrètement et techniquement :nerd_face:

### 3.1. Base de données

* User : Une base de donnée utilisateur contenant tous les profils disponibles sur l'appli.
* Rent : Une base de donnée contenant les différentes locations.
* Bike : Les vélos disponibles sur le site.
* City : Les différentes villes ou sont disponibles les vélos et utilisateurs (Uniquement Rennes pour le départ de l’appli).

*Et d’autres en fonctions des options disponibles à la sortie de l’appli*

### 3.2. Front

* #MobileFirst
* Utilisation de Bootstrap.
* kit UI/UX

* navbar 
* molécule de recherche
* organisme d’inscription
* organisme de souscription 
* organisme de paiements
* etc...

*Pleins d’autres choses qui viendront à la conception de la charte graphique et de la maquette plus précise du site*


### 3.3. Backend

* Ruby
* Ruby on Rails
* Mailers
* gem Device pour la sécurité client et la registration.
* gem Stripe pour les paiements.

*Pleins d’autres choses qui viendront à la conception de la charte graphique et de la maquette plus précise du site*

### 3.4. Mes besoins techniques

**Husain et moi nous avons actuellement de bonnes bases sur tout ce qui y a était vu durant la formation : Ruby,ROR,HTML,…**

**Nous avons bosser durant toute la formation pour progresser et s’éclater avec ces langages nous sommes donc en recherches de partenaires dans le même état d’esprit que nous et qui veulent contribuer à un super projet !!! :smile: :muscle:**

## 4. La version minimaliste mais fonctionnelle qu'il faut avoir livré la première semaine

* UI kit / front minimum 
* Création de compte/location possible
* Chercher des Location possible
* Devise installé avec la partie mailer en place 
* Paiements en place 

## 5. La version que l'on présentera aux jury

* Front finaliser et app fonctionnelle et responsive.


## 6. Notre mentor

**Thibault leygnac Web Designer/Da freelance**
Rencontrez sur la ville de Rennes.Il va nous permettre d'organiser nos semaines,d'énormes conseils sur le parcours utilisateur,le design et la charte graphique de notre site.
