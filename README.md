#  **Repositorio de análisis de datos** 📈💰📊 👨‍💻 

Este repositorio está enfocado en el análisis y ciencia de datos con Python. Se lleva a cabo el proceso ETL ( Extraction, Transformation and Load) mediante herramientas como MySQL, Python y Power BI para la obtención, limpieza, procesamiento y visualización de datos.

**NOTA**: Algunos análisis siguen en construcción y continuamente serán actualizados.

## [Housing Colombia](https://www.kaggle.com/datasets/julianusugaortiz/colombia-housing-properties-price)
Este dataset tiene información del precio, área construida, cantidad de habitaciones, ubicación, descripción, entre otras características de 1 millón de inmuebles en Colombia durante 2020 y 2021.

### Conclusiones

### Información adicional

## [Netflix Titles](https://github.com/pablocarmona1527/Data_analyst/blob/main/netflix_titles.csv)
En este dataset se encuentra información de los shows y películas de Netflix por año de estreno y año de adición al catálogo. Además, se tiene información del Rating de cada show y película. 
### Conclusiones
* Fueron usados 7 modelos de Machine Learning para predecir la cantidad de temporadas que tendría un Show de TV de Netflix a partir del actor principal, país del show, director, rating, entre otras variables.
* El mejor modelo fue el de Random Forest Classifier con un puntaje recall de 0.69, es decir, predijo correctamente el 69% de los datos.
* Las variables que más influyen para calcular la cantidad de temporadas son el actor principal (23.12%) y la categoría principal del show (19.99%).
* La información podría ser de ayuda para Netflix en su selección de actores y categoría de cada show para estimar el potencial de éxito de sus shows de TV.
### Información adicional:
* El dataset tiene 8807 registros y 12 columnas.
* Hay casi 3 veces más películas que shows de TV.
* Estados Unidos, India y Reino Unido son los mayores productores de shows.
* Menos del 30% de los shows de TV consiguen una segunda temporadas.
* Las categorías con más shows son Dramas, comedias y shows internacionales.
* Entre 2016 y 2020 fue donde más shows se estrenaron.
* Estados Unidos es el país con mayor producción de Documentales, dramas y comedias.

**Dashboard en Power BI**

![](https://github.com/pablocarmona1527/Data_analyst/blob/main/netflix.png)

## [Space missions](https://github.com/pablocarmona1527/Data_analyst/blob/main/mission_launches.csv)
En este dataset se tiene información de las misiones espaciales desde 1957 por parte de diversas compañías espaciales. Se tiene información del ligar de lanzamiento del cohete, nombre del cohete, dinero invertido, estado del cohete y resultado de la misión.
### Conclusiones
* Se usaron 7 modelos de Machine Learning para predecir si una misión tendrá éxito o fracaso basada en el país de lanzamiento, la compañía espacial, el costo, entre otros.
* El modelo que se ajustó mejor a los datos fue K-nearest neighbors. Obtuvo un puntaje de 0.9 y un F1-score de 0.87, es decir, predijo correctamente el 87% del éxito o fracaso de las misiones.
### Información adicional:
* El dataset inicial tiene 4324 registros y 7 columnas.
* El 89.9% de las misiones espaciales fueron un éxito.
* Solo el 18.3% de los cohetes usados en misiones siguen activos.
* Los países con más misiones son Rusia, USA y Kazakhstan.
* Entre 1965 y 1976 es donde más misiones se han lanzado.
* Las compañías que más misiones exitosas han lanzado son RVSN URSS, Arianespace y CASC.
* Los países que más dinero han invertido en misiones son USA, Rusia y Kazakhstan.
* Típicamente n los meses de noviembre y diciembre se lanzan misiones con mayor costo.

**Dashboard en Power BI**
![](https://github.com/pablocarmona1527/Data_analyst/blob/main/space_dashboard.png)

## [Amazon products](https://www.kaggle.com/datasets/lokeshparab/amazon-products-dataset)
Este dataset  tiene información de más de 500 mil productos de Amazon con información de la categoría, el precio real, el precio de descuento, la calificación de cada producto, entre otras características.

### Análisis hechos

