# Generador de Calendario con Gestión de Tareas

Este proyecto es una aplicación web sencilla que permite generar un calendario mensual dinámico y añadir tareas para fechas específicas. El calendario muestra los días correspondientes al mes actual y permite agregar, editar y eliminar tareas. La interfaz es intuitiva y permite realizar las acciones de manera rápida y eficaz.

## Características

- Generación automática del calendario basado en el mes y año actual.
- Agregar tareas a fechas específicas.
- Editar o eliminar tareas con facilidad.
- Modal emergente para agregar nuevas tareas.
- Interacciones intuitivas para manejar las tareas (clic para editar, clic derecho para eliminar).

## Funcionalidades

1. **Generar calendario**: Al cargar la página, se genera automáticamente un calendario con los días del mes actual.
2. **Agregar tareas**: Los usuarios pueden seleccionar una fecha e introducir una tarea, la cual se mostrará en el día correspondiente del calendario.
3. **Editar tareas**: Clic en una tarea para modificar su descripción.
4. **Eliminar tareas**: Hacer clic derecho en una tarea para eliminarla.
5. **Modal de tarea**: Modal interactivo para añadir y gestionar tareas.

## Estructura del Proyecto

- `generateCalendar()`: Genera el calendario dinámico para el mes actual.
- `addTask()`: Permite agregar una nueva tarea al calendario en la fecha seleccionada.
- `editTask()`: Permite editar una tarea existente con un solo clic.
- `deleteTask()`: Elimina una tarea al hacer clic derecho sobre ella.
- `showAddTaskModal()` y `closeAddTaskModal()`: Controlan la apertura y cierre del modal para agregar tareas.

## Tecnologías Utilizadas

- **HTML5**: Estructura de la página.
- **CSS3**: Estilos para el diseño del calendario y el modal.
- **JavaScript**: Lógica de generación de calendario y gestión de tareas.

## Instalación

1. Clonar este repositorio:
   ```bash
   git clone https://github.com/tuusuario/nombre-repo.git
