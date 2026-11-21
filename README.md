# Castillo Infinito

**Castillo Infinito** es un videojuego de terror y exploración en primera persona desarrollado con HTML, CSS y JavaScript, utilizando la biblioteca Three.js para representar el escenario en 3D.

## Descripción

El jugador explora un castillo formado por salas que se generan progresivamente. Cada sala tiene una puerta que conduce a la siguiente. Durante el recorrido debe buscar llaves, administrar la linterna y la energía, y evitar a las criaturas que aparecen en algunas salas.

## Características

- Escenario 3D en primera persona.
- Salas generadas de forma progresiva.
- Puertas que pueden estar cerradas con llave.
- Llaves que el jugador puede recoger.
- Linterna con batería limitada.
- Barra de energía para correr.
- Armarios donde el jugador puede esconderse.
- Enemigos y eventos aleatorios.
- Efectos de sonido generados mediante JavaScript.
- Récord de salas alcanzadas guardado en el navegador.

## Controles

| Tecla o control | Acción |
|---|---|
| W, A, S, D | Moverse |
| Ratón | Mirar alrededor |
| Shift | Correr |
| E | Interactuar: abrir puertas, recoger llaves o esconderse |
| F | Encender o apagar la linterna |
| Clic (cuando está en pausa) | Continuar |

## Cómo ejecutar el juego

1. Descarga `index.html`.
2. Abre el archivo con un navegador moderno, como Google Chrome, Microsoft Edge o Firefox.
3. Pulsa **ENTRAR AL CASTILLO**.
4. Haz clic en la ventana del juego si el navegador lo solicita para activar el control del ratón.

## Tecnologías utilizadas

- **HTML5:** estructura del juego.
- **CSS3:** estilos de la interfaz y pantallas.
- **JavaScript:** lógica, controles, generación de salas, enemigos y sonidos.
- **Three.js (r128):** gráficos y escena 3D.

## Requisitos

- Un navegador moderno compatible con WebGL.
- Conexión a Internet al iniciar el juego para cargar Three.js desde CDN.

## Archivos

- `index.html`: contiene el juego completo (estructura, estilos y código JavaScript).
- `README.md`: documentación y descripción del proyecto.

## Nota

El juego utiliza Pointer Lock para controlar la cámara con el ratón. Para salir del control del ratón, utiliza la tecla `Esc`.
