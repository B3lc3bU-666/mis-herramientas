# Mis herramientas

Portal personal publicado con GitHub Pages:
https://b3lc3bu-666.github.io/mis-herramientas/

## Aplicaciones
- `index.html`: menú principal y acceso a las herramientas.
- `control_ing.html`: control del ciclo de nómina y previsiones.
- `Presupuesto.html`: ingresos, gastos y proyecciones de ahorro.
- `styles.css`: diseño común responsive, temas claro y oscuro automáticos según `prefers-color-scheme`.

## Diseño
Los cambios estéticos se concentran en `styles.css` para compartir colores, tarjetas, botones y navegación. Las aplicaciones conservan su JavaScript original, sus cálculos y las claves de almacenamiento.

## Privacidad y datos
**No subir `presupuesto.json` ni datos económicos personales al repositorio público.** Cada navegador guarda sus propios datos mediante `localStorage`; no existe sincronización automática entre dispositivos. Se puede usar la importación y exportación JSON de Mi presupuesto para trasladar valores manualmente.

## Publicación
GitHub Pages utiliza la rama `main`, carpeta `/ (root)`. Los cambios subidos a esa rama se publican automáticamente.
