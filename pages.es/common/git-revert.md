# git revert

> Crea nuevas confirmaciones que revierten el efecto de los anteriores.
> Más información: <https://git-scm.com/docs/git-revert>.

- Revierte la confirmación más reciente:

`git revert {{HEAD}}`

- Revierte la quinta confirmación más reciente:

`git revert HEAD~{{4}}`

- Revierte una confirmación específica:

`git revert {{0c01a9}}`

- Revierte múltiples confirmaciones:

`git revert {{nombre_rama~5..nombre_rama~2}}`

- Revierte confirmaciones sin crear nuevas confirmaciones:

`git revert {{[-n|--no-commit]}} {{0c01a9..9a1743}}`
