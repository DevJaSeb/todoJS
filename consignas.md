# FLUJO DE VERSIONES
## Crear una nueva rama con su funcionalidad
    - git checkout -b feature/agregar-filtro
    - Realiza cambios
    - git add .
    - git commit -m "Agregar funcionalidad de filtro a la lista"
## Fusionar en develop
    -git checkout develop
    -git merge feature/agregar-filtro
## Borrar la rama creada
    -git branch -d feature/agregar-filtro     
## Realizar Pruebas y luego fusionar con main
    -git checkout main
    -git merge develop

# Requisitos:
## Estructura HTML:

- Header con el título de la aplicación.
- Sección principal con un input para agregar tareas y un botón "Agregar".
- Lista de tareas (cada tarea debe tener un checkbox para marcarla como completada, un botón para editar y un botón para eliminar).
- Footer con un contador de tareas pendientes.

## Estilos CSS:

- Diseño minimalista y responsive.
- Animaciones al agregar o eliminar tareas.
- Uso de flexbox o grid para el diseño.

## Funcionalidad JavaScript:

- Agregar tareas: Al hacer clic en "Agregar", la tarea debe aparecer en la lista.
- Marcar como completada: Al hacer clic en el checkbox, la tarea debe tacharse.
- Editar tareas: Al hacer clic en el botón de editar, el texto de la tarea debe ser editable.
- Eliminar tareas: Al hacer clic en el botón de eliminar, la tarea debe desaparecer de la lista.
- Contador de tareas pendientes: Debe actualizarse automáticamente.
- Drag and Drop

## Paleta de colores

### Colores principales
- **#FFF2F2** (Rosa muy claro): Color de fondo principal de la aplicación, proporciona un ambiente suave y acogedor.
- **#A9B5DF** (Azul lavanda claro): Usado para elementos secundarios, bordes, footer y elementos de acento.
- **#7886C7** (Azul púrpura medio): Utilizado para elementos interactivos, botones secundarios y elementos destacados como pestañas activas.
- **#2D336B** (Azul oscuro/índigo): Color principal para encabezados, botones primarios y textos importantes.

### Colores funcionales
- **Blanco (#FFFFFF)**: Fondo de las tarjetas de tareas y contraste para mejorar la legibilidad.
- **Gris claro (#F3F4F6)**: Fondo para tareas completadas, creando un contraste visual.
- **Gris medio (#9CA3AF)**: Texto secundario y elementos deshabilitados.
- **Gris oscuro (variante de #2D336B)**: Texto principal, asegurando buena legibilidad.

### Usos específicos
- **Encabezado**: #2D336B con texto blanco para máximo contraste.
- **Footer**: #A9B5DF con texto en #2D336B para información secundaria.
- **Botones primarios**: #2D336B con hover ligeramente más claro.
- **Botones secundarios**: #7886C7 con hover ligeramente más claro.
- **Bordes**: #A9B5DF para delimitar elementos y crear separación visual.
- **Filtros activos**: #7886C7 para destacar la pestaña seleccionada.
- **Checkbox**: Borde #A9B5DF y relleno #7886C7 cuando está marcado.

## Tipografías

- Principal: 'Poppins', sans-serif
- Secundaria: 'Nunito', sans-serif

## Iconos:
- Usa FontAwesome para los iconos de editar y eliminar.