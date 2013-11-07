Personalización de Emmet
=====================

En Sublime Text 2 sirve para:

 * Cerrar etiquetas con comentarios que incluyan la clase que ésta lleva.
 * Sentirse bien.
 * No perderse.

______________

Estas líneas deben pegarse en el archivo `Emmet.sublime-settings`.
Para acceder a este archivo, en OS X, al abrir **Sublime Text** debe irse a `Preferences > Package Settings > Emmet > Settings - User `.

Luego de guardar, Emmet debe hacer que algo así:

	.hola>ul.laLista>li.item*3
	
Quede así:
	
	<div class="hola">
  		<ul class="laLista">
    		<li class="item"></li><!-- .item -->
    		<li class="item"></li><!-- .item -->
    		<li class="item"></li><!-- .item -->
  		</ul><!-- .laLista -->
	</div><!-- .hola -->
	
![Pikachu feliz](http://i.imgur.com/ZyPBv.gif)
