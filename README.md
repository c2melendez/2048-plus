# 2048 Plus

Juego de 2048 para navegador con seis potenciadores: deshacer, teletransportar, intercambiar fichas, girar el borde, borrar por número y bomba.

## Jugar

Abre `index.html` en un navegador moderno. Usa las flechas, WASD o desliza para mover las fichas. Las partidas y el récord se guardan en el almacenamiento local del navegador.

## Potenciadores

Las fichas 128 recargan Deshacer; las 256 recargan Teletransportar, Intercambiar y Girar; y las 512 recargan Borrar número y Bomba. Los usos iniciales y el máximo de dos cargas son aproximaciones. La bomba afecta de cuatro a seis casillas y solicita confirmación.

Inspirado en 2048, creado por Gabriele Cirulli, y en sus versiones posteriores.

## Instalar como aplicación

Abre el juego publicado por HTTPS y usa la opción «Instalar aplicación» o «Añadir a pantalla de inicio» del navegador. En iPhone o iPad, abre la página en Safari y selecciona Compartir → Añadir a pantalla de inicio. Después de la primera visita completa, el juego y los recursos principales quedan disponibles sin conexión.

Para probar la PWA localmente, sirve esta carpeta en `localhost` (por ejemplo, `python -m http.server 8000`); abrir el archivo directamente no activa el service worker.
