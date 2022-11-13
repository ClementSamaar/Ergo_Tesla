# Rapport projet web front-end <br> <sub>*Interface application Tesla*</sub>
Pour ce projet, j’avais choisi de réaliser la page d’accueil, la page concernant les statistiques de recharge et la page permettant de contrôler le véhicule à distance. 
Par faute de temps, je n’ai pas réalisé la page de contrôle. 
## HTML
À propos de l’HTML, j’ai choisi de massivement utiliser des balises ```section``` afin de représenter un élément qui contient au moins deux contenus. 
Par exemple, l’élément indiquant l’état de la batterie de la voiture qui est composé d’une balise ```progress``` et d’une balise ```p``` est une section. 
Bien sûr, j’ai bien veillé à mettre un ```header``` au début de chaque section. Lorsque l’affichage d’un ```header``` n’est pas utile, je lui assigne la classe ```hidden``` qui 
permettra de cacher le contenu. J’ai aussi veillé à respecter la hiérarchie des titres. Enfin, en ce qui concerne les images, j’ai essayé de déterminer 
au mieux l’utilité de l’attribut ```alt``` en fonction du contexte de l’image. Mon objectif était d’apporter des informations complémentaires à une image si besoin, 
mais aussi de ne pas surcharger le site d’informations inutiles.
## CSS
Pour réaliser le style de ce site, j’ai choisi de principalement utiliser ```grid``` et ```flex```. 
J’aurai aussi apprécié découvrir un framework ou un préprocesseur tel “SASS”, j’ai préféré revoir les bases du CSS et d’apprendre à utiliser ```grid``` qui était 
totalement nouveau pour moi. Même si l’apprentissage a été complexe au début, je me suis rapidement acclimaté à ce type de display et je pense le réutiliser à l’avenir. 
Effectivement, ```grid``` est très pratique surtout s’il est nécessaire de réaliser une interface responsive avec plusieurs dispositions. Malgré cela, c’est une solution
que j’ai trouvée assez complexe à mettre en place, car il faut positionner chaque élément de manière unitaire. Pour les tailles, j’ai choisi d’utiliser le pourcentage et 
les ```em```. Ces deux unités sont très utiles pour réaliser des interfaces responsive. Le ```em``` en particulier est très pratique parce qu'on peut simplement modifier toutes 
les tailles définies par cette unité en déterminant le ```rem```. 
