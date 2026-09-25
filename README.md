# Le Contes | Pastelería artesanal

El proyecto final del curso de Desarrollo Web. El sitio está desarrollado con HTML, SCSS, Bootstrap y AOS y SEO.

## SCSS

Para visualizar los cambios realizados teniendo scss se debe activar sass. Para saber si tiene o no carpetas sass, se busca la ruta `sass/main.scss` mientras que el CSS compilado se encuentra en `styles/style.css`.
Instalar Sass, desde la raíz del proyecto ejecutar:

```bash
sass --watch sass/main.scss:styles/style.css
```

## La estructura principal

```text
index.html
pages/
  contacto.html
  el-espacio.html
  menu.html
  sobre-nosotros.html
image/
sass/
styles/
```

## SEO
- Cada página contiene exactamente un `h1`. (check)
- La jerarquía de encabezados `h1` para el título y `h2`/`h3` para subsecciones.(check)
- La navegación utiliza etiquetas semánticas (`header`, `nav`, `main`, `section`, `article`, `footer`).
- Todas las etiquetas `<img>` incluyen un atributo `alt` descriptivo, esto para los ususarios con dificultad visual. (check)
- Las 5 páginas HTML deben incluir un `title`, `meta description` y `meta keywords` específico para su contenido.
- Los enlaces de correo y teléfono utilizan `mailto:` y `tel:`.(check)

## Visualización de pagina 
https://ceciliaberon.github.io/Desarrollo_Web_94785_entrega9/
