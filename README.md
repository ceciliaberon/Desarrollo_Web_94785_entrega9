# Le Contes | Pastelería artesanal

Proyecto final del curso de Desarrollo Web. El sitio está desarrollado con HTML semántico, SCSS, Bootstrap y AOS, con enfoque responsive, accesibilidad y SEO on-page.

## Cómo ejecutar el proyecto

1. Clonar o descargar este repositorio.
2. Abrir `index.html` en el navegador. También puede utilizarse la extensión **Live Server** de Visual Studio Code.
3. La navegación permite acceder a las páginas de contacto, espacio, menú y sobre nosotros.

No se requiere backend ni base de datos. Bootstrap, Google Fonts y AOS se cargan mediante CDN.

## Compilar SCSS

El archivo de entrada es `sass/main.scss` y el CSS compilado se encuentra en `styles/style.css`.

Con Sass instalado, desde la raíz del proyecto ejecutar:

```bash
sass --watch sass/main.scss:styles/style.css
```

## Estructura principal

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

## Evidencias de la entrega SEO

- Cada una de las 5 páginas HTML incluye un `title`, `meta description` y `meta keywords` específico para su contenido.
- Cada página contiene exactamente un `h1`.
- La jerarquía de encabezados utiliza `h1` para el título principal y `h2`/`h3` para subsecciones.
- Todas las etiquetas `<img>` incluyen un atributo `alt` descriptivo.
- Los nombres de las imágenes y páginas son descriptivos, usan minúsculas y guiones, y evitan espacios, paréntesis y caracteres especiales.
- La navegación utiliza etiquetas semánticas (`header`, `nav`, `main`, `section`, `article`, `footer`) y marca la página actual con `aria-current="page"`.
- Los enlaces de correo y teléfono utilizan `mailto:` y `tel:`.
- El contraste principal usa texto oscuro sobre fondos rosa o claros. Para estados interactivos se utiliza el color de acento `#5a2020`, que mantiene contraste legible sobre esos fondos.

## Páginas y foco SEO

| Página | Foco principal |
| --- | --- |
| `index.html` | Pastelería artesanal y presentación de Le Contes |
| `pages/menu.html` | Menú, productos dulces y salados |
| `pages/contacto.html` | Contacto, consultas, teléfono y correo electrónico |
| `pages/el-espacio.html` | Instalaciones y espacio de Le Contes |
| `pages/sobre-nosotros.html` | Historia, proyecto y equipo de Le Contes |

## Publicación

Para la entrega, el repositorio debe ser **público** y contener esta versión actual del proyecto de forma clara en la raíz, evitando mantener varias carpetas paralelas de entregas anteriores que puedan confundir la corrección automática.

En GitHub Pages puede publicarse desde **Settings > Pages**, seleccionando la rama que contiene `index.html` en la raíz.
