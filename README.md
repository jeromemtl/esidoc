# Générateur de bibliographie et de critique
## Qu'est ce que c'est ?
Un [générateur de bibliographie](https://jeromemtl.github.io/esidoc/bibliographie.html) et un [générateur de critique](https://jeromemtl.github.io/esidoc/critique.html).  
Je vous invite à visiter [le blog](https://fenetresur.wordpress.com/2020/03/01/esidoc-v2-comment-integrer-les-generateurs-de-critique-et-de-bibliographie/) de @fenetresur pour avoir plus de détails.
## Pourquoi avoir fait un embranchement ?
Mon idée de départ était de donner un look un peu plus "à la e-sidoc" à ces générateurs.  
Finalement, je me suis laissé emporter...
## Comment intégrer un générateur dans e-sidoc ?
* Connectez vous en administrateur à e-sidoc en allant à l'URL [administration.esidoc.fr](https://administration.esidoc.fr/) ou en utilisant [ce userscript](https://github.com/jeromemtl/e-sidoc_userscript).
* Allez dans le menu ["Menu et rubriques"](https://administration.esidoc.fr/portail/arborescence).
* Créez un espace ou une rubrique.
* Cliquez sur le bouton "Source" dans le champ "Description".
* Copiez et collez le code ci-dessous selon le générateur dans le champ "Description".

**Bibliographie**
```
<div style="padding-top:110%; position:relative"><iframe src="https://jeromemtl.github.io/esidoc/bibliographie.html" style="position:absolute;top:0;left:0;width: 100%;height: 100% !important;max-width: 100% !important;border:0;"></iframe></div>
```

**Critique**
```
<div style="padding-top:110%; position:relative"><iframe src="https://jeromemtl.github.io/esidoc/critique.html" style="position:absolute;top:0;left:0;width: 100%;height: 100% !important;max-width: 100% !important;border:0;"></iframe></div>
```
