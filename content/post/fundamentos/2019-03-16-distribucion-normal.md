---
title: La Distribución Normal
date: 2019-03-16
draft: False
categories: ["fundamentos"]
tags: ["normal", "visualizaciones", "distribucion", "gráficos", "gaussiana"]
myVar: "myValue"

weight: 10
image: img/visualizaciones/visualizaciones_basicas.png
authorAvatar: datalaria-logo.png
---

En esta entrada, vamos a centrarnos en la distribución normal, la cual ya fue brevemente introducida en el post [estadística descriptiva](https://www.datalaria.com/post/fundamentos/2018-10-07-estadistica-descriptiva/).

La distribución normal o gaussiana (o también conocida como Laplace-Gauss) es una de las distribuciones de probabilidad de variable continua que con más frecuencia aparece en estadística y en la teoría de probabilidades.

La distribución normal (en ocasiones llamada distribución gaussiana) es la distribución continua que se utiliza más comúnmente en estadística.

- La distribución normal o distribución gaussiana consiste en la distribución deseada para todos nuestros datos. Aunque debido a su importancia se dedicará una entrada específica a este tipo de distribución, explicado de manera breve, se trata de una función simétrica con forma de campana que permite modelar numerosos fenómenos de la naturaleza. La gran ventaja que presenta disponer de variables cuyos datos se asimilan a este tipo de distribución es que su distribución puede caracterizarse en función de su desviación estándar de la siguiente manera:

![Normal](/img/estadistica_descriptiva/normal.png):

- **[Gráficos de tarta](#grafico_tarta)**

*Nota: Para todos los ejemplos (excepto para los gráficos de línea por sus características) se va a utilizar como dataset el fichero train.csv un subconjunto de 891 individuos representativo de la población del Titanic utilizado para el entrenamiento de modelos de Aprendizaje automático.*

## <a name="grafico_tarta"></a>Gráficos de tarta

Los gráficos de tarta o circulares (en inglés *pie charts*) son utilizados para representar la proporción de los datos de una variable o característica según su valor respecto al total de los mismos. Este tipo de gráficos presentan multitud de variantes y son ampliamente utilizados debido a su sencillez de preparación e interpretación. Sin embargo, muchas veces se abusa de este tipo de gráficos o se utilizan indebidamente (ver el siguiente [artículo sobre el mal uso de los gráficos de tarta](https://www.elartedepresentar.com/2011/11/las-tartas-son-para-el-postre-5-razones-por-las-que-no-uso-graficos-circulares/)).

 * Ejemplo: Proporciones de pasajeros del Titanic por estatus socioeconómico

![Grafico_tarta](/img/visualizaciones/grafico_tarta.png)


#### Fuentes de interés:
- Kaggle – [Titanic Machine Learning from Disaster](https://www.kaggle.com/c/titanic)
- Datos abiertos del Gobierno de España – [datos.gob.es](https://datos.gob.es/es)
- El Arte de Presentar – [Las tartas son para el postre: 5 razones por las que no uso gráficos circulares](https://www.elartedepresentar.com/2011/11/las-tartas-son-para-el-postre-5-razones-por-las-que-no-uso-graficos-circulares/)
- Curso _“[Essential Statistics for Data Analysis using Excel](https://courses.edx.org/courses/course-v1:Microsoft+DAT222x+1T2017/course/)”_ perteneciente al Microsoft Data Science Program
- Catálogo de Visualización de Datos - [Catálogo de Visualización de Datos](https://datavizcatalogue.com/ES/)
