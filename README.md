# Portafolio Personal — Victoria Roiz

## 1. Nombre del proyecto

**Portafolio Personal de Victoria Roiz**

---

## 2. Descripción del proyecto y su funcionalidad

Portfolio personal de una sola página con scroll, construido a partir de un diseño de Figma. Presenta mi perfil como desarrolladora Full-Stack Junior, mis habilidades técnicas, proyectos destacados y formas de contacto.

La página está organizada en cuatro secciones principales:

- **Hero:** presentación con nombre, subtítulo, descripción profesional, foto y tres enlaces de acción (Descargar CV, Enlace a GitHub, Hablemos).
- **Habilidades y herramientas:** muestra los íconos de las tecnologías que manejo: HTML5, CSS3, JavaScript, Git, GitHub y ChatGPT.
- **Proyectos destacados:** tarjetas con imagen de preview, tecnologías usadas, descripción y enlaces a la demo en vivo y al repositorio de GitHub.
- **Contacto:** correo electrónico y enlaces a redes sociales.

La página es completamente responsiva y se adapta a tres tamaños de pantalla: desktop (1440px), tablet (hasta 1023px) y móvil (hasta 767px).

---

## 3. Tecnologías y técnicas utilizadas

**Tecnologías:**

- HTML5 semántico
- CSS3 puro, sin frameworks
- SVGs inline
- Fuentes locales con `@font-face` (Archivo Black y Open Sans)

**Técnicas de CSS:**

- Variables CSS (`custom properties`) en `:root` para colores, fuentes y tamaños tipográficos
- Flexbox para el layout del hero, la barra de CTAs y el footer
- CSS Grid para la grilla de tarjetas de proyectos
- Media queries con breakpoints en `1023px` y `767px`
- `flex-direction: column-reverse` para reorganizar el hero en móvil sin modificar el HTML
- Pseudoelementos `::before` y `::after` para efectos decorativos de luz en el header y el footer
- `linear-gradient` con `background-size` y `background-position` para crear subrayados decorativos en los enlaces
- `position: absolute` sobre contenedores `position: relative` para superponer íconos sobre las imágenes de los proyectos
- `filter: blur()` y `border-radius: 50%` para crear destellos de color difusos
- `calc()` para mantener los efectos decorativos centrados en cualquier ancho de pantalla
- `aspect-ratio: 16/9` y `object-fit: cover` para imágenes responsivas sin distorsión
- Atributo `aria-label` en íconos sin texto visible para accesibilidad

---

## 4. Enlace a GitHub Pages

🔗 [Ver portfolio en vivo](https://victoriaroiz-96.github.io/web_project_portfolio_es)
