# Instrucciones para Añadir Fotos

Este documento explica cómo añadir las fotos al portfolio una vez estén listas.

## 1. Estructura de Carpetas Recomendada

Crea las siguientes carpetas para organizar las imágenes:

```
alonia-portfolio/
├── images/
│   ├── team/          # Fotos del equipo
│   └── projects/      # Fotos de proyectos
├── index.html
├── about.html
├── projects.html
└── styles.css
```

## 2. Añadir Fotos del Equipo (about.html)

Busca en `about.html` la sección con clase `.team-grid`. Actualmente tiene 3 placeholders:

```html
<div class="team-placeholder">
    <div class="team-photo-placeholder"></div>
    <h3>Miembro del Equipo</h3>
    <p>Rol / Posición</p>
</div>
```

**Reemplaza por:**

```html
<div class="team-placeholder">
    <img src="images/team/persona1.jpg" alt="Nombre de la persona" class="team-photo">
    <h3>Nombre de la Persona</h3>
    <p>Director / Diseñador / etc.</p>
</div>
```

**Añade este CSS a `styles.css`:**

```css
.team-photo {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    object-fit: cover;
    margin: 0 auto 1rem;
    display: block;
}
```

## 3. Añadir Fotos de Proyectos (projects.html)

Busca en `projects.html` los elementos con clase `.project-image-placeholder`:

```html
<div class="project-image-placeholder">
    <span>Imagen del Proyecto</span>
</div>
```

**Reemplaza por:**

```html
<img src="images/projects/proyecto1.jpg" alt="Nombre del proyecto" class="project-image">
```

**Añade este CSS a `styles.css`:**

```css
.project-image {
    width: 100%;
    height: 250px;
    object-fit: cover;
    display: block;
}
```

## 4. Optimización de Imágenes

Antes de subir las fotos, es recomendable:

1. **Redimensionar las imágenes:**
   - Fotos de equipo: 300x300 píxeles
   - Fotos de proyectos: 800x600 píxeles

2. **Comprimir las imágenes:**
   - Usa herramientas como TinyPNG, ImageOptim, o Squoosh
   - Objetivo: mantener buena calidad pero reducir el tamaño del archivo

3. **Formato recomendado:**
   - JPG para fotos
   - PNG para imágenes con transparencia
   - WebP para mejor compresión (opcional, con fallback a JPG)

## 5. Subir las Imágenes al Repositorio

```bash
# Crear carpetas
mkdir -p images/team images/projects

# Copiar tus fotos a estas carpetas
# Luego añadir al git
git add images/
git commit -m "Add team and project images"
git push
```

## 6. Actualizar Información de Contacto

Recuerda actualizar en los 3 archivos HTML:

- Email: `contacto@alonia.com` → tu email real
- Teléfono: `+34 123 456 789` → tu teléfono real
- Instagram: `@alonia` → tu usuario real de Instagram

Busca y reemplaza en todos los archivos HTML.

## 7. Ejemplo Completo de Proyecto

Así debería verse un proyecto completo en `projects.html`:

```html
<div class="project-card">
    <img src="images/projects/website-corporativo.jpg" alt="Website Corporativo" class="project-image">
    <div class="project-info">
        <h3>Website Corporativo</h3>
        <p>Diseño y desarrollo de sitio web corporativo moderno y responsive para empresa de tecnología.</p>
        <div class="project-tags">
            <span class="tag">Web Design</span>
            <span class="tag">Desarrollo</span>
        </div>
    </div>
</div>
```

## 8. Verificar los Cambios

Después de añadir las fotos:

1. Abre los archivos HTML en tu navegador
2. Verifica que todas las imágenes se cargan correctamente
3. Comprueba que se ven bien en móvil y desktop
4. Asegúrate de que los enlaces de contacto funcionan

## ¿Necesitas Ayuda?

Si tienes problemas para añadir las fotos, puedes:
1. Revisar este documento
2. Buscar en la documentación de HTML/CSS
3. Contactar al desarrollador que creó esta estructura
