# Terapia Luis Moreno

Sitio web para la consulta del psicólogo Luis Moreno en Quito.

## Trabajar con hivemind

Este repo ya trae la configuración para usar el plugin **hivemind** en Claude Code (`.claude/settings.json`).

1. Clona el repo y abre Claude Code dentro de la carpeta.
2. Acepta confiar en la carpeta. Claude Code te pedirá instalar el marketplace `hivemind-marketplace` y el plugin `hivemind`; acepta ambos.
3. La primera vez, corre en el chat:

   ```text
   /hivemind:init-project
   ```

   Te hará unas preguntas (nombre, tipo de proyecto, usuarios, casos de uso, stack) y dejará listo `PROJECT.md`, el backlog en `tasks/` y el estado en `state/`.

Para actualizar hivemind más adelante, dentro de Claude Code corre `/hivemind:update`.
