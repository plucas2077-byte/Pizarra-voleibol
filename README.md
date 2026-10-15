# Pizarra de Ejercicios

Banco de ejercicios de voleibol para entrenadores: escribe la explicación, dibuja el ejercicio sobre una pista editable, anímalo paso a paso y expórtalo a PDF para compartirlo con tu cuerpo técnico.

Sin cuentas, sin servidores y sin internet: es un único archivo HTML y tus datos se guardan en una carpeta de tu ordenador.

![Editor de ejercicios](docs/captura-editor.png)

## Qué puedes hacer

- **Dibujar en la pista**: jugadores, rivales, entrenador, balón, conos, zonas, textos y flechas de desplazamiento, pase y remate. Pista entera o media pista, y plantillas de 6 en base.
- **Animar la jugada**: crea varios fotogramas y reprodúcelos para ver cómo se mueven los jugadores.
- **Clasificar a tu manera**: tipo de ejercicio (Analítico, Sintético, Juego reducido, Global), tipologías que creas tú, fundamentos y categorías de edad. Filtra y busca en tu biblioteca.
- **Explicarlo entero**: objetivo, desarrollo, puntos clave, variantes, reglas de puntuación, material, jugadores, minutos e intensidad.
- **Enlazarlo con tus datos**: cada ejercicio tiene un campo para el indicador de DataVolley que quieres mejorar.
- **Exportar a PDF**: la ficha de un ejercicio o todos los de la lista filtrada, uno por página, con la secuencia de fotogramas.
- **Exportar imagen**: un PNG de la pista para mandarlo por mensaje.
- **Guardar en tu ordenador**: elige una carpeta y la app guarda `pizarra-datos.json` y una copia diaria en `copias/` (se conservan 14 días).

<p>
  <img src="docs/captura-biblioteca.png" width="300" alt="Biblioteca con filtros">
  <img src="docs/ejemplo-pdf-1.png" width="300" alt="Ejemplo de PDF">
  <img src="docs/ejemplo-pdf-2.png" width="300" alt="Secuencia de fotogramas en el PDF">
</p>

## Cómo usarla

**Online:** abre la versión publicada en GitHub Pages (enlace en la descripción del repositorio).

**En tu ordenador:**
1. Descarga el repositorio (botón verde *Code → Download ZIP*) y descomprímelo.
2. Abre `index.html` con **Chrome o Edge**.
3. Pulsa **Elegir carpeta** y escoge dónde quieres guardar tus ejercicios.

Cada vez que abras la app, el navegador pedirá permiso para usar esa carpeta: pulsa **Conectar carpeta**.
En Firefox y Safari funciona, pero solo guarda dentro del navegador.

> `jspdf.umd.min.js` es la librería que genera los PDF. Déjala siempre junto a `index.html`.

## Compartir ejercicios

- **PDF**: para cualquier persona, sin instalar nada.
- **Copia de seguridad / Importar**: un `.json` para pasar tus ejercicios a otro entrenador que también use la app.

## Vídeo

[Ver el vídeo de presentación](docs/promo-reel.mp4)

## Licencia

MIT. Hecha por Pedro, entrenador de voleibol.
