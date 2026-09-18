# Prácticas guiadas con MakeCode Arcade

Estas prácticas trasladan la programación por bloques a [MakeCode Arcade](https://arcade.makecode.com/). Primero consigue que funcione la versión mínima; después personaliza solo lo indicado.

## AR3-1 · Nave, proyectil y asteroide

!!! example "Ejemplo de resultado"
    La nave dispara; el proyectil destruye un asteroide y suma un punto; un choque con la nave resta una vida.

1. Crea un proyecto llamado `AR3_1_ApellidoNombre`.
2. Crea una nave **Player** y muévela únicamente en vertical.
3. Al pulsar A, crea un proyectil hacia la derecha.
4. Crea un asteroide **Enemy** que aparezca por la derecha y avance hacia la izquierda.
5. Si el proyectil toca el asteroide, destruye ambos y suma un punto.
6. Si el asteroide toca la nave, resta una vida.
7. Prueba hasta conseguir tres puntos.

**Entrega:** enlace y captura con tres puntos.

## AR3-2 · Laberinto con tilemap

!!! example "Ejemplo de resultado"
    El jugador recoge 5 objetos y solo entonces la meta muestra la pantalla de victoria.

1. Crea un proyecto nuevo y un sprite **Player**.
2. Diseña un mapa pequeño con paredes, suelo, cinco objetos y una meta.
3. Marca las paredes para que no puedan atravesarse.
4. Al recoger un objeto, destrúyelo y suma un punto.
5. Al llegar a la meta, gana solo si la puntuación es 5.
6. Añade un mensaje que avise si todavía falta algún objeto.
7. Prueba dos recorridos diferentes.

**Entrega:** enlace, captura del mapa y lista de las dos pruebas.

## AR3-3 · Una función para crear enemigos

!!! example "Ejemplo de resultado"
    La función `crearEnemigo` contiene creación, posición y velocidad; un temporizador la llama cada dos segundos.

1. Abre una copia de AR3-1.
2. Crea una función llamada `crearEnemigo`.
3. Mueve dentro de la función los bloques que crean y desplazan el asteroide.
4. Llama a la función cada dos segundos.
5. Haz aleatoria la posición vertical del enemigo.
6. Comprueba que aparecen al menos cinco enemigos.
7. Explica en dos frases qué evita repetir la función.

**Entrega:** enlace y explicación en Aules.

## AR3-4 · Prueba y mejora

!!! example "Ejemplo de resultado"
    `Problema: conserva puntos al reiniciar | Cambio: fijar puntos a 0 | Resultado: reinicia correctamente`.

1. Intercambia tu enlace con un compañero.
2. Juega durante dos minutos sin modificar el proyecto.
3. Anota un fallo, una dificultad y una mejora.
4. Recupera tu proyecto y corrige solo un problema.
5. Cambia el número de versión de `v01` a `v02`.
6. Comprueba que la corrección no rompe la puntuación ni las vidas.

**Entrega:** enlace v02 y tabla `problema - cambio - resultado`.
