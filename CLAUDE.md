# CLAUDE.md — mermail-skills (fork)

## Qué es esto

Fork de `Nudgen-Marketing/mermail-skills` que existe para sostener una
contribución hacia el upstream (la skill de expense ledger). No es un
proyecto propio: es la rama de trabajo de un pull request ajeno.

## El negocio, en cinco líneas

El valor está en que la contribución sea aceptada arriba. Todo lo que
dificulte ese PR — reformateos, cambios en ficheros ajenos a la
contribución, divergencia gratuita del upstream — resta aunque «mejore» el
código.

## Cómo se trabaja aquí

```bash
npm ci
```

Las pruebas y validaciones son las que defina el `package.json` del
upstream; se corren antes de proponer nada.

## Restricciones duras

- **Divergencia mínima**: solo los cambios que la contribución necesita.
  Mejoras generales del proyecto se proponen upstream, no se acumulan aquí.
- El fork se actualiza trayendo del upstream, no editando en paralelo.

## Commits y PRs

Mensajes en **español** para el trabajo propio del fork (los PRs hacia el
upstream siguen las convenciones del upstream). Nunca se toca `main`
directamente ni se fusiona nada: rama + pull request, y la fusión la decide
el dueño del repo.

Todo PR cierra con estas tres líneas rellenas:

- **Qué cambia y por qué:**
- **Probado y descartado:**
- **Queda a medias:**

Si trabajando aquí descubres que algo de este archivo ya no es verdad, dilo
en el PR.
