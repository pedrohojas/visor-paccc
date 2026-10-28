# Visor de medidas de adaptación — PACCC, PARCC y PSA (Chile)

Visor de la base nacional de medidas de los Planes de Acción Comunal (PACCC), Regionales (PARCC) y Sectoriales de Adaptación (PSA) al cambio climático de Chile. Versión de trabajo, Convenio MMA N°20260121_MMA_2_SbN_2026, programa DPS.

Las clasificaciones, resúmenes y síntesis fueron generados por modelos de lenguaje a partir del texto de cada instrumento; cada etiqueta cita la página y el pasaje que la respalda y debe verificarse antes de su uso oficial.

## Archivos
- `index.html` — página autocontenida (D3 7.9.0 y TopoJSON 3.0.2 desde cdnjs).
- `datos.json` — medidas en formato columnar, territorio, cobertura, población (INE, Censo 2024).
- `detalle.json` — textos por medida (se carga al abrir fichas).
- `resumenes.json` — síntesis por región, comuna, PARCC y PSA.
- `comunas.topojson` — límites comunales, Mapoteca BCN (SIIT, 2019), simplificados.

En esta versión pública no está el botón "Analizar esta selección", que solo funciona dentro de claude.ai.

## Actualizar
Desde `analisis_medidas/`: `python3 scripts/p3_payload_v3.py`, copiar `04_base/visor/*.json` a esta carpeta y hacer commit.
