# Aplicación To-Do con React y Vite

## Resumen:
Esta aplicación To-Do, desarrollada con React y Vite, facilita la gestión eficiente de tus tareas pendientes. Agrega, completa, y actualiza títulos, todo con la capacidad de filtrar por estado. La interfaz intuitiva agiliza la organización de tus actividades diarias.

## Características Principales:
### Gestión de Tareas:
- Añade nuevas tareas mediante el componente `Header`.
- Marca las tareas como completadas a través del componente `Todos`.

### Filtrado y Conteo:
- Filtra las tareas por estado (completadas, activas) con el componente `Footer`.
- Obtiene información en tiempo real sobre tareas activas y completadas.

### Actualización Dinámica:
- Actualiza dinámicamente la lista de tareas utilizando el hook personalizado `useTodos`.

### Interfaz Intuitiva:
- La interfaz fácil de usar permite una experiencia fluida para la gestión de tareas diarias.

## Estructura del Código:
### Componentes:
- `Header`: Encabezado para agregar nuevas tareas.
- `Todos`: Lista de tareas con opciones para marcar como completadas, editar y eliminar.
- `Footer`: Pie de página para filtrar tareas y mostrar estadísticas.
- `Copyright`: Componente de derechos de autor para dar créditos.

### Hooks Personalizados:
- `useTodos`: Gestiona el estado y las funciones relacionadas con las tareas.

## Uso de Tecnologías:
- **React:** Librería de JavaScript para construir interfaces de usuario interactivas.
- **Vite:** Herramienta de construcción rápida para aplicaciones web modernas.

## Instrucciones de Ejecución:
1. Clona este repositorio.
2. Instala las dependencias con el comando: `npm install`.
3. Inicia la aplicación con: `npm run dev`.
4. Abre el navegador y accede a `http://localhost:3000`.

## Colaboración y Contribuciones:
¡Contribuciones son bienvenidas! Si tienes ideas para mejorar la aplicación o encontraste algún problema, por favor crea un *issue* o envía una *pull request*.
