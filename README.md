<div align="center">
<h2>
    <em>Mi</em> cv formato JSON
</h2>
## Descripción

Este repositorio contiene una versión minimalista de un portfolio/CV en formato JSON, renderizado con **Astro** y componentes en `src/components`. El proyecto toma como base el esquema de `jsonresume.org` y un diseño inspirado en:
<p>
Esquema del JSON de CV de <a href="https://jsonresume.org/schema/">jsonresume.org</a>
</p>

<p>
Basado en el diseño de <a href="https://github.com/BartoszJarocki/cv">Bartosz Jarocki</a>

</p>
<p>
Idea del diseño de <a href="https://github.com/midudev/minimalist-portfolio-json">midudev</a>

</p>

</div>

## Instalación (PowerShell)

Recomendado: usar `pnpm` (el repositorio ya contiene `pnpm-lock.yaml`). Desde la raíz del proyecto:

```powershell
pnpm install
pnpm dev    # desarrolla en local
# o para producción:
pnpm build
pnpm preview
```

Notas: en algunos entornos `pnpm` puede pedir aprobar builds nativos (esbuild/sharp). Si aparecen advertencias, ejecutar `pnpm approve-builds` y confirmar según prefieras.

## Scripts disponibles

Los scripts definidos en `package.json` son:

- `dev`: `astro dev`
- `start`: `astro dev`
- `build`: `astro check && astro build`
- `preview`: `astro preview`
- `astro`: `astro`

## Contribuir

1. Haz un fork y crea una rama con tu cambio: `git checkout -b feat/mi-cambio`
2. Asegúrate de ejecutar `pnpm install` y `pnpm build` localmente.
3. Envía un PR describiendo los cambios.

## 🔑 Licencia

[MIT](LICENSE.txt)
