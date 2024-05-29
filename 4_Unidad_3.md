# Metodos de analitica de datos, exploratorio, estadistcos y visualizaciones

## Bienvenida

ver video 1_Bienvenida

## Análisis exploratorio de datos

El análisis exploratorio de datos (EDA, por sus siglas en inglés) es una fase crítica en cualquier proceso de análisis de
datos que precede a las etapas de modelado o inferencia estadística. Esta etapa se centra en descubrir patrones, detectar
anomalías, probar hipótesis y verificar suposiciones con la ayuda de estadísticas descriptivas y representaciones gráficas

![alt text](image-122.png)

El EDA es una filosofía o un enfoque para el análisis de conjuntos de datos generalmente grandes con el fin de resumir sus
principales características, a menudo visualmente. Este enfoque fue promovido por el estadístico John Tukey en 1977, con el
objetivo de fomentar la utilización de los datos para generar hipótesis y permitir la interpretación del fenómeno subyacente
en los datos.

![alt text](image-123.png)

El EDA se lleva a cabo a través de un proceso iterativo en el cual el analista genera preguntas sobre los datos, utiliza
estadísticas descriptivas y técnicas de visualización para responder a estas preguntas, y luego genera más preguntas en
función de lo que ha aprendido.

Generacion de preguntas:

El primer paso en EDA es generalmente la formulación de preguntas sobre los datos. Estas preguntas pueden ser tan simples
como "¿Cuál es la media de esta variable?" o tan complejas como "¿Hay alguna correlación entre estas dos variables?".

Las estadísticas descriptivas

Las estadísticas descriptivas se utilizan para responder a estas preguntas. Estas pueden incluir medidas de tendencia
central como la media, la mediana y la moda; medidas de dispersión como la varianza, la desviación estándar y el rango
intercuartil; y medidas de forma como la curtosis y la asimetría.

Las técnicas de visualización

Las técnicas de visualización son una herramienta importante en EDA. Los histogramas, gráficos de barras, gráficos de caja,
gráficos de dispersión y mapas de calor son algunos ejemplos de las representaciones gráficas utilizadas en EDA para
explorar la distribución de los datos, las relaciones entre variables, y las tendencias y patrones en los datos.

Generacion de nuevas preguntas e hipotesis

Basándose en los resultados de las estadísticas descriptivas y las visualizaciones, el analista puede generar nuevas
preguntas e hipótesis para investigar. Este proceso iterativo permite al analista profundizar en los datos y descubrir
patrones y relaciones que pueden no ser evidentes en una inspección superficial.

![alt text](image-124.png)

El EDA es un paso crucial en el proceso de análisis de datos por varias razones. Primero, ayuda a los analistas a entender
la estructura y las propiedades de los datos, lo cual es esencial para seleccionar las técnicas de modelado o inferencia
adecuadas. Segundo, puede ayudar a identificar errores, valores atípicos y anomalías en los datos que pueden afectar los
resultados del análisis. Tercero, puede revelar patrones y relaciones en los datos que pueden informar el desarrollo de
hipótesis y la selección de variables para el análisis posterior.

Tecnicas multivariadas

Este tipo de análisis examina dos o más variables simultáneamente para identificar relaciones y dependencias entre ellas.
Las técnicas multivariadas comúnmente utilizadas incluyen la construcción de gráficos de dispersión, que muestran la
relación entre dos variables, y el cálculo de medidas de correlación, como el coeficiente de correlación de Pearson, que
cuantifica la relación lineal entre dos variables.

Tecnicas univariadas

Este tipo de análisis se enfoca en una sola variable a la vez. Las técnicas univariadas comúnmente utilizadas incluyen el
análisis de la distribución de frecuencias, donde se cuenta el número de veces que cada valor de una variable aparece en el
conjunto de datos, y la construcción de histogramas, que proporciona una representación visual de la distribución de una
variable. Estos análisis pueden revelar patrones en la distribución de los datos, como por ejemplo, si los datos están
sesgados a la izquierda o a la derecha, o si hay valores atípicos evidentes.

desafíos y consideraciones en EDA

Uno de los principales desafíos es la "maldición de la dimensionalidad", es decir, la dificultad de visualizar y entender
los datos en espacios de alta dimensión. A medida que el número de variables en un conjunto de datos aumenta, la dificultad
de explorar y visualizar todas las combinaciones posibles de variables también aumenta exponencialmente.

Además, el EDA debe realizarse con cuidado para evitar sesgos y malinterpretaciones. Por ejemplo, la correlación no implica
causalidad: aunque dos variables pueden estar correlacionadas, esto no significa necesariamente que una variable cause el
cambio en la otra. Además, los valores atípicos pueden tener un gran efecto en las estadísticas descriptivas y las
visualizaciones, y deben tratarse adecuadamente para evitar conclusiones engañosas.

El papel del EDA en la Ciencia de Datos:

El análisis exploratorio de datos es un componente crucial de la ciencia de datos. Proporciona el contexto necesario para el
desarrollo y ajuste de modelos de aprendizaje automático y permite a los científicos de datos generar y refinar hipótesis.
Además, el EDA es un componente esencial del "ciclo de vida" de un proyecto de ciencia de datos, que generalmente incluye la
recopilación de datos, la limpieza de datos, el EDA, el modelado, la interpretación y la comunicación de los resultados.

