# MD Sistemas — Servicios (build rápido)

Este paquete incluye `index.html` listo para copiar/pegar.

## Vista previa local (sin instalar nada)
- **macOS / Linux**: abre Terminal en esta carpeta y ejecuta:
  python3 -m http.server 8000
  Luego visita http://localhost:8000

- **Windows (PowerShell)**:
  python -m http.server 8000
  Luego visita http://localhost:8000

## Publicar online (2 clics)
- **Netlify Drop**: arrastra *index.html* a https://app.netlify.com/drop
- **GitHub Pages**:
  1) Crea repo, sube `index.html` a la rama principal.
  2) Settings → Pages → Deploy from branch → `main` → `/ (root)`.

## Dónde me dirás los cambios
Si me indicas “cambia X”, te devolveré: `index.html:línea N` con el reemplazo exacto.