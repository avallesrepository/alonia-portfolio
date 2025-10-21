# Alonia Portfolio

Un sitio web portfolio moderno y responsive para Alonia.

## Estructura del Proyecto

El portfolio consta de 3 páginas principales:

1. **index.html** - Página de inicio con presentación y contacto
2. **about.html** - Página "Quiénes Somos" con información sobre la empresa
3. **projects.html** - Página de proyectos con galería de trabajos

## Características

✅ **Dos páginas principales:**
- Quiénes Somos (about.html) - Explica la misión, visión, valores y equipo
- Proyectos (projects.html) - Muestra una galería de proyectos realizados

✅ **Información de contacto visible y accesible:**
- Email: contacto@alonia.com
- Teléfono: +34 123 456 789
- Instagram: @alonia
- Presente en todas las páginas en la sección de contacto

✅ **Diseño responsive:**
- Adaptable a dispositivos móviles, tablets y escritorio
- Navegación intuitiva
- Diseño moderno y profesional

## Cómo Usar

### Para visualizar localmente:

Simplemente abre cualquier archivo HTML en tu navegador web:

```bash
# Con Python 3
python -m http.server 8000

# O con Node.js (si tienes http-server instalado)
npx http-server

# Luego visita http://localhost:8000 en tu navegador
```

### Para añadir fotos:

1. **Para el equipo (about.html):**
   - Sustituye los placeholders en la sección `.team-grid`
   - Añade imágenes dentro de `.team-photo-placeholder`

2. **Para los proyectos (projects.html):**
   - Sustituye los `.project-image-placeholder`
   - Añade las imágenes de tus proyectos
   - Actualiza los títulos, descripciones y etiquetas

### Personalización

- **Colores:** Modifica las variables CSS en `styles.css` (sección `:root`)
- **Contenido:** Edita directamente los archivos HTML
- **Contacto:** Actualiza los enlaces de email, teléfono e Instagram en las tres páginas

## Tecnologías Utilizadas

- HTML5
- CSS3 (con variables CSS y Grid/Flexbox)
- SVG para iconos
- Diseño mobile-first

## Próximos Pasos

1. Añadir las fotos del equipo y proyectos
2. Actualizar la información de contacto real
3. Personalizar los textos según las necesidades
4. Opcional: Añadir funcionalidades JavaScript (formulario de contacto, animaciones, etc.)