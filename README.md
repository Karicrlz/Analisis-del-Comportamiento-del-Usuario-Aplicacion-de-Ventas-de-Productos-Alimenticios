# 📱🍎Análisis del Comportamiento del Usuario y Test A/A/B en Aplicación de Ventas de Productos Alimenticios 🤳🏼🍔
### Descripción de proyecto 
En una empresa emergente dedicada a la venta de productos alimenticios, fui responsable de investigar el comportamiento de los usuarios dentro de la aplicación. Comencé estudiando el embudo de ventas para comprender cómo los usuarios avanzan hacia la etapa de compra. Me enfoqué en identificar cuántos usuarios llegaban a esta fase, cuántos se quedaban atascados en etapas anteriores y cuáles de estas etapas presentaban más problemas.
Además, realicé un análisis de los resultados de un test A/A/B que se llevó a cabo para evaluar un cambio propuesto en el diseño de la aplicación. El equipo de diseño sugirió actualizar las fuentes de la aplicación, pero la gerencia tenía preocupaciones sobre si el cambio sería percibido como intimidante por los usuarios. Para tomar una decisión informada, decidimos realizar el test con tres grupos: dos grupos de control que mantenían las fuentes antiguas y un grupo de prueba con las nuevas fuentes.
Mi objetivo fue analizar los resultados del test A/A/B para determinar qué conjunto de fuentes generaba mejores resultados en términos de experiencia del usuario y rendimiento general de la aplicación. Este análisis ayudó a la empresa a tomar decisiones basadas en datos para optimizar la interfaz de usuario y mejorar la conversión en el proceso de ventas.

## Motivación 
Al investigar el comportamiento de los usuarios y analizar el embudo de ventas, el objetivo fue identificar las barreras que impedían que los usuarios llegaran a la etapa de compra, lo que permitió tomar medidas para mejorar la conversión. Además, el análisis del test A/A/B realizado para evaluar el impacto de un cambio en el diseño, como la actualización de las fuentes, fue crucial para tomar decisiones informadas sin generar resistencia en los usuarios. Este proyecto es importante porque ayudó a la empresa a hacer mejoras en la interfaz de usuario basadas en datos reales, lo que no solo optimizó la experiencia de los usuarios, sino que también mejoró la eficiencia del proceso de ventas. Al identificar qué diseño tenía un mejor rendimiento, se logró maximizar el potencial de conversión y, en última instancia, aumentar los ingresos de la empresa emergente.

## Características del Dataset

Cada entrada de registro es una acción de usuario o un evento.

event_name: nombre del evento.

uid: identificador de usuario unívoco.

event_ts: hora del evento.

expid: número de experimento: 246 y 247 son los grupos de control, 248 es el grupo de prueba.

## Herramientas Utilizadas
### Lenguaje: 
Python 
### Librerías:
pandas para la manipulación de datos.

numpy para cálculos numéricos.

matplotlib y seaborn para visualizaciones.

scikit-learn para la creación y evaluación de modelos de Machine Learning.

scipy para os calculos estaditícos 

Jupyter Notebook para la documentación del análisis.


## Proceso del Proyecto

### Carga y Exploración de Datos

Análisis inicial del dataset: revisión de los valores faltantes, tipos de datos y distribuciones.

Exploratory Data Analysis (EDA) para entender las relaciones entre las variables.

### Limpieza y Preprocesamiento

Imputación de valores faltantes en variables.

Conversión de variables categóricas en variables numéricas.

Normalización de variables continuas.

### Estudiar el embudo de eventos

Se observa qué eventos hay en los registros y su frecuencia de suceso. 

Se encontro la cantidad de usuarios y usuarias que realizaron cada una de estas acciones.

Se utilizó el embudo de eventos para encontrar la proporción de usuarios y usuarias que pasan de una etapa a la siguiente. (Por ejemplo, para la secuencia de eventos A → B → C, calcula la proporción de usuarios en la etapa B a la cantidad de usuarios en la etapa A y la proporción de usuarios en la etapa C a la cantidad en la etapa B).

### Estudiar los resultados del experimento

### ¿Qué nivel de significación has establecido para probar las hipótesis estadísticas mencionadas anteriormente?
Para probar las hipotesis se utilizo unb nivel de significancia del 0.05, lo que implica que existe un 5% de probabilidad de obtener un resultado falso positivo. el nivel de significación es 0.1 (10%).

Cuando se realizan varias pruebas de hipótesis, el riesgo de cometer un error tipo I (falso positivo) aumenta. Esto es conocido como el problema de las comparaciones múltiples. Si se usa un nivel de significación de 0.1 para cada prueba, la probabilidad de obtener al menos un resultado falso positivo en varias pruebas aumenta.

Si se utiliza un nivel de significación de 0.1 sin ninguna corrección, aproximadamente 1 de cada 10 resultados podría ser falso.Por lo que se dejara el nivel de significación en 0.05.








