# Proyecto_Econometria_1
---

# Análisis del precio de la vivienda en Colombia 🇨🇴

Este repositorio contiene un proyecto de econometría aplicada que estudia los determinantes del precio de la vivienda en Colombia, con foco en diferencias por tipo de propiedad y ubicación geográfica.

## Objetivo

Estimar modelos hedónicos del precio de la vivienda utilizando datos masivos de propiedades listadas en línea. En particular, se comparan:

* Medellín vs el resto del país
* Bogotá D.C, Medellín y Cali (Big3) vs el resto

Se analizan por separado apartamentos y casas.

## Metodología

Se implementa un modelo de regresión lineal (OLS) con forma semi-logarítmica y errores robustos a heterocedasticidad (HC3), evaluando:

* Impacto de atributos físicos (tamaño, cuartos, baños)
* Prima de localización geográfica
* Diagnósticos del modelo (heterocedasticidad, RESET, multicolinealidad)
* Comparación de coeficientes y visualizaciones

```

## Datos: se pueden descargar con el siguiente link: https://drive.google.com/file/d/1-dYEDcBWE8vJwiNrA-C4DQKFxYmgPHYB/view?usp=sharing

* Más de 150.000 registros de propiedades en Colombia
* Variables: precio, superficie, cuartos, baños, ciudad, tipo de propiedad
* No incluye fechas ni coordenadas geográficas

Por limitaciones de tamaño, los datos completos no se incluyen en este repositorio. Para obtenerlos:

1. Descarga el archivo original desde \[Drive / fuente] (especificar).


## 🖥️ Cómo reproducir

1. Clona este repositorio
2. Instala los paquetes:

```bash
pip install -r requirements.txt
```

3. Abre el notebook: Cambios en el Precio de la Vivienda en Colombia 

## Principales hallazgos

* Los apartamentos en las tres principales ciudades cuestan en promedio 80% más que en el resto del país.
* En casas, Medellín muestra un descuento relativo del 15%.
* El tamaño y el número de baños son los atributos físicos más importantes.
* Se detectó heterocedasticidad (corregida), cierta colinealidad, y posible mala especificación.

## Herramientas y librerías

* Python 3.10
* pandas, numpy, statsmodels, matplotlib, seaborn, scikit-learn

## Referencias

* Rosen, S. (1974). “Hedonic prices and implicit markets.”
* Malpezzi, S. (2003). “Hedonic pricing models: A selective and applied review.”
* Wooldridge, J. M. (2013). *Introductory Econometrics*.

## Licencia

MIT License
