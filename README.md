# PENDULO FC · Táctica & Estadísticas ⚽

App web (un solo archivo, sin dependencias) para gestionar el equipo **Pendulo FC** en la **Liga La Barraca** (fútbol 7 amateur, El Último Diez Torneos).

Funciona 100% offline en el navegador y guarda todo localmente (localStorage). No necesita servidor ni instalación: se abre haciendo doble clic en `pendulo-fc.html`.

## Funcionalidades

- **Planteles** — carga de equipos y jugadores con número, posición y **foto**. Escudo del club configurable.
- **Pizarra táctica** — arrastrás jugadores en la cancha, dibujás **flechas de movimiento, pases, líneas, rotaciones, zonas y notas**, colocás pelota y rivales. Formaciones rápidas. Colores, deshacer/borrar.
  - **Animación de jugadas**: capturás pasos y reproducís la secuencia animada.
  - **Exportar imagen** (PNG) de la jugada para compartir.
- **Partidos** — carga en vivo de goles, asistencias, tarjetas, cambios, **convocatoria**, titulares y **puntaje (0–10) por jugador** con MVP automático.
- **Estadísticas** — acumulado y por partido, **rankings** (goleadores, asistencias, promedio, MVPs, presentismo, minutos, arco), **forma/racha**, **historial vs rivales** y **comparador de jugadores**.
- **Torneo** — tabla de posiciones y fixture.
- **Backup** — exportar/importar todos los datos en un archivo `.json`.

## Uso

Abrí `pendulo-fc.html` en cualquier navegador (Chrome/Edge/Firefox). Todos los datos quedan guardados en ese navegador.

## Publicado

Servido como sitio estático: la raíz (`index.html`) redirige a la app. Compatible con GitHub Pages, Netlify, Vercel o cualquier hosting estático.

---
Hecho con la ayuda de Claude Code.
