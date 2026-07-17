# Carta de presentación profesional — Aarón Fernández

Portfolio estático y responsive construido a partir del currículum facilitado. La página prioriza el perfil de ingeniería informática e inteligencia artificial, con una dirección visual cálida, minimalista y un elemento principal de *liquid metal*.

## Vista local

Desde esta carpeta:

```bash
python3 -m http.server 4180
```

Después abre `http://localhost:4180`.

También se puede abrir `index.html` directamente, aunque un servidor local permite probar todas las funciones del navegador en un contexto seguro.

## Personalización rápida

Todo el contenido, los estilos y las interacciones están dentro de `index.html`:

- **Textos y experiencia:** busca los títulos de las secciones en el HTML.
- **Colores:** modifica las variables de `:root` al comienzo del bloque `<style>`.
- **Correo y enlaces:** busca `aaron.fernandez.ramon@gmail.com`, `Rapidfiend34` o `linkedin.com`.
- **Currículum descargable:** reemplaza `assets/curriculum-aaron-fernandez.pdf` conservando el mismo nombre.

## Contenido incluido

La versión actual incorpora el perfil, trabajo en Gemminis, formación, certificados, experiencia adicional, idiomas, permiso de conducir y los proyectos Human-TrAIts y TFGTiempoReal. Los enlaces de LinkedIn y GitHub se han contrastado con el PDF y con los repositorios públicos.

Para futuras actualizaciones basta con facilitar, por cada novedad: título, organización, periodo, descripción breve, tecnologías, resultado medible y enlace público si existe. Los hitos más relevantes pueden promocionarse al bloque de trabajo seleccionado sin rehacer el diseño.

## Publicación

Es un sitio estático sin dependencias ni proceso de compilación. Se puede publicar directamente en:

- GitHub Pages
- Netlify
- Cloudflare Pages
- Vercel

La carpeta publicable es la raíz de este proyecto y el documento de entrada es `index.html`.

## Privacidad

El portal muestra el correo y los perfiles profesionales incluidos en el currículum. El teléfono se ha omitido deliberadamente para reducir spam y exposición en una página pública.
