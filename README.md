# Castillo Infinito

**Castillo Infinito** es un juego de exploración y terror en primera persona. El jugador debe avanzar por las salas del castillo, abrir puertas, encontrar llaves y evitar a las criaturas que aparecen durante el recorrido.

## Objetivo

- Explorar las salas numeradas desde la puerta 300.
- Encontrar llaves cuando una puerta esté cerrada.
- Usar los armarios para esconderse cuando sea necesario.
- Administrar la energía para correr y la batería de la linterna.
- Llegar hasta la puerta final y escapar del Guardián de Acero.

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

### Teléfono o dispositivo táctil

- **Joystick izquierdo:** moverse.
- **Deslizar en la mitad derecha:** mirar alrededor.
- **Botón E:** interactuar.
- **Botón de linterna:** encender o apagar la linterna.
- **Botón ⚡:** mantener pulsado para correr.
- **Botón ❚❚:** pausar.

En teléfonos, el juego solicita colocar el dispositivo en posición horizontal.

## Cómo jugar

1. Descarga `index.html`.
2. Abre el archivo con un navegador moderno, como Google Chrome, Microsoft Edge o Firefox.
3. Pulsa **ENTRAR AL CASTILLO**.
4. Recorre cada sala y presta atención a los avisos del juego.
5. Si encuentras una puerta cerrada, busca la llave en la sala.
6. Cuando las luces tiemblen o escuches señales de peligro, busca un armario y escóndete.
7. Conserva la batería de la linterna y la energía para correr.
8. Avanza hasta completar el recorrido.

## Requisitos

- Navegador moderno con soporte para WebGL.
- Conexión a internet para cargar la biblioteca Three.js, que el juego utiliza desde un CDN.
- Teclado y ratón para jugar en computadora, o pantalla táctil para jugar en dispositivos compatibles.

## Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript
- [Three.js](https://threejs.org/) r128 para los gráficos 3D
- Web Audio API para efectos y audio del juego
- `localStorage` para guardar el récord de salas alcanzadas en el navegador

## Archivos del proyecto

- `index.html`: contiene el juego completo: estructura, estilos, controles y programación.

## Publicar en GitHub Pages

1. Crea un repositorio en GitHub.
2. Sube `index.html` y `README.md` a la carpeta principal del repositorio.
3. En el repositorio, abre **Settings → Pages**.
4. En la opción de publicación, selecciona la rama principal y la carpeta raíz (`/root`).
5. Guarda los cambios y espera a que GitHub Pages publique el sitio.
6. Abre el enlace que GitHub Pages te proporcione.

---

Proyecto: **Castillo Infinito**.
