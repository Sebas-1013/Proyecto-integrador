# CedAsistencia

transformamos la manera en que gestionas la asistencia de los estudiantes y docentes. Nuestra herramienta digital te permite registrar, visualizar y analizar la asistencia en tiempo real, desde cualquier lugar y dispositivo.

## Características

- La plataforma permite registrar la asistencia de estudiantes según el grupo, materia o curso asignado. Cada profesor puede tomar asistencia desde su cuenta en función del horario académico, asegurando que los registros estén organizados por semestre, asignatura y programa.

- Cada usuario accede a la plataforma con funciones específicas:

Docentes: pueden tomar, revisar y editar las asistencias de sus clases.

Estudiantes: pueden consultar su historial de asistencia e interactuar con un formulario de excusas.

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
│       ├── logodepagina
│       ├── placeholder.txt      
├── pages/
│   ├── about.html              # Página Acerca de
│   └── contact.html            # Página Contacto
├── index.html                  # Página principal
└── README.md                   # Este archivo
```

## Páginas Incluidas

- **Inicio (index.html)**: Página principal con secciones de hero, características y llamada a la acción.
- **Acerca de (about.html)**: Pagina con nuestra historia, vision, mision e informacion de los desarrolladores.
- **Contacto (contact.html)**: Formulario de contacto, información de contacto, mapa y preguntas frecuentes.
- **Planilla de Asistencias (planilla.html)**: Pagina con registro de asistencias ordenado e interactuable.
- **Registro de Excusas (registro.html)**: Pagina con formulario para la toma de excusas de los estudiantes.

## Personalización
Usamos temas con los colores parecidos a nuestro boceto.
### Colores

La paleta de colores se puede personalizar fácilmente modificando las variables CSS en el archivo `assets/css/styles.css`. Las principales variables son:

```css
:root {
    --color-primary: #881f50;       /* Rosa oscuro */
    --color-secondary: #3d3b3c;     /* Gris oscuro*/
    --color-accent: #881e4f;        /* Rosa acento */
    --color-dark: #666666;          /* Gris claro*/
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

## Créditos

<<<<<<< HEAD
Desarrollado como parte de un proyecto integrador por Santiago Calderon y grupo.
=======
Desarrollado como parte de un proyecto integrador por Santiago Calderon y grupo.
>>>>>>> 8f2efdb0062b628d88ec72f2aa479c0e162bd61f
