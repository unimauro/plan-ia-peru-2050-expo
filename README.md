# Plan IA Perú 2050 — Expo

Presentación web (23 láminas) de la **Comisión de Inteligencia Artificial** (CIP · CNPP):
_Plan IA Perú 2050 — el Perú entre las potencias mundiales de la inteligencia artificial_. Borrador en validación.

Copia estática de la expo publicada en <https://planperu2050.pe/expo/>.

## Uso

Es un sitio estático de un solo archivo. Ábrelo directamente o sírvelo:

```bash
python3 -m http.server 8080
# http://localhost:8080
```

### Navegación
- **← / →**, PageUp/PageDown, barra espaciadora, o swipe: cambiar de lámina
- **G**: índice (grilla de todas las láminas)
- **F**: pantalla completa
- **Home / End**: primera / última lámina
- Deep-link por lámina con `#n` (ej. `.../#12`)

## Estructura

```
index.html            slideshow (HTML/CSS/JS, sin dependencias)
slides/slide-01..23.jpg
assets/               favicon (svg/ico/png), apple-touch-icon, og.jpg, manifest
```

## Créditos

Ing. Carlos Mauro Cárdenas Fernández — Presidente de la Comisión.
Colegio de Ingenieros del Perú (CIP) · Consejo Nacional de Planeamiento (CNPP).
