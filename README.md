# Agentes autónomos — Actividad 04

## Canción
Sison Beats/Nemesis & Luis7Lunes — *El Pecado Original*
https://www.youtube.com/watch?v=-5OkuVBiFf4

## Concepto y uso del programa
Interpreto la canción a través de tres familias de agentes que conviven en el mismo lienzo. El **physarum** es el rastro pagano: colectivo, anónimo, orgánico — nadie decide nada individualmente, el patrón emerge de miles de agentes moviéndose sobre el mismo mapa de rastro compartido. El **campo de flujo** (espiral con bandas concéntricas, sin ruido de por medio) es lo sagrado: orden geométrico que estructura el espacio de fondo. **Sison** y **Luis7Lunes** son los únicos dos agentes con nombre propio — se mueven entre ambas fuerzas, cada uno con su propia sensibilidad al orden y al impulso.

## Programa
https://github.com/n4ndeZzz/physarum-core

Controles (todo por teclado, nada de mouse):
- **Q/A** — sensor distance · **W/S** — sensor angle · **E/D** — rotation angle · **R/F** — move distance (los cuatro parámetros del rastro pagano)
- **↑/↓** — decay del rastro
- **T/G** — cuánto pesa lo sagrado sobre todo el sistema (pagano y los dos agentes con nombre a la vez)
- **Espacio** — profanación: ráfaga de caos que rompe el orden por un instante

## Score (verificado en tiempo real con la canción)

| Pasaje | Intención | Qué toco |
|---|---|---|
| 0:00–0:12 — intro, solo beat | El pecado aún no se comete; silencio antes del acto | `sacredWeight` alto (**T**), rastro casi invisible |
| 0:12–0:35 — primer verso | La primera voz empieza a profanar el silencio | bajo con **G** gradual, subo `MD` (**R**) |
| 0:35–0:50 — transición | Respiro entre las dos voces | sostengo, dejo asentar el rastro |
| 0:50–1:15 — segundo verso | La segunda voz entra, el pecado se profundiza | `sacredWeight` bajo, `SA`/`RA` más abiertos (**W**/**E**) |
| 1:15–1:35 — cruce de las dos voces | El choque entre sagrado y pagano, en su punto más intenso | **espacio** (profanación) justo acá |
| 1:35–2:02 — cierre | Consecuencia, no redención — queda la marca | `sacredWeight` sube de nuevo, `decay` baja un poco |

## Autoevaluación

1. Cumplimiento del encargo — ✅ **Cumple.** Tiempo real, web, tres familias de agentes (physarum/flow field/steering) combinadas con una lógica justificada, score verificado contra la canción real.
2. Comprensión y verificación — ✅ **Cumple.**
3. Diseño e intención — ✅ **Cumple.**
4. Interpretación humana — ✅ **Cumple.** Score y controles existen, se corrieron en tiempo real junto a la canción y los tiempos coincidieron.
