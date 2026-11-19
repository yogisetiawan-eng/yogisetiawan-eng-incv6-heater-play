# INCV6 incubator — heat & airflow 3D

Interactive 3D result of the INCV6 CO₂ incubator heater simulation (Elmer FEM, CAD-based model):
chamber wall temperatures vs the dew point at 37 °C / 90 %RH, airflow streamlines, sensors and heater zones Z1–Z12.

**Open it:** https://yogisetiawan-eng.github.io/yogisetiawan-eng-incv6-heater-play/

Current page: steady state of run v8 (room 18 °C). Coming next: a "play" version with sliders for every heater
zone, loop setpoints, room temperature and vaporizer power, recomputing the full 3D map and the control loops live
in the browser from precomputed Elmer basis fields.

Files: `index.html` (three.js viewer), `surfaces.json` (wall temperatures), `flow.json` (streamlines),
`zones.json` (heater zones, loops, operating condition). No build step; any static host works.
