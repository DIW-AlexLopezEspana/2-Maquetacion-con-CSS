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

/------- PAGINA LOGIN -------/

La página del login está separada en 2 partes generales y despuees interna mente esta separada en 3.

La primera parte y la que mas llama la atención es el sidebar que se ha hecho mediante un float para poderlo mostrar,
también se le han metido separaciones para que de la sesación de que está flotando la imagen. para ello se ha usado
las siguientes clases (.sidebar, .sidebar img)

La segunda parte es la sección de datos donde aquí moto parte del formulario, la cual tiene que rellenar el usuario, esta aprte esta dividida en
muchas subpartes.

Que son las siguientes: - Un form el cual esta con un float a la izquierda y se ha ido jugando con los padding y margin para poder centrar sus datos, este lo compone
el input de email, el imput de contraseña el boton de enviar y el texto de si se te ha olvidado la contraseña

    - Otra parte sería la separación para inicio manual y la otra parte seria la de inicio con google, con apple o para crearte una cuanta, esto
        se ha separado mediante un div que contiene varios hr, los cuales uno se ha puesto con float right y otro con float left.

    - La penultima parte está separa en varios div segun los botones que nos han hecho falta y para separar un poco más el codigo por comodida.
        Esta parte se han usado los float za la izquierda y se han ido jugando con los padding y los margin para centrar tanto su contenido como
        el boton en sí. y también el logo de la empresa, ya que nos interesa que sea una de las cosas que el usuario que quede antes de irse de la pagina.

    - La ultima parte es el footer que se ha puesto centrado para que quede toda la pagina simetrica y que no estuviera a un lado.

/------- PAGINA Register -------/

La página del register está separada en 2 partes generales y despues interna mente esta separada en 3.

La primera parte se ha quereido diferenciar un poco del login para que no sea tan monotono, se ha querido
que el header se metiera por debajo del contenido para que diera la sensación que es más importante los datos que se tienene que rellenar
a la imagen.

La segunda parte es la sección de datos donde aquí moto parte del formulario, la cual tiene que rellenar el usuario, esta aprte esta dividida en
muchas subpartes.

Que son las siguientes: - Un form el cual esta con un float a la izquierda y se ha ido jugando con los padding y margin para poder centrar sus datos, este lo compone
el input de email, el imput de contraseña,el de repetir contraseña, el boton de enviar y el texto de si se te ha olvidado la contraseña

    - Otra parte sería la separación para inicio manual y la otra parte seria la de inicio con google, con apple o para crearte una cuanta, esto
        se ha separado mediante un div que contiene varios hr, los cuales uno se ha puesto con float right y otro con float left.

    - La penultima parte está separa en varios div segun los botones que nos han hecho falta y para separar un poco más el codigo por comodida.
        Esta parte se han usado los float a la izquierda y se han ido jugando con los padding y los margin para centrar tanto su contenido como
        el boton en sí. y también el logo de la empresa, ya que nos interesa que sea una de las cosas que el usuario que quede antes de irse de la pagina.

    - La ultima parte es el footer que se ha puesto centrado para que quede toda la pagina simetrica y que no estuviera a un lado.
