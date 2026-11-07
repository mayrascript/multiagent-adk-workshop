# Tu próximo equipo no es humano

Guía paso a paso del workshop de orquestación de agentes con Google ADK, de **MayraScript**.

[Leer la guía pública](https://mayrascript.github.io/multiagent-adk-workshop/) · [Abrir el proyecto del taller](https://github.com/mayrascript/golden-rentals-studio)

## Para realizar el taller

Clona el proyecto de ejercicios:

```sh
git clone --branch starter https://github.com/mayrascript/golden-rentals-studio.git
cd golden-rentals-studio
pnpm install --frozen-lockfile
pnpm workshop:check setup
pnpm dev
```

Sigue la [preparación](workshop/guide/01-preparacion.md) para instalar las herramientas. En el nuevo repositorio, `starter` contiene los 14 TODO y `main` la solución completa. Las etiquetas `workshop-v1-starter` y `workshop-v1-solution` conservan la versión inicial de esta edición.

## Para mantener la explicación

Este repositorio contiene el contenido, las ilustraciones, tu guía de facilitación y el sitio estático. La aplicación, los agentes y sus dependencias se mantienen en **golden-rentals-studio**.

```sh
pnpm install --frozen-lockfile
pnpm guide:dev
```

Antes de publicar: `pnpm guide:build`, `pnpm typecheck`, `pnpm lint` y `pnpm test`. Se versionan las fuentes y la salida de `docs/`. GitHub Pages mantiene la dirección pública actual.

Consulta [cómo mantener la guía](docs/guide-site.md). La identidad visual usa la skill MayraScript versionada en `.agents/skills/mayrascript-brand/`. Golden Rentals sigue siendo el caso ficticio del taller.

[LICENSE](LICENSE) · [NOTICE](NOTICE)
