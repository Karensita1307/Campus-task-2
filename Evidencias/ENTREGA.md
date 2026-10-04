# Taller CampusTasks

## Objetivo

Este taller usa la implementación de **actualización y eliminación de tareas** en CampusTasks, verificando tanto el backend como el frontend. fileciteturn0file0L2-L8

## Backend

Se implementaron y probaron:

- Método `actualizar` en `tareas.service.ts`.
- Ruta `PATCH /tareas/:id` en el controlador.
- Manejo de tareas inexistentes mediante respuesta **404 Not Found**.
- Método `eliminar` en el servicio.
- Ruta `DELETE /tareas/:id`.
- Pruebas unitarias e integración para los casos exitosos y de error.
- Prueba manual del backend usando la base de datos real. fileciteturn0file0L11-L30

## Frontend

Se agregaron:

- Botón **Editar** para cada tarea y su prueba de componente.
- Botón **Eliminar** para cada tarea y su prueba de componente.
- Prueba manual desde `http://localhost:4200`.

## Resultado

La funcionalidad permite **editar y eliminar tareas**, validando su funcionamiento mediante pruebas unitarias, pruebas de integración y una comprobación manual completa.
