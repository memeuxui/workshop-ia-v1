# IxDF Mendoza · Comunidad

Sitio del grupo local de la Interaction Design Foundation en Mendoza, construido desde el diseño de Figma en el workshop *Del Diseño a la Web con Claude*.

- Un solo `index.html` con el CSS y el JS adentro, sin librerías.
- Imágenes en `assets/`.
- El contenido (encuentros, temas, links) está en arrays al principio del `<script>`: se edita ahí, sin tocar el HTML.
- Paletas y estilos del design system: `?paleta=Taller|Bosque|Noche|Mono&estilo=Techy|Neobrutalista|Minimal|Notion`.

## Verlo en local

Abrí `index.html` con doble clic, o levantá un servidor:

```bash
python3 -m http.server 8000
```
