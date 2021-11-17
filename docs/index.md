# Histogramas
**Nombre:** Histograma   
**Origen:** El término "histograma" fue acuñado en 1891 por el matemático estadístico inglés [Karl Pearson](https://es.wikipedia.org/wiki/Karl_Pearson).   
**Descripción:** Es la representación gráfica de una variable mediante un gráfico de barras, donde cada barra representa un rango de valores que puede tomar la variable y la altura de la misma representa la frecuencia de aparición de los valores de dicho rango.   
**Ejemplos de aplicación:** El histograma de una imagen representa la frecuencia relativa de los niveles de gris de la imagen. Se usa mucho en análisis preliminares de datos para comprender como son las variables.  

**Tipo de datos que se pueden representar:** Se usa para representar datos cuantitativos contínuos o discretos con un número significativo de valores.  
**Estructura de los datos:** Se necesita un simple array con los valores de una variable.   
**Limitaciones**

[Ejemplo de un **Histograma** creado con **d3**](https://miguellm-uoc.github.io/DataVisualizationPEC2/Histogram2.html)


# Small Multiple
**Nombre:** Small Multiple     
**Origen:** El primer uso conocido de este tipo de visualización fue en 1626 por Christopher Schein, que realizó una representación visual de las diferentes posiciones del sol en diferente tiempo. Posteriormente, el término fue popularizado por [Edward Tufte](https://en.wikipedia.org/wiki/Edward_Tufte).     
**Descripción:** es un conjunto de gráficas que usan los mismos ejes y escala, permitiendo compararlas fácilmente. Permite comparar un mayor número de variables sin confundir al usuario.  
**Ejemplos de aplicación:** Se usa para descubrir patrones en gráficos. https://www.juiceanalytics.com/writing/better-know-visualization-small-multiples

**Tipo de datos que se pueden representar:** Como es un conjunto de gráficos depende de los datos que pueda representar cada gráfica. De entrada parece que se puede representar cualquier tipo de datos.  
**Estructura de los datos:** Depende del gráfico que se use, pero generalmente serán datos agrupados.  
**Limitaciones** La ubicación de las gráficas debe seguir un orden lógico, para que el usuario pueda localizar fácilmente la información de interés.  


[Ejemplo de un **Small Multiple**, con gráficas de línea, creado con **d3**](https://miguellm-uoc.github.io/DataVisualizationPEC2/small_multiple2.html)
[Ejemplo de un **Small Multiple**, con histogramas, creado con **d3**](https://miguellm-uoc.github.io/DataVisualizationPEC2/small_multiple3.html)


# Hyperbolic trees
**Nombre:** Hyperbolic tree  
**Origen:** Fueron patentados en Estados Unidos por Xerox en 1996, pero la patente ya ha expirado.  
**Descripción:** Es un método de visualización de una estructura de tipo árbol, con una representación inspirada en la geometría hiperbólica. Se representa sobre un plano hiperbólico y se da más énfasis(más espaciados) a los nodos que están en el centro de la imágen, dando menos importancia(más comprimidos) a los elementos que están en la periferia.  
**Ejemplos de aplicación:** Usados para representar información web. Representación de taxonomías de especies animales.  

**Tipo de datos que se pueden representar:** Los datos tienen que tener definida una jerarquía  
**Estructura de los datos:** Tienen que tener una estructura jerárquica.  
**Limitaciones:** Si cada nodo tienen demasiados hijos la visualización resulta demasiado compleja 

[Ejemplo de un **Hyperbolic tree** creado con **d3**](https://miguellm-uoc.github.io/DataVisualizationPEC2/hyperbolicTree/)



## Datasets: 
**Sample Sales Data**, contiene datos de ventas con campos como Order Info, Sales, Customer, Shipping, etc. Usado originalmente por Pentaho DI Kettle, escrito por María Carina Roldán, Pentaho Community Member, BI consultant (Assert Solutions), Argentina. Licencia Creative Commons Attribution-Noncommercial-Share Alike 3.0 Unported License. Modificado por Gus Segura en junio de 2014.

**Mushroom (KIDR-MR)**, contiene la categorización taxonómica de setas de Korea. 
Licence CC BY-NC 4.0
GBIF.org (14 November 2021) GBIF Occurrence Download  https://doi.org/10.15468/dl.f9cpb9
Korea Institute of Science and Technology Information (2021). Mushroom (KIDR-MR). Occurrence dataset https://doi.org/10.15468/xivglt accessed via GBIF.org on 2021-11-17.

