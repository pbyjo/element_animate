## Controlar animaciones 💿📀
* 
	> Podemos controlar el estado de la animación. Esto podemos hacerlo por medio de botones que disparen la función que queremos. Los métodos que tenemos disponibles podemos verlos en la variable 'animate' en la consola.

	EJ:

```javascript
const animation = $element.animate(
keyFrames, animateProperties)
	
const $playButton = document.getElementById('play');
const $pauseButton = document.getElementById('pause');
const $stopButton = document.getElementById('stop');
const $reverseButton = document.getElementById('reverse');

$playButton.addEventListener ('click', () => {
	animation.play();
});
$pauseButton.addEventListener ('click', () => {
	animation.pause();
});
$stopButton.addEventListener ('click', () => {
	animation.stop();
});
$reverseButton.addEventListener ('click', () => {
	animation.reverse();
});
```

	