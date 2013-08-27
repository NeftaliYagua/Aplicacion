---
layout: default
title: OpenHackVE - Su ciudad?
---

## No encuentra su ciudad?

Nos encantaría comenzar OpenHackVe en tantas ciudades como sea posible. Este sitio está destinado a facilitar el inicio de nuevos grupos OpenHack, pero no pretende en realidad "ejecutar" o "RSVP" para grupos. Si desea añadir su ciudad, esto es lo que debe hacer:

1. Puede comenzar "forkeando" y clonando el [openhack.github.com](https://github.com/OpenHackVE/openhackve.github.com) repositorio.
2. Instala Ruby (¡Contundente!); En la cónsola: `su apt-get install ruby1.9.1`, `sudo apt-get install rubygems`, `gem install bundler; bundle`
3. Luego, en cónsola igual: `rake city NAME=Nombre_ciudad`.<br />Si su ciudad es: "Caracas, Distrito Capital" escriba: `rake city NAME='Caracas, Distrito Capital'`. Esto creará un directorio con el nombre `caracas` con un archivo: `index.markdown` que será para tú ciudad. __Adicional__: Para obtener una ubicación en el mapa, agrega más detalles. Ejemplo: `rake city NAME='Caracas, Distrito Capital' ADDRESS='Calle 1, avenida 2'`
4. Edita el archivo `index.markdown` con la información que desees de tú ciudad. Ejecuta: `rake` para ver el sitio en acción y ve a: `http://localhost:4000`.
5. También edita el archivo `_config.yml` con el nombre correcto de tú ciudad y algunas coordenadas.
6. Haz "commit" con tus cambios, luego "push" al "fork", y envía un "pull request" para el repositorio. Una vez aceptado, lo añadiremos al repositorio principal para que pueda actualizar la página de tu ciudad en cualquier momento.

Eso es todo! Si deseas recibir ayuda en el proceso puedes abrir un [issue](https://github.com/OpenHackVE/openhackve.github.com/issues) y hacernos preguntas.

### Recuerda nuestra cuenta en Twitter

Si necesitas alguna ayuda, tienes algún comentario, pregunta, duda, problemas, lagunas mentales... 
Aquí estamos. :)

 [@OpenHackVE](https://twitter.com/OpenHackVE).

#### Acá puedes añadir las redes sociales para su ciudad.

Por ejemplo, la de nosotros. :)

* [OpenHackVe](https://twitter.com/OpenHackVe) para Venezuela.
* [OpenHackCaracas](https://twitter.com/OpenHackCaracas) para Caracas.
* etc.

#### Perfil

* Para agregar en la "cabezera" de tú ciudad una foto:
	 Foto [`Vista_PlazaVenezuela.jpg`](/images/Vista_PlazaVenezuela.jpg).


#### Para el diseño

* Background: Usa [`tile.png`](/images/tile.png).  Asegúrate que tengas la opción "Tile background" habilitada.
* Background color: `#ddd`
* Link color: `#69b373`
* Overlay: White


### ¿Algo más? ¡Eso es todo! 
