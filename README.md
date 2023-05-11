# Naomi Padilla - Portafolio
Portafolio de mis proyectos más destacables en ciencia de datos.

## Sobre mi
Estudiante del 6to semestre de **Ingeniería en Ciencia de Datos y Matemáticas en el Tecnológico de Monterrey**.
Me apasiona la programación y la tecnología. Me considero una persona perseverante en mis metas académicas, laborales y personales. Siempre dispuesta a aprender y tener nuevos retos. A lo largo de mi carrera y experiencia laboral he desarrollado diversas competencias como la comunicación, el trabajo en equipo, pensamiento crítico y toma de desiciones.

Mi [CV](https://github.com/NaomiPadillaM/Naomi_Portfolio/blob/main/files/Naomi_Padilla%20Mora_Resumen.pdf) (español).

Mi [CV](https://github.com/NaomiPadillaM/Naomi_Portfolio/blob/main/files/Naomi_Padilla%20Mora_Resume.pdf) (inglés).

Tablero de [GitHub](https://github.com/NaomiPadillaM).

Mi perfil en [Linkedin](https://www.linkedin.com/in/naomi-padilla-mora-/).

## Skills

skills:
- name: Python
  logo: "/images/heart_1.png"
  summary: "Descripción media de lo que sabes hacer con esta habilidad"

# [Proyecto 1: Heart Failure Predictions](https://github.com/NaomiPadillaM/Heart-Failure-Predictions.git)
## Lenguajes: Python 
* Limpieza y pretratamiento de datos usando *pandas* y *numpy* con el objetivo de verificar el tipo de datos y la presencia de datos nulos.
* Análisis estadístico de cada variable, su distribución y correlación. 
* Uso de Sklearn *Principal Component Analysis (PCA)* y *StandarScaler* para la estandarización de los datos.
* Uso de *train_test_split* para el entrenamiento de los datos en los modelos de aprendizaje supervisado.
* Intento de predicción de _heart failure_ usando **Support Vector Machine**, **Decision Tree**, **Neuronal Network**, **Logistic Regression**, **Random Forest** and **K-Nearest Neighbours** complementando con la matriz de confusión para la evaluación de cada modelo. 
* Uso de la librería _matplotlib_ para la visualización. 

![](/images/heart_1.png)

![](/images/heart_2.png)


# [Proyecto 2: Life-Expectancy](https://naomipadillam.github.io/Life-Expectancy/) 
## Lenguajes: Python 
* Limpieza y pretratamiento de datos usando *pandas* y *numpy* con el objetivo de verificar el tipo de datos y la presencia de datos nulos.
* Cambio de variables _string_ a _int_, tratamiento de datos nulos y selección de variables más relevantes.
* Uso de la librería **geopandas** para el modelado geográfico de la solución.
* Uso de Sklearn *Principal Component Analysis (PCA)* y *StandarScaler* para la estandarización de los datos.
* Implementación del método del codo y _Silhouette Coefficient_ para la obtención de número de clusters a implementar.
* Modelos de clasificación por condiciones de salud a nivel mundial utilizando **K-Means**, **Affinity Propagation**, **Spectral clustering** y **DBSCAN**.
* Reducción dimensional para la visualización de los datos.
* Uso de las librerías _plotly.express_ y _matplotlib.pyplot_ para las gráficas de dispersión por grupos. 
* Uso de la librería _folium_ para la creación de la visualización geográfica final. Mapa interactivo por cada uno de los métodos aplicados.

![](/images/life_1.png)

<iframe src="https://e6lifenosupervisado.netlify.app/" height="400" width="900"></iframe>

Puedes explorar este mapa en el [link](https://e6lifenosupervisado.netlify.app/)

# [Proyecto 3: Reto Coppel](https://naomipadillam.github.io/RetoCoppel/) 
## Lenguajes: Python 
* Optimización de rutas para el _e-commerce_ de Coppel.
* Uso de algoritmos **TPS**, **VRP** y **CVRP**.
* Implementación de web scrapping para la búsqueda de direcciónes optimizada.
* Sistema de optimización de rutas que contempla el número de vehículos, volumen de los productos, tiempo de entrega y de traslado para generar las mejores rutas disponibles.
* Aproximación de tráfico muy cercana a una situación real.

<iframe src="https://ma2001b-202-4-mapeop2.netlify.app/" height="500" width="700"></iframe>

Puedes explorar este mapa en el [link](https://ma2001b-202-4-mapeop2.netlify.app/)


# [Proyecto 4: Predicción Contagios Montecarlo](https://naomipadillam.github.io/ContagioMontecarlo/)
## Lenguajes: R, Python 
* Creación de simulaciones de la distribución de contagios por una enfermedad en México, implementando el modelo SIR.
* Creación de aplicación _dashboard_ consulte en el [link](https://adrian-landaverde.shinyapps.io/ContagioEpidemia/).
* La aplicación que permite ver la expansión de una enfermedad usando una simulación Montecarlo con el modelo SIR. En ella es posible probar los escenarios deseados a través de variables como la cantidad de días, población total, razón de infección y de recuperación.
* Implementación de este método en una representación geográfica de México con la libreria _geopandas_.

![](/images/montecarlo_1.png)

Simulación de 365 días: 

<iframe width="340" height="280" src="https://www.youtube.com/embed/mel1g1ueas4" title="Simulación A con 365 días" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# [Proyecto 5: Reto FEMSA](https://github.com/NaomiPadillaM/Reto-FEMSA-COCA-COLA) 
## Lenguajes: R, Python 
* Análisis exploratorio de las variables por cada uno de los compresores de la planta de FEMSA COCA-COLA.
* Análisis estadístico.
* Prueba Anova y su distribución por SKU (variable) y _t-student_.
* Creación de aplicación _dashboard_ consulte en el [link](https://adrian-landaverde.shinyapps.io/ProyectoCocaCola3/).
* En la aplicación se pueden ver los gráficos de cada compresor con las variables requeridas, además de las correlaciones y los resultados de la prueba Anova.
* Implementación del método **Random Forest** para la predicción del consumo de energía por cada compresor de la planta por día.

![](/images/femsa_1.png)

![](/images/femsa_2.png)

# [Proyecto 6: Predicción de calorías](https://github.com/NaomiPadillaM/Prediccion-de-calorias) 
## Lenguajes: Python, Excel 
* Creación de dataset de manera manual. Registro de consumo nutrimental (calorías, grasas, proteínas, carbohidratos y sodio) por cada alimento consumido a lo largo de 15 semanas. Con una dimensión de 5 x 317.
* Análsis exploratorio en excel, **análisis de correlación** y **Regresión múltiple**. Además de la obtención de la ecuación lineal que modela la situación.
* Implementación del modelo de predicción de calorías utilizando **Sickit-Learn**.

![](/images/nutrimental_1.png)

# [Proyecto 7: Genes de Cancer de Colon](https://github.com/NaomiPadillaM/Genes-en-cancer-colon) 
## Lenguajes: R 
* Utilizando datasets sobre la expresión de genes, obtenidos de _Geo Datasets_.
* El análisis se llevó a cabo en jóvenes y adultos con cáncer de colon en estapa II y III.
* La selección de genes o biomarcadores se llevó a cabo con **t-test**.
* Implementación de _volcano Graph_ y _R-I Graph_ con el objetivo de encontrar las diferencias entre los cuatro grupos de estudio:
  * Adultos jóvenes con cáncer de colon etapa II.
  * Adultos jóvenes con cáncer de colon etapa III.
  * Adultos mayores con cáncer de colon etapa II.
  * Adultos mayores con cáncer de colon etapa III.
* Investigación de cada uno de los biomarcadores identificados como los más relevantes usando _genomic datasest_ como **STRING**, **KEGG**, **Panther** y **NCBI**.

![](/images/genes_1.png)
