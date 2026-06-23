# chenchito - Página de la tarjeta

Este commit añade la página interactiva "sobre → tarjeta" corregida y accesible.

Archivos añadidos:

- `index.html` — Página principal con el sobre, la tarjeta y el reproductor de audio.
- `TU-MUSICA-README.md` — Instrucciones para añadir el archivo de audio o usar una URL externa.

Qué hice:

- Arreglé el HTML/CSS/JS (eliminé un <script> dentro del <style>, corregí llaves y duplicados).
- Añadí mejoras de accesibilidad (role, aria, keyboard support) y ajustes responsivos.

Probar localmente:

1. Clona el repo:

   git clone https://github.com/dianitalizondo-commits/chenchito.git

2. Cambia a la rama con los cambios:

   git checkout fix/envelope-page

3. Abre `index.html` en tu navegador (doble clic) o usa un servidor local como `Live Server` o `python -m http.server`.

Añadir audio:

- Coloca tu archivo `tu-musica.mp3` en la raíz del repo (junto a index.html), o modifica la etiqueta `<source>` en `index.html` para apuntar a una URL externa.

Crear PR:

- Si todo está bien, crea un Pull Request desde `fix/envelope-page` hacia la rama por defecto en GitHub y revisa los cambios.
