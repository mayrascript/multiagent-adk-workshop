# Instrucciones para este repositorio

## Identidad visual de la guía

Para cambiar la apariencia o el tono de la guía del workshop, lee y aplica
`.agents/skills/mayrascript-brand/SKILL.md` y su referencia de marca.

La skill está versionada en este repositorio y su origen está registrado en
`workshop/site/brand-source.json`. El generador consume directamente sus tokens,
fuentes e isotipo. Mantén las adaptaciones de componentes en
`workshop/site/style.css`; no dupliques la paleta ni modifiques la copia de la
skill sin actualizar su procedencia.

Conserva los temas claro y oscuro, navegación móvil, progreso y copiado de
código. Comprueba `pnpm guide:build`, `pnpm typecheck` y las pruebas de la guía.
La salida pública vive en `docs/` y debe actualizarse junto con las fuentes.

MayraScript identifica a la autora y el workshop. Golden Rentals es el caso
ficticio: conserva sus datos y la skill didáctica `skills/instagram-copy/` del repositorio golden-rentals-studio.
Nunca incluyas `.env`, credenciales ni campañas personales en el sitio público.

## Separación del proyecto

Este repositorio contiene sólo la guía. La aplicación y los ejercicios viven en https://github.com/mayrascript/golden-rentals-studio. Usa projectRepository en workshop/site/steps.ts para enlaces de código y repository para enlaces editoriales. No añadas dependencias de la aplicación para compilar la guía. El inventario de TODO está en workshop/site/exercises.json.
