# Misión UPN

Minijuego de trivia diaria: 3 preguntas al día, XP, racha, vidas y medallas canjeables.

## Probar en local
Abre `index.html` en el navegador.

## Publicar en GitHub Pages
1. Crea un repositorio en GitHub y sube todo el contenido de esta carpeta.
2. Ve a **Settings → Pages**.
3. En **Source** elige **Deploy from a branch**, rama `main`, carpeta `/ (root)`.
4. Espera 1-2 minutos. Tu juego estará en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Editar contenido
- `js/config.js`: preguntas, XP por acierto, costo de las medallas.
- `assets/`: imágenes de Atoq Yachaq (`atoq_neutro.png`, etc.).
- `css/style.css`: estilos.
- `js/app.js`: lógica del juego.

El progreso se guarda en el `localStorage` del navegador de cada persona.
