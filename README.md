
# Proyecto de Análisis de Regresión 2026

## Tema

Proyecto aplicado de regresión lineal múltiple usando el conjunto de datos Body Dimensions.

## Pregunta de investigación

¿Cómo se relacionan distintas medidas corporales con el peso de una persona adulta?

## Datos

Se usa la base `bdims.csv`, distribuida por OpenIntro.  
La unidad de observación es una persona adulta.  
La variable respuesta principal será `wgt`, peso corporal.

## Estructura del repositorio

- `data/`: contiene la base de datos.
- `R/`: contiene los scripts de limpieza, análisis exploratorio, modelos y diagnósticos.
- `informe/`: contiene el avance, informe final y archivos fuente.
- `output/`: contiene figuras y tablas generadas por el código.

## Cómo reproducir el análisis

1. Abrir el proyecto en RStudio.
2. Ejecutar los scripts en este orden:

```r
source("R/01_limpieza.R")
source("R/02_eda.R")
source("R/03_modelos.R")
source("R/04_diagnosticos.R")
