# Flujos MOP — Censos de flujo vehicular (TMDA) de Chile

Visor interactivo de los **censos de tránsito del Plan Nacional de Censo Vial (PNCV)** de la
Dirección de Vialidad del MOP, georreferenciados sobre la red vial nacional, con la ubicación
de las plazas de peaje.

**Ver el visor:** https://romedinag-tech.github.io/flujosmop/

## Qué muestra

- **Serie 2014–2025** de TMDA (Tránsito Medio Diario Anual) · 1.405 estaciones censales
- Dos lentes: **flujo por rama (sentido)** y **flujo por estación (total)**
- Coropleta comunal por quintiles, zonificación con tendencia por año, y **212 plazas de peaje**
- Mapa con base, satélite, vialidad y cuerpos de agua

## Fuentes

- Puntos censales y red vial: ArcGIS REST de la Dirección de Vialidad, MOP
  (`VIALIDAD/Plan_Nacional_de_Censos`, `VIALIDAD/Red_Vial_Chile`, `VIALIDAD/Infraestructura_Vial`).
- Datos públicos del Ministerio de Obras Públicas de Chile.

Visor autocontenido (un solo `index.html`). Las teselas del mapa requieren conexión a internet.
