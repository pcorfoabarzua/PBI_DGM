# Changelog
Todos los cambios relevantes del proyecto **PBI_DGM** se documentan en este archivo.

El formato está basado en *Keep a Changelog* y el versionado sigue una lógica incremental por hitos del proyecto.

---

## [Unreleased]
### Added
- 

### Changed
- 

### Fixed
- 


---


### Fixed
- Mejora en la semántica de las tablas e indicadores de muestreo.
- Diferenciación explícita entre ausencia de datos y valores cero en KPI operacionales.

---

### Changed

- Ajuste en la presentación del dashboard para mejorar la interpretación de los indicadores de cumplimiento.
- Revisión de la lógica de las medidas asociadas a requerimientos de viajes y muestreos, considerando la disponibilidad parcial de PB_REQ_MUESTREO.

### Fixed

- Mejora en la comunicación visual de estados donde no existen requerimientos definidos para el período o proyecto seleccionado.

---

## [2026-04-14]
### Fixed
- Corrección de datos erróneos en la dimensión **Dim_Barcos** mediante transformaciones en Power Query.
- Normalización de atributos para mejorar la consistencia en análisis por barco.
- Actualización de visualizaciones que utilizan nombres de barcos corregidos.

---

## [2026-03-31]
### Added
- Dashboard de **Bentónicos**.
- Tooltips para:
  - Número de muestreos biológicos.
  - Longitud.

---

## [2026-03-25]
### Fixed
- Corrección de medidas:
  - Viajes totales.
  - Viajes requeridos.
  - Viajes totales OC.

---

## [2026-02-10]
### Added
- Inicio del proyecto DGM Power BI:
  - Pelágicos.
  - Crustáceos.
  - Aguas profundas.