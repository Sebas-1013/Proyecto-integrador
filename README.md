# Plantilla Web Responsive

Este proyecto es una plantilla web responsive desarrollada exclusivamente con HTML y CSS, diseñada para ser reutilizable y adaptable a diferentes propósitos como portafolios, sitios educativos o negocios pequeños. Incluye una biblioteca de componentes UI reutilizables que siguen la metodología BEM.

## Características

- Desarrollado exclusivamente con HTML y CSS (sin JavaScript ni frameworks)
- Diseño responsive que se adapta a diferentes tamaños de pantalla
- Estructura semántica utilizando las etiquetas HTML5 apropiadas
- Metodología BEM (Block, Element, Modifier) para nombrar clases CSS
- Paleta de colores personalizable mediante variables CSS
- Estructura de archivos organizada y modular
- Biblioteca de componentes UI reutilizables (botones, tarjetas, formularios, acordeones, alertas, paginación, barras de progreso, pestañas, tooltips, etc.)
- Página de visualización de componentes para facilitar su implementación

## Estructura del Proyecto

```
/
├── assets/
│   ├── css/
│   │   ├── styles.css          # Estilos globales y variables
│   │   ├── index.css           # Estilos específicos para la página principal
│   │   ├── about.css           # Estilos específicos para la página Acerca de
│   │   ├── services.css        # Estilos específicos para la página Servicios
│   │   ├── contact.css         # Estilos específicos para la página Contacto
│   │   └── components/         # Estilos específicos para componentes
│   └── images/                 # Carpeta para almacenar imágenes
├── components/                 # Componentes UI reutilizables
│   ├── accordion.html          # Componente de acordeón
│   ├── alerts.html             # Componente de alertas
│   ├── breadcrumbs.html        # Componente de migas de pan
│   ├── buttons.html            # Componente de botones
│   ├── cards.html              # Componente de tarjetas
│   ├── content.html            # Componente de secciones de contenido
│   ├── footer.html             # Componente de pie de página
│   ├── form.html               # Componente de formularios
│   ├── gallery.html            # Componente de galerías
│   ├── header.html             # Componente de cabecera
│   ├── hero.html               # Componente de sección hero
│   ├── navbar.html             # Componente de menú de navegación
│   ├── pagination.html         # Componente de paginación
│   ├── progress-bars.html      # Componente de barras de progreso
│   ├── tabs.html               # Componente de pestañas
│   ├── testimonials.html       # Componente de testimonios
│   └── tooltips.html           # Componente de tooltips
├── pages/
│   ├── about.html              # Página Acerca de
│   ├── components-view/        # Visualización de componentes
│   │   └── index.html          # Página principal de visualización de componentes
│   ├── services.html           # Página Servicios
│   └── contact.html            # Página Contacto
├── index.html                  # Página principal
└── README.md                   # Este archivo
```

## Páginas Incluidas

- **Inicio (index.html)**: Página principal con secciones de hero, características y llamada a la acción.
- **Acerca de (about.html)**: Información sobre la empresa, historia, misión, valores y equipo.
- **Servicios (services.html)**: Descripción de servicios ofrecidos, proceso de trabajo y planes de precios.
- **Contacto (contact.html)**: Formulario de contacto, información de contacto, mapa y preguntas frecuentes.
- **Biblioteca de Componentes (pages/components-view/index.html)**: Visualización de todos los componentes UI disponibles con enlaces a sus respectivas páginas de detalle.

## Personalización

### Colores

La paleta de colores se puede personalizar fácilmente modificando las variables CSS en el archivo `assets/css/styles.css`. Las principales variables son:

```css
:root {
    --color-primary: #3498db;       /* Azul principal */
    --color-secondary: #2ecc71;     /* Verde secundario */
    --color-accent: #e74c3c;        /* Rojo acento */
    --color-dark: #2c3e50;          /* Azul oscuro */
    --color-light: #ecf0f1;         /* Gris claro */
    /* ... más variables ... */
}
```

### Tipografía

La tipografía también se puede personalizar modificando las variables correspondientes en el mismo archivo:

```css
:root {
    --font-family-base: 'Arial', 'Helvetica', sans-serif;
    --font-family-heading: 'Arial', 'Helvetica', sans-serif;
    /* ... tamaños de fuente ... */
}
```

## Metodología BEM

Este proyecto utiliza la metodología BEM (Block, Element, Modifier) para nombrar las clases CSS, lo que facilita la comprensión y el mantenimiento del código. Ejemplos:

- `.header` (bloque)
- `.header__logo` (elemento)
- `.nav__link--active` (modificador)

## Responsive Design

El diseño se adapta a diferentes tamaños de pantalla mediante el uso de media queries. Los principales breakpoints son:

- **Móvil**: hasta 480px
- **Tablet**: hasta 768px
- **Desktop**: más de 768px

## Uso

Para utilizar esta plantilla:

1. Clona o descarga este repositorio
2. Personaliza los colores, tipografía y contenido según tus necesidades
3. Reemplaza los textos de placeholder con tu contenido real
4. Añade tus propias imágenes en la carpeta `assets/images/`
5. Explora la [Biblioteca de Componentes](pages/components-view/index.html) para ver todos los componentes UI disponibles y cómo implementarlos en tu proyecto

## Créditos

Desarrollado como parte de un proyecto integrador educativo enfocado en fundamentos de desarrollo web frontend.