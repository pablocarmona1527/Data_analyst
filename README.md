#  **Repositorio de análisis de datos** 📈💰📊 👨‍💻 

Este repositorio está enfocado en el análisis y ciencia de datos con Python. Se lleva a cabo el proceso ETL ( Extraction, Transformation and Load) mediante herramientas como SQL, Python y Power BI para la obtención, limpieza, procesamiento y visualización de datos.

**NOTA**: Algunos análisis siguen en construcción y continuamente serán actualizados.

## [Intentos de suicidio en Medellín](https://github.com/pablocarmona1527/Data_analyst/blob/main/suicidios_colombia/intento_suicidio.csv)
## Conclusiones
* Fue implementado un proceso de Machine Learning mediante eliminación recursiva de características con validación cruzada (RFECV) a 5 modelos de clasificación para predecir si una persona fallece tras un intento de suicidio.
* Los mejores modelos fueron Xtreme Gradient Boosting, Linear Support Vector Machine y Logistic Regression.
* Dichos modelos fueron sometidos a validación de hiperparámetros y todos consiguieron puntajes f1 muy similares.
* El mejor puntaje fue 0.78 lo cual indica que el 78% de los datos fueron clasificados correctamente. 
* Estos modelos pueden ser usados para determinar si una persona con problemas familiares, problemas de pareja o recibe acompañamiento psicológico es propensa a cometer un intento de suicidio.

## Información adicional
* El dataset inicial tiene 18507 filas y 19 columnas.
* Las mujeres llevan a cabo casi el doble de intentos de suicidio.
* Robledo es la comuna donde más intentos de suicidio hubo.
* Septiembre y marzo son los meses donde más intentos de suicidio se llevan a cabo.
* Los estratos 2 y 3 presentan la mayor cantidad de intentos de suicidio.
* Las personas que ya han intentado suicidarse son propensas a intentarlo de nuevo.

**Dashboard en Power BI**
![](https://github.com/pablocarmona1527/Data_analyst/blob/main/suicidios_colombia/dashboard_suicidios.jpg)

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

![](https://github.com/pablocarmona1527/Data_analyst/blob/main/netflix_titles/netflix.png)

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
![](https://github.com/pablocarmona1527/Data_analyst/blob/main/space_missions/space_dashboard.png)

## [Housing Colombia](https://www.kaggle.com/datasets/julianusugaortiz/colombia-housing-properties-price)
Este dataset tiene información del precio, área construida, cantidad de habitaciones, ubicación, descripción, entre otras características de 1 millón de inmuebles en Colombia durante 2020 y 2021.

### Conclusiones
* Fueron usados 8 modelos de Machine Learning para predecir el precio de cada de venta de cada inmueble a partir del área, habitaciones, ubicación, entre otras características.
* El modelo que mejores predicciones generó fue Random Forest con un R2 de 0.44. Es decir, explica el 44% de la variabilidad de los precios de venta.
* A pesar de la gran cantidad de datos iniciales, la mayor parte de estos tienen valores nulos que pueden sesgar los resultados.
* Las ciudades con los precios venta y renta promedio más altos son Bogotá y Barranquilla, respectivamente.
### Información adicional
* El dataset inicial tiene 1 millon de filas y 25 columnas.
* 8 columnas tienen más del 30% de datos faltantes.
* El 57% de los inmuebles son para venta.
* El 56.53% de los inmuebles son apartamentos, seguido por casas (22.02%).
* Los lotes tienen el precio de renta promedio más alto mientras que los locales comerciales tienen el precio de venta promedio más alto.
* Bucaramanga y Cali tienen el menor precio de renta en apartamentos promedio.
  
**Dashboard en Power BI**

![](https://github.com/pablocarmona1527/Data_analyst/blob/main/housing_colombia/plantilla_housing.png) 

## [Amazon products](https://www.kaggle.com/datasets/lokeshparab/amazon-products-dataset)
Este dataset  tiene información de más de 500 mil productos de Amazon con información de la categoría, el precio real, el precio de descuento, la calificación de cada producto, entre otras características.


##[Vuelos en India](https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction/data)
Este dataset tiene información de más de 300 mil vuelos registrados en India entre sus principales ciudades. Se tiene informacion del precio de cada vuelo, la clase, la ciudad de salida y llegada, la hora de salida y llegada, la cantidad de paradas y la duración de cada vuelo.

### Conclusiones
* Fueron usados 7 modelos de regresión (Linear regression, Ridge, Lasso, Elastic Net, Decission Tree, Random Forest, Support Vector Machine) para predecir el precio de los vuelos de clase económica a partir de la aerolínea, la ciudad de salida y de llegada, la hora de salida y llegada, la cantidad de paradas y la duración del vuelo.
* Inicialmente el mejor modelo fue Random Forest con un R2 de 0.727. Este modelo fue ajustado mediante eliminación recursiva de características (RFECV) y GridSearch para mejorar su rendimiento. Luego de eso obtuvo un R2 de 0.74.
* Las características más importantes para predecir el precio de la clase económica son la duración y los días fuera.
### Información adicional
* El Dataset tiene 300153 filas y 19 columnas útiles.
* Las aerolíneas Air India y Vitara tienen los precios promedio más elevados.
* La mayoría de vuelos son entre Mumbai, Delhi y Bangalore
* La aerolínea Vistara realiza el 42.6% del total de vuelos. Pero NO tiene vuelos con hora de salida en la tarde.
* Solo el 0.43% de los vuelos salen tarde en la noche.
* Más del 80% de los vuelos tienen por lo menos una parada.
* En promedio los vuelos más largos son de Kolkata a Chennai. Y los más cortos son de Mumbai y Bangalore a Delhi


