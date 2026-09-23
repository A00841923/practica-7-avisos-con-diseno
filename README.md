# Práctica 7 — Avisos con diseño

Código de arranque de la Práctica 7 de TC2007B.

Es la app de Avisos de la Práctica 6 **terminada**: login, sesión cifrada,
refresh y el tablón con su rol. Todo funciona. Lo que le falta es el tema de la
práctica: se ve como cualquier app de ejemplo, con el tema que Material trae por
omisión.

Ya trae lo que no es el tema de la práctica:

- `app/src/main/res/font/` — las cuatro fuentes, como instancias estáticas TTF.
- `app/src/main/res/drawable/` — los íconos que Material no trae.
- `licencias/` — la licencia OFL de las dos familias tipográficas.

## Cómo empezar

1. Clona el repositorio y ábrelo en Android Studio.
2. Espera a que Gradle sincronice y corre la app: entra con tu cuenta de la
   Práctica 6 y ve el tablón.
3. Sigue la guía: https://startdroid.com/practicas/avisos-con-diseno.html

## Cómo trabajar

Haz un commit en cada checkpoint de la guía:

    git add -A ; git commit -m "checkpoint a2"

Si algo se rompe sin remedio, `git restore .` te regresa al último checkpoint bueno.

Los experimentos que rompen el código a propósito van en una rama:

    git switch -c experimento-a4                  # antes de romper nada
    git add -A ; git commit -m "experimento-a4"   # al terminar: guárdalo EN la rama
    git switch main                               # el código bueno vuelve intacto

Sin el commit en la rama, `git switch main` se lleva tus cambios contigo y
el código roto aparece en `main`.

## Uso de IA

Todo commit con código generado por IA debe declararlo con un trailer
`Co-Authored-By`. Ver la política completa en la guía.

## Entrega

Ver la rúbrica en la guía. Al subir tu repositorio, sube también la rama del
experimento: `gh repo create … --push` solo sube la rama actual.

    git push origin --all
