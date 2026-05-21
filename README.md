# Proyecto EYP2307 - Body Dimensions

Este repositorio contiene el avance del proyecto aplicado de Análisis de Regresión usando el conjunto de datos `Body Dimensions` de OpenIntro.

## Pregunta inicial

¿Qué medidas corporales permiten explicar y predecir razonablemente el peso de una persona adulta mediante un modelo de regresión lineal múltiple?

## Datos

- Fuente: OpenIntro, conjunto `bdims`.
- URL oficial del CSV: https://www.openintro.org/data/csv/bdims.csv
- Unidad de observación: persona adulta físicamente activa.
- Respuesta principal: `wgt`, peso en kilogramos.
- Predictores candidatos: `hgt`, `age`, `sex`, diámetros corporales y perímetros corporales.

## Estructura
1. avance_Visualizacion.md : Visualización directa en GitHub del código Rmarkdown
2. avance_rmarkdown: Código en Rmarkdown del avance
3. avance_latex.tex : Código para generar el documento del informe , las imagenes que se utilizan están subidas al proyecto
4. Base de datos: bdims.csv


## Paquetes necesarios

El script usa principalmente funciones base de R. El paquete `car` se usa de forma opcional para calcular VIF.

```r
install.packages("car")
```

## Nota ética

Los datos no identifican directamente a personas. Las conclusiones se presentan como asociaciones/predicciones, no como causalidad.

