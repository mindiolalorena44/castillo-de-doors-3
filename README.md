# Castillo Infinito

**Castillo Infinito** es un videojuego de exploración y terror en primera persona. El jugador avanza por un castillo formado por salas conectadas, encuentra llaves y abre puertas mientras evita a las criaturas que aparecen durante el recorrido.

## Características

- Salas generadas de forma procedural, con distintas decoraciones y obstáculos.
- Exploración en primera persona.
- Puertas que pueden estar cerradas y requieren encontrar una llave.
- Linterna con batería limitada.
- Barra de energía para correr.
- Armarios donde el jugador puede esconderse.
- Enemigos: un espectro y un caballero.
- Efectos de sonido y ambiente generados mediante Web Audio.
- Récord de la sala alcanzada guardado en el almacenamiento local del navegador.
- Controles para computadora y dispositivos con pantalla táctil.

## Controles

### Computadora

| Tecla o control | Acción |
|---|---|
| W, A, S, D o flechas | Moverse |
| Ratón | Mirar alrededor |
| Shift | Correr |
| E | Interactuar, abrir puertas, recoger llaves o esconderse |
| F | Encender o apagar la linterna |
| Escape | Liberar el control del ratón y pausar |

### Dispositivos táctiles

- Joystick izquierdo: moverse.
- Deslizar en la mitad derecha: mirar alrededor.
- Botón **E**: interactuar.
- Botón de linterna: encender o apagarla.
- Botón de rayo: correr mientras se mantiene pulsado.
- Botón de pausa: pausar el juego.

En teléfonos, el juego solicita usar la pantalla en posición horizontal.

## Cómo jugar

1. Abre `index.html` en un navegador moderno.
2. Selecciona **ENTRAR AL CASTILLO**.
3. Explora cada sala y busca llaves cuando encuentres una puerta cerrada.
4. Administra la batería de la linterna y la energía para correr.
5. Si aparecen señales de peligro, busca un armario para esconderte.
6. Avanza por las puertas para llegar a nuevas salas y superar tu récord.

## Requisitos

- Navegador moderno compatible con WebGL.
- Conexión a internet para cargar Three.js desde CDN.
- Teclado y ratón para jugar en computadora, o pantalla táctil en dispositivos compatibles.

## Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript
- [Three.js r128](https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js)
- Web Audio API

## Archivos

- `index.html`: contiene el juego completo, incluidos los estilos, la lógica y la interfaz.
- `README.md`: documentación e instrucciones del proyecto.

## Publicación

Para publicar el proyecto en GitHub Pages, coloca `index.html` y `README.md` en la carpeta principal del repositorio. Luego configura GitHub Pages para publicar desde la rama y carpeta que estés utilizando.
