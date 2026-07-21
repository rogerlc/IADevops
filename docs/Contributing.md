# Guía de Contribución y Formato de Commits

## Formato de Commits (Conventional Commits)
Todos los commits deben seguir la siguiente estructura:

`<tipo>: <descripción corta>`

### Tipos permitidos:
- **feat**: Nueva funcionalidad.
- **fix**: Corrección de errores.
- **docs**: Cambios en documentación.
- **style**: Cambios de formato o estilo sin alterar código funcional.
- **refactor**: Refactorización de código sin cambiar comportamiento.
- **test**: Añadir o modificar pruebas.
- **chore**: Tareas de configuración, herramientas o dependencias.

## Reglas para Pull Requests (PR)
1. Ningún cambio se debe subir directamente a `master` (se requiere crear una rama y abrir PR).
2. Los títulos de los PR deben seguir el mismo formato que los commits.
3. Se requiere la revisión y aprobación de al menos 1 colaborador antes de hacer el merge.
