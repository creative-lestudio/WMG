# World Management Group — sitio web

Sitio estático (HTML + CSS + JS, sin build). Todo vive en `index.html`; el logo en `assets/`.

## Línea gráfica
- **Índigo WMG** `#2F2780` (fondo del logo) · **Hielo** `#E7EBF1` (símbolo) · **Volt** `#C9F25B` (acento dinámico) · **Violeta eléctrico** `#6F5CFF`.
- Tipografía: Sora (títulos) + Inter (texto).
- El símbolo (dos rombos entrelazados) se usa como patrón, máscara y elemento animado.

## Contenido por reemplazar
Roster real: César Oliveira. Para agregar talentos o fotos edita el arreglo `ROSTER` en `index.html` (campo `img`, ej. `assets/talentos/cesar-oliveira.webp`). Los textos de nosotros/servicios son genéricos y deben validarse.

## Local
```bash
python3 -m http.server 8000
```
Publicación: Settings → Pages → Source: **GitHub Actions**.