El análisis exploratorio de datos es una parte fundamental de cualquier proceso de análisis de datos, proporcionando una
forma sistemática de examinar, entender y describir el conjunto de datos a mano. A través de técnicas visuales y
estadísticas, los analistas pueden descubrir patrones, detectar anomalías, probar hipótesis y verificar supuestos,
proporcionando una base sólida para las etapas posteriores del análisis de datos.

## Complemento: Análisis exploratorio de datos

Ver pdf 2_Análisis exploratorio de datos

## Profundización: Análisis exploratorio de datos

ver video 3_Profundización_Análisis exploratorio de datos

## Métodos estadísticos básicos para el análisis de datos

El análisis de datos es un proceso multidimensional que implica la aplicación de varias técnicas y metodologías con el objetivo de extraer información útil, sugerir conclusiones y apoyar la toma de decisiones. Los métodos estadísticos juegan un papel fundamental en este proceso, proporcionando un marco para analizar, interpretar y predecir fenómenos basándose en datos. Los métodos estadísticos básicos, tales como pruebas de hipótesis, análisis de regresión y análisis de varianza, son herramientas esenciales en la caja de herramientas de un analista de datos.

**Las pruebas de hipótesis** son una de las técnicas más comunes utilizadas en el análisis de datos. Una prueba de hipótesis es un método estadístico que se utiliza para tomar decisiones sobre una población basándose en una muestra de datos. La hipótesis nula, que es la afirmación que se está probando, generalmente representa una situación de "no cambio" o "no efecto". La hipótesis alternativa, por otro lado, representa una situación de "cambio" o "efecto". La decisión sobre si rechazar o no la hipótesis nula se basa en el valor p de la prueba, que es la probabilidad de obtener los datos observados si la hipótesis nula es verdadera.

**El análisis de regresión** es un método estadístico que explora la relación entre una variable dependiente y una o más variables independientes. En su forma más simple, la regresión lineal, se asume una relación lineal entre las variables. Los coeficientes de regresión, que se estiman a partir de los datos, describen la magnitud y la dirección de la relación entre las variables. El análisis de regresión puede ser utilizado para predecir el valor de la variable dependiente basándose en los valores de las variables independientes.

**El Análisis de Varianza** es un método estadístico utilizado para comparar las medias de dos o más grupos. ANOVA divide la variabilidad total en los datos en variabilidad debida a los grupos (variabilidad entre grupos) y variabilidad dentro de los grupos (variabilidad dentro de los grupos). Si la variabilidad entre grupos es significativamente mayor que la variabilidad dentro de los grupos, entonces se concluye que hay una diferencia significativa entre los grupos.

**La correlación y la covarianza** son dos medidas estadísticas que se utilizan para evaluar la relación entre dos o más variables. La correlación es una medida normalizada de la dependencia lineal entre dos variables y varía entre -1 y 1. Un valor de correlación positivo indica que las variables tienden a aumentar o disminuir juntas, mientras que un valor negativo indica que una variable tiende a aumentar cuando la otra disminuye. La covarianza, por otro lado, es una medida de la variación conjunta de dos variables aleatorias con respecto a sus medias. Si bien la correlación es una medida adimensional de la relación entre las variables, la covarianza está en las unidades del producto de las dos variables.

**Las pruebas de normalidad** son utilizadas para determinar si un conjunto de datos se ajusta a una distribución normal. Esto es relevante porque muchos de los métodos estadísticos asumen que los datos se distribuyen normalmente. Las pruebas de normalidad incluyen el test de Shapiro-Wilk, el test de Anderson-Darling, el test de Kolmogorov-Smirnov, entre otros. Los resultados de estas pruebas, junto con gráficos como el histograma y el gráfico Q-Q, pueden proporcionar una buena indicación de si los datos son normalmente distribuidos o no.

**La estadística descriptiva** se utiliza para resumir y describir los datos. Esto incluye medidas de tendencia central, como la media, la mediana y la moda; medidas de dispersión, como la varianza, la desviación estándar, el rango y el coeficiente de variación; y medidas de forma, como la asimetría y la curtosis. Estas medidas proporcionan una visión general de los datos y pueden ayudar a identificar patrones y anomalías.

**La estadística inferencial**, Mientras que la estadística descriptiva se centra en describir los datos, la estadística inferencial se utiliza para hacer inferencias sobre una población basándose en una muestra de datos. Esto implica el uso de pruebas de hipótesis, intervalos de confianza, análisis de regresión y otros métodos estadísticos para estimar parámetros de la población, probar hipótesis y predecir resultados futuros.

## Métodos estadísticos básicos para el análisis de datos profundizacion

## Técnicas de visualización de datos

## Complemento: Técnicas de visualización de datos

## Profundización: Técnicas de visualización de datos

## Herramientas de visualización de datos

## Complemento: Herramientas de visualización de datos

## Profundización: Herramientas de visualización de datos

## Interpretación de los resultados del análisis y visualización de datos

## Complemento: Interpretación de los resultados

## Cerrando la unidad
