# Flujos MOP — Censos de flujo vehicular (TMDA) de Chile

Visor interactivo de los **censos de tránsito del Plan Nacional de Censo Vial (PNCV)** de la
Dirección de Vialidad del MOP, georreferenciados sobre la red vial nacional, con la ubicación
de las plazas de peaje.

**Ver el visor:** https://romedinag-tech.github.io/flujosmop/

## Qué muestra

- **Serie 2014–2025** de TMDA (Tránsito Medio Diario Anual) · 1.402 estaciones censales
- Dos lentes: **flujo por rama (sentido)** y **flujo por estación (total)**
- Coropleta comunal por quintiles, zonificación con tendencia por año, y **212 plazas de peaje**
- Mapa con base, satélite, vialidad y cuerpos de agua
- **Capa de concesiones de Santiago:** 184 pórticos y plazas con flujo y perfil horario

Lo que el visor **dibuja** usa la *coordenada vigente* y el *rol vigente*: la coordenada publicada venía
desplazada en 54 estaciones, y el azimut de cada flecha se mide contra el eje del rol que la red vigente
tiene. La versión publicada y lo que cambió están en [`version.json`](version.json).

## Fuentes

- Puntos censales y red vial: ArcGIS REST de la Dirección de Vialidad, MOP
  (`VIALIDAD/Plan_Nacional_de_Censos`, `VIALIDAD/Red_Vial_Chile`, `VIALIDAD/Infraestructura_Vial`).
- Datos públicos del Ministerio de Obras Públicas de Chile.

Visor autocontenido (un solo `index.html`). Las teselas del mapa requieren conexión a internet.
