**UD1-UD2 · Tarea de evaluación: Mi proyecto web (1.ª entrega · HTML + XML)**

## Reto 1 qué he hecho?
Nombre: xinyi ye
Usuario de GitHub: yexinyi0609-nini
Tema elegido: un guía de juego sobre Stardew Valley
Por qué lo he elegido (3-4 líneas con tus palabras): porque quiero crear una guía de juego ordenador para todo el mundo , sobre todo para las personas que están en China , ya que ellos no pueden entrar en la página oficial de Stardew Valley para buscar la guía.



## Reto 2 qué he hecho en esta entrega?
He creado una página web sobre mi juego favorito, con su título, dos párrafo de presentación y una lista de información sobre el juego.
He añadido un archivo XML con los datos de los aldeanos
He subido a GitHub con vaios commit.

## Reto 3 qué he hecho?
He creado los datos personales de cada aldeanos con atributos id único y sus regalos favoritos.

## Reta 4, qué he hecho?
He revisado los error que había en index.html, he terminado de rellenar los datos de los aldeanos en datos.xml. Web se puede abri correctamente con Live Server y con error 0.


**UD3 · Práctica: Estructura HTML de mi proyecto web (de una página a un sitio)**
*palabra del día: contexto*

## Reto 1 - «UD3 · Estructura HTML»
-- Metadatos incompletos: el título no es Inicio|nombre , el formato es incorrecto y falta meta description (una frase tuya que resuma la página), keywords (al menos 4 palabras de tu tema) y author (tu nombre).

-- Falta la estructura de bloques div. no hay div encabezado, ni divs para cada caítulo, ni comentarios para cada bloque ni sangría uniforme.

-- Faltan varios elementos obligatorios: hr, blockquote, pre, un pie con(&copy) y otras entidades.

## Reto 4 - Mapa del sitio

Mi página web trata sobre el videojuego Stardew Valley. El objetivo es ofrecer información sobre el juego, sus aldeanos, los cultivos y la gestión de la granja.

|    Ficher     |          title            |                           Qué contiene                                 |
|---------------|---------------------------|------------------------------------------------------------------------|
|   index.htm   | Inicio   \| Guía de juego | Presentación del juego, información general y opinión personal.        |
| aldeanos.html | Aldeanos \| Guía de juego | Información sobre los aldeanos, sus nombres y sus regalos favoritos.   |
| cultivos.html | Cultivos \| Guía de juego | Información sobre los cultivos, las estaciones y las cosechas.         |
| granja.html   | Granja   \| Guía de juego | Información sobre la granja, los animales y las actividades del juego. |



### Validación de las páginas HTML

He utilizado el validador W3C para comprobar la estructura de las cuatro páginas de mi sitio web.

|    Página     |              Errores encontrados               |                       Correcciones realizadas                       |
|---------------|------------------------------------------------|---------------------------------------------------------------------|
| index.html    | 0 errores                                      | No ha sido necesario realizar correcciones.                         |
| aldeanos.html | 0 errores                                      | No ha sido necesario realizar correcciones.                         |
| cultivos.html | He cerrado </body> antes, en la línea 20.      | Corregido, movido a la lína 123.                                    |
| cultivos.html | Encoding not supported.                        | Cambié charset="viewport" por name="viewport".                      |
| cultivos.html | Element hi not allowed.                        | Cambié <hi> por <h1>.                                               |
| granja.html   | Stray end tag html.                            | Coloqué </html> al final del documento, después de </body>.         |
| granja.html   | Character encoding was not declared.           | Añadí <!DOCTYPE html> y revisé <meta charset="UTF-8">.              |
| granja.html   | Stray start tag body.                          | Corregí el orden de las etiquetas <body> y </html>.                 |

### ¿Qué he hecho en esta unidad?

En esta unidad he creado una página web sobre Stardew Valley utilizando HTML. He organizado la información en cuatro páginas: inicio, aldeanos, cultivos y tipos de granja.

También he utilizado diferentes etiquetas HTML para organizar los contenidos, como títulos, párrafos, listas y bloques de información. Por último, he aprendido a utilizar el validador W3C para encontrar errores y corregirlos de html.