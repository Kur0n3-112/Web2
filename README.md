# Portal de Intercambio de Material Académico
## Bloque 1 - Prototipo HTML5 + CSS

### Descripción del Proyecto

Plataforma web colaborativa para facilitar el intercambio de apuntes, exámenes y recursos educativos entre estudiantes y docentes.

**Enlaces del curso:**
- Link curso: https://studium25.usal.es/course/view.php?id=2502022
- Link tarea: https://studium25.usal.es/mod/resource/view.php?id=142553

---

## Estructura de Archivos

```
Web1/
├── index.html                   ← Página principal
├── css/
│   └── styles.css               ← CSS único global
├── public/
│   ├── index.html               ← Dashboard usuario registrado
│   ├── materiales.html          ← Listado de materiales
│   ├── material.html            ← Detalle de material
│   ├── colecciones.html         ← Listado de colecciones
│   ├── coleccion.html           ← Detalle de colección
│   ├── login.html               ← Autenticación
│   ├── registro.html            ← Registro
│   ├── subida.html              ← Subir material
│   ├── dudas.html               ← Q&A listado
│   └── duda.html                ← Q&A detalle
├── admin/
│   ├── index.html               ← Dashboard admin
│   ├── usuarios.html            ← Gestión usuarios
│   ├── documentos.html          ← Validación docs
│   ├── comentarios.html         ← Moderación
│   └── categorias.html          ← CRUD categorías
└── docs/
    └── memoria/                 ← Memoria del proyecto
```

---

## Cómo Visualizar el Proyecto

### Opción 1: Abrir directamente en el navegador
1. Navega hasta la carpeta `Web1`
2. Abre `index.html` con tu navegador preferido:
   - **Chrome** (recomendado)
   - Firefox
   - Edge

### Opción 2: Usar Live Server (VS Code)
1. Instala la extensión "Live Server" en VS Code
2. Haz clic derecho en `index.html`
3. Selecciona "Open with Live Server"
4. Se abrirá en `http://localhost:5500`

---

## Design System

### Colores Principales
- **Primario**: `#2563eb` (azul)
- **Secundario**: `#7c3aed` (púrpura)
- **Success**: `#059669` (verde)
- **Warning**: `#d97706` (naranja)
- **Error**: `#dc2626` (rojo)

### Componentes
- Botones (6 variantes + 3 tamaños)
- Formularios completos (input, select, textarea, checkbox, radio)
- Cards con variantes
- Badges (5 variantes)
- Alertas (4 tipos)
- Paginación accesible
- Rating con estrellas

---

##  Accesibilidad AA

### Características implementadas:
- **Skip link** en todas las páginas
- **HTML semántico** con landmarks (header, nav, main, aside, footer)
- **Contraste de color** ≥ 4.5:1 (texto normal)
- **Focus visible** en todos los elementos interactivos
- **Navegación por teclado** completa
- **ARIA labels** donde corresponde
- **Títulos únicos** por página
- **Labels asociados** a todos los inputs
- **Responsive** sin scroll horizontal (hasta 320px)

---

## Responsive Design

### Breakpoints implementados:
- **Mobile**: 320px - 767px (1 columna)
- **Tablet**: 768px - 1023px (2-3 columnas)
- **Desktop**: 1024px - 1439px (3-4 columnas)
- **Large Desktop**: ≥1440px (4-5 columnas)

---

## Validación

### HTML
- Validado en W3C HTML Validator
- Sin errores críticos
- HTML5 semántico

### CSS
- Validado en W3C CSS Validator
- Sin errores
- CSS3 moderno con variables

### Navegadores probados
- Google Chrome (últimas 2 versiones)
- Mozilla Firefox (últimas 2 versiones)
- Microsoft Edge (últimas 2 versiones)
