# Comment intégrer un nouveau programme d'enseignement à pySéquence ? #


Selon la nature du programme à intégrer, créer une copie d'un des fichiers "référentiel" existant :
  * Ref\_SSI.xls : s'il n'y a pas de tronc commun ni d'option à cet enseigmentmet
  * Ref\_STI2D-ETT.xls et Ref\_STI2D-AC.xls : dans le cas contraire

Modifier le contenu du classeur en adéquation avec le programme à intégrer.

  * Attention à bien respecter les consignes et informations figurant dans les zones de commentaire.
  * Ne pas modifier les cellules protégées
  * Ne pas utiliser de caractères spéciaux, ni de retour à la ligne
  * Ne pas lancer pySéquence avant d'avoir totalement complété le fichier

### Cas particulier des programmes avec Tronc-commun et Options ###
Le programme du tronc commun et ceux des options doivent figurer dans des fichiers différents, reliés entre eux de la manière suirante :

![http://pysequence.googlecode.com/svn/trunk/images_aide/Ref_TC-Options.png](http://pysequence.googlecode.com/svn/trunk/images_aide/Ref_TC-Options.png)

Afin que la relation de Tronc-commun / Options apparaisse dans pySéquence, il faut leur donner le même nom de famille :

![http://pysequence.googlecode.com/svn/trunk/images_aide/Ref_Famille.png](http://pysequence.googlecode.com/svn/trunk/images_aide/Ref_Famille.png)

## Intégration à pySéquence ##
L'intégration à pySéquence est automatique dès lors que le fichier Ref\_xxx.xls se trouve dans le dossier "Referentiels".
Lors du lancement de pySéquence, si tout s'est bien passé, un nouveau fichier Ref\_xxx.xml est généré.
Dans le cas contraire, ou bien si pySéquence ne se lance plus et renvoie une erreur, c'est que le fichier Ref\_xxx.xls n'a pas pu être correctement interprété. Merci de [contacter les auteurs](Contact.md) dans ce cas.

## Publication ##
Si vous avez réalisé un référentiel (qui fonctionne), et afin de rester dans l'esprit "logiciel libre" de pySéquence, merci de partager votre travail afin d'en faire profiter tout les utilisateurs de pySéquence.
Pour cela, il suffit d'envoyer le fichier Ref\_xxx.xls au auteurs, qui le publieront sur l'espace de [téléchargement](https://drive.google.com/folderview?id=0B2jxnxsuUscPX0tFLVN0cF91TGc&usp=sharing#list).