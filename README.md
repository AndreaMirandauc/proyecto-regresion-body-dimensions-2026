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

## Estructura sugerida

```text
.
├── README.md
├── avance_body_dimensions.tex
├── avance_body_dimensions.R
├── data/
│   └── README.md
├── figures/
│   └── .gitkeep
└── output/
    └── .gitkeep
```

## Cómo reproducir el avance

1. Abrir RStudio.
2. Abrir el archivo `avance_body_dimensions.R`.
3. Ejecutar el script completo.
4. Revisar que se creen las figuras en la carpeta `figures/` y las salidas en `output/`.
5. Compilar `avance_body_dimensions.tex` con XeLaTeX o subirlo a Overleaf.

## Paquetes necesarios

El script usa principalmente funciones base de R. El paquete `car` se usa de forma opcional para calcular VIF.

```r
install.packages("car")
```

## Nota ética

Los datos no identifican directamente a personas. Las conclusiones deben presentarse como asociaciones/predicciones, no como causalidad.

