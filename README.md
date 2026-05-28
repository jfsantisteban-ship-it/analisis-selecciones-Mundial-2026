# Análisis de Selecciones · Camino al Mundial 2026

Dashboard interactivo de análisis de fútbol que perfila el estilo de juego de las selecciones nacionales a partir de sus torneos recientes, usando datos abiertos de StatsBomb.

## 🔗 Ver el tablero

**[Abrir dashboard](https://jfsantisteban-ship-it.github.io/analisis-selecciones-Mundial-2026/)**

## ¿Qué incluye?

Tres torneos navegables — **Mundial 2022**, **Copa América 2024** y **Eurocopa 2024** — con cuatro vistas de análisis:

- **Comparador de selecciones** — radar de 9 ejes que perfila a cada equipo en ataque, defensa y progresión (posesión, circulación, verticalidad, altura, presión, xG, xG concedido, xT y balón parado).
- **Evolución 2022 → 2024** — cómo cambió el perfil de una selección entre torneos.
- **Análisis de partido** — shot map, mapa de calor, zonas de generación/envío y evolución de la red de pases en tres tramos, para cualquiera de los 147 partidos.
- **Comparador de jugadores** — 716 jugadores perfilados con radar de 8 ejes y vista beeswarm, con cálculo de similitud entre perfiles.

## Métricas destacadas

El tablero va más allá de las estadísticas básicas e incorpora métricas avanzadas de la analítica de fútbol moderna:

- **xG / xGA** — calidad de las ocasiones generadas y concedidas
- **xT (Expected Threat)** — valor de amenaza que aporta la circulación del balón
- **PPDA** — intensidad de la presión alta
- **Redes de pase por tramos** — estructura de circulación y cómo cambia con las sustituciones

## Notas metodológicas

- Los percentiles son **relativos a cada torneo** y no se comparan entre torneos distintos (cada uno tiene rivales y nivel diferentes).
- Las métricas reflejan el **rendimiento pasado**; no son una predicción del Mundial 2026.
- Los perfiles de jugador describen el rendimiento **en ese torneo** (muestra de 3 a 7 partidos), no la carrera del jugador.

## Tecnología

Aplicación HTML autocontenida, sin dependencias externas. Datos procesados con Python (statsbombpy, pandas, scikit-learn) y visualizaciones construidas en SVG.

---

Elaborado por Julio Santisteban · Datos: [StatsBomb Open Data](https://github.com/statsbomb/open-data)
