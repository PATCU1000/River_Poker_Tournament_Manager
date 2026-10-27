# RIVER — Poker Tournament Manager

Aplicación web local para organizar torneos recreativos de Texas Hold'em.

## Cómo abrirla
1. Descomprime la carpeta.
2. Abre `index.html` en un navegador moderno (Chrome, Edge o Firefox).
3. Los torneos se guardan en el almacenamiento local del navegador de ese dispositivo.

No requiere instalación de paquetes ni claves API para probar la versión inicial.

## Funcionalidades incluidas
- Panel de inicio y navegación.
- Generador de estructura de niveles y ciegas con descansos.
- Gestor de maletín y comprobación básica del inventario.
- Temporizador con inicio, pausa, reinicio, niveles, ajustes de tiempo y pantalla completa.
- Registro de jugadores y eliminaciones.
- Calculadora de bote y premios con validación de porcentajes y cálculo en céntimos.
- Historial, duplicado, eliminación y copia de seguridad JSON.

## Limitaciones conocidas
- El reparto automático es una comprobación inicial por valores de ficha, no un optimizador exhaustivo de combinaciones.
- La estructura de ciegas es una planificación recreativa y no puede garantizar la duración real del torneo.
- La persistencia es local al navegador; no hay sincronización entre dispositivos ni cuentas/Supabase.
- La versión actual no incluye exportación PDF/CSV, ligas privadas ni pagos.
- Antes de usarla para un torneo real, conviene probar los casos límite y revisar las reglas que quieras utilizar.

## Publicar en GitHub Pages
1. Crea un repositorio nuevo en GitHub.
2. Sube `index.html`, `styles.css`, `app.js` y `README.md` a la raíz del repositorio.
3. En el repositorio, abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/ (root)`, y guarda.
6. Espera a que GitHub Pages indique la dirección pública del sitio.

Esta versión es completamente estática y no necesita Supabase para las funciones locales.
