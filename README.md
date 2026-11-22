# Castillo Infinito

**Castillo Infinito** es un videojuego de terror en primera persona creado con HTML, CSS y JavaScript, utilizando Three.js para representar el escenario en 3D.

## Descripción

El jugador debe avanzar por un castillo formado por salas y puertas numeradas desde la **300 hasta la 400**. En el recorrido encontrará habitaciones decoradas, objetos que puede abrir, llaves, zonas oscuras y enemigos que debe evitar para llegar a la salida.

El juego incluye:
- Exploración en primera persona de escenarios 3D.
- Puertas numeradas y progresión por el castillo.
- Cofres, cajas y cajones que se pueden abrir para buscar objetos.
- Objetos útiles, como llaves, pizza, vitaminas y encendedor.
- Linterna, energía y vida.
- Armarios para esconderse.
- Enemigos y secciones de persecución.
- Efectos de sonido y ambiente generados mediante Web Audio.
- Controles para computadora y dispositivos con pantalla táctil.
- Ajuste de sensibilidad de cámara.

## Controles

### Computadora
| Tecla o control | Acción |
|---|---|
| W, A, S, D | Moverse |
| Ratón | Mirar alrededor |
| Shift | Correr |
| E | Interactuar, abrir puertas y objetos, esconderse |
| F | Encender o apagar la linterna |
| M | Abrir o cerrar los ajustes |
| Espacio | Saltar |
| 4 o C | Agacharse (mantener pulsado) |

### Dispositivos táctiles
- Joystick de la izquierda: moverse.
- Deslizar en la mitad derecha: mirar alrededor.
- Botón **E**: interactuar.
- Botón de linterna: encender o apagar la linterna.
- Botón de rayo: correr mientras se mantiene pulsado.
- Botones de flechas: saltar y agacharse.
- Botón de engranaje: ajustes.
- Botón de pausa: pausar la partida.

En teléfonos, el juego solicita colocar el dispositivo en posición horizontal.

## Requisitos

- Un navegador moderno actualizado, como Google Chrome, Microsoft Edge o Firefox.
- Compatibilidad con WebGL y aceleración gráfica activada.
- Conexión a Internet para cargar la biblioteca Three.js desde su CDN.
- Teclado y ratón para jugar en computadora, o pantalla táctil en dispositivos compatibles.

## Tecnologías utilizadas

- **HTML5:** estructura del juego.
- **CSS3:** interfaz, menús y controles.
- **JavaScript:** lógica, movimiento, interacción y funcionamiento del juego.
- **Three.js r128:** gráficos y objetos tridimensionales.
- **Web Audio API:** sonidos y ambiente.

## Cómo ejecutar el juego

1. Descarga `index.html`.
2. Abre el archivo con un navegador moderno.
3. Espera a que cargue Three.js y pulsa **ENTRAR AL CASTILLO**.
4. En computadora, permite el bloqueo del puntero cuando el navegador lo solicite para poder mirar con el ratón.

## Publicar en GitHub Pages

1. Crea un repositorio en GitHub.
2. Sube `index.html` y `README.md` a la carpeta principal del repositorio.
3. Entra en **Settings → Pages**.
4. En la sección de publicación, selecciona la rama principal (`main`) y la carpeta raíz (`/root`).
5. Guarda los cambios y espera a que GitHub Pages genere el enlace del sitio.

## Nota técnica

El archivo HTML contiene el juego y sus estilos y scripts. Three.js se carga desde un CDN, por lo que se necesita Internet para iniciar la parte 3D. El código también contiene un espacio reservado para una pista de música (`__MUSIC_B64__`); si no se reemplaza por datos de audio válidos, esa pista no se reproducirá. Los efectos y sonidos sintetizados del juego se generan por separado.
