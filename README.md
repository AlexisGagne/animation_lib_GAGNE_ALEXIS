animation_lib_GAGNE_ALEXIS
==========================

TP1 Animation 


###Appliquer l'animation sur un objet
Les animations de la librairie sont sous forme de classes. Pour appliquer une animation à un élément, 
vous n'aurez seulement qu'à appliquer la classe à l'élément désiré.
Par exemple: 
```
<div class="animation01"></div>
```


###Tester l'animation
Pour tester les animations, je vous invite à ajouter également la classe "square". Vous aurez donc un aperçu de
l'animation appliqué à un carré.
Par exemple: 
```
<div class="animation01 square"></div>
```


###Les composantes de l'animation

####Les paramètres
Les animations ont deux composantes principales, soit la classe et les keyframes. Pour la classe, vous trouverez 
les attributs suivants:

```
  animation-name: le nom de votre animation
  animation-duration: la durée de l'animation
  animation-iteration-count: le nombre de répétition de l'animation
  animation-direction: le sens de lecture de l'animation
  animation-timing-function: le rythme de l'animation
  animation-fill-mode: états de votre animation
  animation-delay: délai avant le départ de l'animation
```

C'est dans ces paramètres que vous pourrez modifier une partie de vos animations. Pour modifier les caractéristiques
visuelles affectés par l'animation, ce sera dans les keyframes que vous pourrez effectuer ces modifications.

####Les keyframes
Les keyframes sont les étapes de votre animation. Les keyframes vous permettent de gérer votre animation en fonction 
du pourcentage écoulé de l'animation. Le code d'un keyframe ressemble à ceci:

```
  0% {
  transform: translateX(-100px) rotate(45deg) scale(1.5);
  background-color: #666;
  border-radius: 0px;
  opacity: 0.5;
  }

  100% {
  transform: translateX(-500px) rotate(90deg) scale(3);
  background-color: #292929;
  border-radius: 5px;
  opacity: 1;
  }
```



MERCI!
