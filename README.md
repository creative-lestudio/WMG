# World Management Group — sitio web

Sitio estático (HTML + CSS + JS, sin build). Todo vive en `index.html`; el logo en `assets/`.

## Línea gráfica
- **Índigo WMG** `#2F2780` (fondo del logo) · **Hielo** `#E7EBF1` (símbolo) · **Volt** `#C9F25B` (acento dinámico) · **Violeta eléctrico** `#6F5CFF`.
- Tipografía: Sora (títulos) + Inter (texto).
- El símbolo (dos rombos entrelazados) se usa como patrón, máscara y elemento animado.

## Contenido por reemplazar
Roster, cifras, correo y textos son **de ejemplo**. Edita el arreglo `ROSTER` y los `data-count` en `index.html`, y las fotos reales en cada tarjeta (`img` en el campo `img`).

## Local
```bash
python3 -m http.server 8000
```
Publicación: Settings → Pages → Source: **GitHub Actions**.
