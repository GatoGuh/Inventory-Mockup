# Inventory Mockup

Maqueta web de un inventario de equipamiento al estilo Diablo. Tiene 9 slots: casco, amuleto, arma, pechera, mano secundaria, anillo, guantes, cinturón y botas. El fondo es un mosaico de cristal líquido hecho con un shader WebGL.

## Estructura

```
index.html                 página y lógica (escena, mosaico, shader)
css/style.css              estilos (panel, marcos, slots, móvil)
scripts/d3-delaunay.min.js triangulación Voronoi del mosaico
.nojekyll                  GitHub Pages sirve los archivos tal cual
```

## Ver en local

La página se abre directamente en el navegador. Para probarla con un servidor local:

```
python -m http.server 8000
```

Después, abre http://localhost:8000.

## Publicar con GitHub Pages

1. En el repositorio, ve a **Settings → Pages**.
2. En **Source**, elige **Deploy from a branch**.
3. Selecciona la rama `main` y la carpeta `/ (root)`, y guarda.
4. Al cabo de un minuto la web estará en https://gatoguh.github.io/Inventory-Mockup/.
