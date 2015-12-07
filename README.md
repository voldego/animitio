# Animitio:
animitio is a javascript library that use [animate.css] (https://daneden.github.io/animate.css/) to set animation in selected html elements.

#Usage:
1. include both the stylesheet animate.css and the javascript file animitio.min.js to your document
  
  ```html
<head>
       <script src="animitio.min.js"></script>
       <link rel="stylesheet" href="animate.css">
</head>
```
2. in the body add a script tag and select the element that you want to be animated with the `Id() function`  :

  ```html
<body>
       <div id="test">the element test</div> 
       <script>
            Id('test').bounce(); // we used the bounce animation & Id() with Uppercase i
       </script>
       
</body>
```

#Events commands:
Event | Animitio command
------------ | -------------
onclick | `Id('').click(function(){})`
ondblclick | `Id('').dblclick(function(){})`
onmousedown | `Id('').mdown(function(){})`
onmouseup | `Id('').mup(function(){})`
onmouseover | `Id('').mover(function(){})`
onmouseout | `Id('').mout(function(){})`
onmousemove | `Id('').mmove(function(){})`
onkeydown | `Id('').keydown(function(){})`
onkeyup | `Id('').keyup(function(){})`

#available animations:
to set the animation you have to use the function `Id('').bounce()` and change `bounce` with one of the animation.css classes:
* `bounce`
* `flash`
* `pulse`
* `rubberBand`
* `shake`
* `headShake`
* `swing`
* `tada`
* `wobble`
* `jello`
* `bounceIn`
* `bounceInDown`
* `bounceInLeft`
* `bounceInRight`
* `bounceInUp`
* `bounceOut`
* `bounceOutDown`
* `bounceOutLeft`
* `bounceOutRight`
* `bounceOutUp`
* `fadeIn`
* `fadeInDown`
* `fadeInDownBig`
* `fadeInLeft`
* `fadeInLeftBig`
* `fadeInRight`
* `fadeInRightBig`
* `fadeInUp`
* `fadeInUpBig`
* `fadeOut`
* `fadeOutDown`
* `fadeOutDownBig`
* `fadeOutLeft`
* `fadeOutLeftBig`
* `fadeOutRight`
* `fadeOutRightBig`
* `fadeOutUp`
* `fadeOutUpBig`
* `flipInX`
* `flipInY`
* `flipOutX`
* `flipOutY`
* `lightSpeedIn`
* `lightSpeedOut`
* `rotateIn`
* `rotateInDownLeft`
* `rotateInDownRight`
* `rotateInUpLeft`
* `rotateInUpRight`
* `rotateOut`
* `rotateOutDownLeft`
* `rotateOutDownRight`
* `rotateOutUpLeft`
* `rotateOutUpRight`
* `hinge`
* `rollIn`
* `rollOut`
* `zoomIn`
* `zoomInDown`
* `zoomInLeft`
* `zoomInRight`
* `zoomInUp`
* `zoomOut`
* `zoomOutDown`
* `zoomOutLeft`
* `zoomOutRight`
* `zoomOutUp`
* `slideInDown`
* `slideInLeft`
* `slideInRight`
* `slideInUp`
* `slideOutDown`
* `slideOutLeft`
* `slideOutRight`
* `slideOutUp`
