# Contenido

## Temas

- [Tema del manual](https://github.com/fniessen/org-html-themes)
- [Tema de lo hoja de evaluación](https://github.com/gongzhitaao/orgcss)
- [Tema org-minimal](https://github.com/caffo/org-minimal-html-theme.git)
- [Tema Org-Simple](https://www.btbytes.com/pages/org-simple.html)
- [Tema solarized](https://thomasf.github.io/solarized-css/)

# Compilación a Latex

Una vez creado el archivo tex se debe borrar la línea que crea la TOC manualmente

# Compilación a HTML

Es  productivo leer [CSS for  Org-exported HTML](https://gongzhitaao.org/orgcss/)

Los 3 `</div>` deben ir antes de la sección de bibliografía.  Se ha creado [un parche](html.patch) para eso.

## Colocación

La página de evaluación debe ser el index.html de la versión web.

Copiar las carpetas `assets`, `im` y `styles` en el sitio.

La versión PDF debe ir en `assets/manual.pdf` y la versión HTML en `manual.html`.

# Bibliografía

Se usa ox-bibtex, ver https://vimeo.com/99167082
