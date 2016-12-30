# city_match

## Description
En entrant un code postal, ce site va retrouver le nom de la ville correspondante.

Vous voulez trouver le nom d'une ville Française via un code postal ?
Allez sur le site [VirgilePostal](http://virgilepostal.esy.es/)

## Réalisation

Pour le design du site, j'ai choisi le thème [Eventually](https://html5up.net/uploads/demos/eventually/)
sur [Webdesignertrends](http://www.webdesignertrends.com/2015/07/12-templates-html5-css3-gratuits-a-telecharger/).

Utilisation d'une [API](http://www.cp-ville.com/) qui permet de faire correspondre un code postal au nom de sa ville
dans le fichier [main.js](./assets/js/main.js)
#### Requete API
	$.getJSON("http://www.cp-ville.com/cpcom.php?jsoncallback=?", { cpcommune:$code_postal });
	
