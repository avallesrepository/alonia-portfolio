# Alonia Portfolio

Portfolio website para Alonia, promotora y constructora inmobiliaria especializada en proyectos residenciales y comerciales de alta calidad.

## Descripción

Sitio web moderno y minimalista inspirado en el diseño de Apple, OpenAI y portfolios arquitectónicos. Diseñado para mostrar proyectos, servicios y facilitar el contacto con potenciales clientes.

## Características

- **Diseño Moderno y Limpio**: Estética minimalista con tipografía clara y espacios amplios
- **Totalmente Responsive**: Adaptado para todos los dispositivos (móvil, tablet, desktop)
- **Animaciones Suaves**: Transiciones y efectos de scroll modernos
- **Secciones Completas**:
  - Hero con llamada a la acción
  - Sobre nosotros con estadísticas
  - Galería de proyectos
  - Servicios ofrecidos
  - Formulario de contacto
- **Navegación Intuitiva**: Menú fijo con smooth scroll
- **Optimizado para SEO**: Estructura semántica HTML5

## Tecnologías Utilizadas

- HTML5
- CSS3 (con variables CSS y Grid/Flexbox)
- JavaScript (ES6+)
- Sin dependencias externas

## Cómo Usar

1. Clona el repositorio:
   ```bash
   git clone https://github.com/avallesrepository/alonia-portfolio.git
   ```

2. Abre el archivo `index.html` en tu navegador web

3. Para desarrollo local, puedes usar cualquier servidor local:
   ```bash
   # Con Python
   python -m http.server 8000
   
   # Con Node.js (http-server)
   npx http-server
   ```

## Estructura del Proyecto

```
alonia-portfolio/
├── index.html      # Página principal
├── styles.css      # Estilos CSS
├── script.js       # JavaScript para interactividad
└── README.md       # Documentación
```

## Personalización

Para personalizar el sitio web:

1. **Colores**: Modifica las variables CSS en `styles.css`:
   ```css
   :root {
       --primary-color: #1d1d1f;
       --accent-color: #0071e3;
       /* ... más colores */
   }
   ```

2. **Contenido**: Edita el texto en `index.html`

3. **Proyectos**: Añade o modifica los proyectos en la sección `#projects`

4. **Imágenes**: Reemplaza las imágenes placeholder con fotos reales de proyectos

## Licencia

© 2024 Alonia. Todos los derechos reservados.