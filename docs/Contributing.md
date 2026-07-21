# Guía de Contribución y Formato de Commits

## Formato de Commits (Conventional Commits)

Todos los commits deben seguir la siguiente estructura:

`<tipo>: <descripción corta>`

### Tipos permitidos

- **feat**: Nueva funcionalidad.
- **fix**: Corrección de errores.
- **docs**: Cambios en documentación.
- **style**: Cambios de formato o estilo sin alterar código funcional.
- **refactor**: Refactorización de código sin cambiar comportamiento.
- **perf**: Mejoras de rendimiento.
- **test**: Añadir o modificar pruebas.
- **build**: Cambios en el sistema de compilación o dependencias.
- **ci**: Cambios en integración o despliegue continuo.
- **chore**: Tareas de mantenimiento, configuración o herramientas.
- **revert**: Revertir un cambio anterior.

## Reglas para Pull Requests (PR)

1. Ningún cambio se debe subir directamente a `main`; se requiere crear una rama y abrir un Pull Request.
2. Los títulos de los Pull Requests deben seguir el mismo formato que los commits.
3. Se requiere la revisión y aprobación de al menos un colaborador antes del merge.
4. Todas las conversaciones de revisión deben resolverse antes del merge.
