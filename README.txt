/------- PAGINA PRINCIPAL -------/

La página principal está dividida en 4 partes (de momento). 

La primera es el header, donde tengo la imagen del logo a la izquierda con un float left. Tiene el fondo blanco y 
los bordes de abajo supuestamente deberían ser redondos, pero no me hace caso. Es un cambio que implementaré para el grid.
A la derecha hay dos elementos más, definidos con un float right. Estos son un texto 'Ofrecer Servicios' (.texto-servicios) y
una imagen que actúa de icono de perfil de usuario (.icono-perfil y .icono-perfil .profile-icon).

La segunda parte es la sección 1, o hero. Se trata de el espacio con fondo azul claro que contiene el eslogan y el buscador.
El eslogan es un titulo h2 (.hero h2) y el buscador un contenedor que agrupa 3 elementos; la barra gris de detrás (.search-bar), el input 
donde el usuario escribe (.search-bar input) y un botón (.search-bar button). El input está situado a la izquierda del container con un 
float left, y el botón a la derecha con un float right.

En la tercera parte tenemos una sección 3 o container que engloba los servicios por los que el usuairo va a poder navegar.
El .container define un fondo blanco, unos bordes redondeados, el texto alineado al centro... Después, he separado cada conjunto de servicios 
en courses, conteniendo 3 course cada uno de ellos. Para los .courses he definido que esten float left y con una anchura del 100% para que ocupen
toda la página. Para cada .course hay definido un ancho, borde, borde redondeado, padding, margin... Cada elemento de un course esta modificado. 
La imagenes para que no den problemas con su posición y tamaño (.course img), los títulos un poco mas grandes y en negrita (.course h3), los textos
con un color ligeramente mas gris y alineados a la izquierda (.course p) y un pequeño agrupador de los dos elementos de abajo del course; el precio
y un botón. El precio a la izq con un float left y el boton a la der con un float right. Por último una pequeña función (por llamarla así) que se 
encarga de cambiar el color del fondo del botón cuando el usuario pasa el ratón por encima (.course-footer button:hover).

Por último un pequeño footer con información breve de la empresa y propietarios (footer).