# AppLove

Para completar tu web **AppLove** hemos creado este repositorio boilerplate (plantilla inicial) con todos los recursos que necesitas. Esto incluye las imágenes y algunas clases CSS que ya hemos creado para ti :)

## Empieza por realizar un fork y clonar este repositorio

1. Debes realizar un **fork** de este repositorio.

2. Luego deberás **clonar** este repositorio boilerplate, después crear un repositorio remoto en tu cuenta de `GitHub` y vincular tu local con tu remoto. Para esto, sigue los siguientes pasos:

    1. Crea un repositorio remoto en tu cuenta de `GitHub` con el nombre del ejercicio (tip: recuerda usar "New Repository")
    2. Obten el URL del repositorio boilerplate haciendo clic en el _botón verde_ "clone or download"
    3. En tu línea de comandos, clona el repositorio boilerplate y vincúlalo con tu repositorio remoto. Para hacer esto debes usar los comandos `git clone`, `git remote add` y `git push` que se muestran a continuación:

        ```js
        ~ git clone <URL del repositorio _boilerplate_ de Laboratoria>
        ~ git remote add origin <URL del repositorio remoto que creaste en tu cuenta de GitHub>
        ~ git push origin master
        ```

## Objetivo Final

El reto consiste en maquetar la web **AppLove**, este es el resultado final:

![AppLove](https://fotos.subefotos.com/1edc0aab51f1d624da4a24ab86129d87o.png)

## Detalles adicionales

- Encontrarás un archivo base `index.html` el cual contiene una estructura inicial sobre la que deberás completar tu proyecto.

- En la carpeta `css` tendrás un archivo base `main.css` donde hay clases reutilizables, quiere decir que dichas clases pueden ser usadas más de una vez. Por ejemplo:

    ```CSS
    .text-uppercase {
      text-transform: uppercase;
    }
    ```

    >Si usamos la clase `.text-uppercase` en algún texto lo que hará es ponerlo en mayúsculas. De esta manera podrás reutilizar esta clase varias veces. **No olvides enlazar tu archivo `CSS` a tu `HTML`**.

- El `header` tiene que estar **estático**, como se muestra en la siguiente _imagen gif_:

![AppLove-gif](https://fotos.subefotos.com/da068e44cb72b36ba6c4458130c00185o.gif)

- Dentro de la carpeta `assets` se encuentra la carpeta `images` donde encontrarás todas las imágenes necesarias para completar tu proyecto.

- Deberás **actualizar el archivo `README.md`** explicando el contenido de tu repositorio.

- El tipo de fuente a utilizar será `Raleway`.

## Consideraciones generales

Este reto sera evaluado sobre lo siguiente:

- Pixel perfect (replicar el diseño con exactitud)
- Nombramiento de clases, id, etc
- Indentación
- Estructura de tus archivos
- Archivo `README.md` actualizado y correctamente redactado
- Uso de comentarios para hacer tu código más legible

**Modificaciones que se hicieron en el HTML y CSS**

- Se llamó a la fuente para que modificara el texto de la página.

- En el HTML se usaron id y clases para cada elemento e invocarlos en el CSS de manera más sencilla.

- Se fue modificando desde la barra principal (container que se encuentra dentro de la etiqueta header en el body),
donde se utilizaron las posiciones relativas, float, las mayúsculas (text-transform), y elementos como height y margin,
para acomodar cada parte de la barra. (Aún no se logra generar la posición estática).

- Luego se trabajó con la segunda sección, donde se posicionó la imagen y los textos, los cuales debían ir delante de la imagen.
También se utilizó la posición relativa, float, alineación de texto, mayúsculas, tamaño de texto, entre otros elementos para
acomodar cada fragmento de texto, más la generación del botón verde.

- Posteriormente, se trabajó en el container 2, donde se usaron los mismos elementos que en las secciones anteriores. En esta
sección, se usaron divs dentro de otros divs para hacer más práctico el llamado de los elementos en el CSS y quedaran alineados,
junto con el color de fondo rosado que se requirió (background-color).

- Después, se trabajó en la sección de las imagenes junto con textos, donde a las imagenes se les colocó clases para que se
pudieran acomodar de mejor manera con el CSS. Igualmente,se usaron divs para encapsular, por un lado, las imagenes de tres en
tres, y por otro, los textos que también van de tres en tres (usando la etiqueta strong para negrita, y span que es inline). En
el CSS se usaron similares elementos que en las secciones anteriores para facilitar en maquetado de la página.

- Para finalizar, se trabajó en la última sección, donde se le colocó fondo, color a las letras, y otros elementos que se usaron
en secciones anteriores, logrando de esta forma, lo que se pidió.

**Consideraciones**

- Las mayores dificultades de este trabajo, recaen en el buen uso de las unidades de medida, ya que una mal utilizada, desconfigura
toda la página.

- El before y after los traté de usar, pero me generaron conflictos con las unidades de medida, por lo tanto, no los use.
(Requiero especialización con el uso de esos elementos).

- Otra gran dificultad que aún no puedo solucionar, es la barra estática. A pesar que en trabajos anteriores logré aquel cometido,
no pude lograrlo aquí a pesar de utilizar position fixed. (Requiero especialización para dar solución a ese requerimiento).

- Igualmente, trabajé con outline para ver los margenes que iban adquiriendo cada item que iba incorporando al HTML, porque ello
permite observar margenes e ir estableciendo medidas.
