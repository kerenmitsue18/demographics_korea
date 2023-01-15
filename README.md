# Extracción de información al conjunto de datos "Korean_demographics"

### Descripción del conjunto de datos
El conjunto de datos incluye indicadores demográficos básicos de Korea (natalidad, mortalidad, crecimiento natural, matrimonios y divorcios) entre enero del 2000 y enero del 2022. Contiene la cantidad de personas y la taza de cada uno de los indicadores. 

###### Atributos
El conjunto de datos tiene 4860 instancias, con 12 atributos:  
- Date: fecha en la que fueron registrados los datos.
- Region: se consideran 18 regiones de Korea.
- Birth: indicador referente a los nacimientos ocurridos en una población.
- Birth_rate: taza de natalidad, también conocida como taza de nacimientos.
- Death: indicador referente a las defunciones ocurridos en una población.
- Death_rate: taza de defunciones.
- Divorce: indicador referente a los divorcios ocurridos en una población.
- Divorce_rate: taza de divocios.
- Marriage: indicador referente a los matrimonios ocurridos en una población. 
- Marriage_rate: taza de matrimonios. 
- Natural_growth: diferencia entre los indicadores de natalidad y mortalidad.
- Natural_growth_rate: taza de crecimiento natural. 
Cada instancia del conjunto de datos contiene la fecha y región de donde se obtuvieron los datos. 

Existen datos incompletos, por lo que, se descartan para el estudio. 
El conjunto de datos fue recuperado de https://www.kaggle.com/datasets/alexandrepetit881234/korean-demographics-20002022. 

### Justificación y objetivos del análisis de datos

En este trabajo se desea encontrar información relevante del conjunto de datos que aborda los indices demográficos de Corea, además de encontrar información que permita observar como influye una pandemia en los datos demográficos del país. La intención inicial del análisis de los datos, es responder las siguientes preguntas: 

De acuerdo al conjunto de datos, y enfocándose en resumir las  características del conjunto de datos, se puede obtener la siguiente  información: 
###### Respecto a indice demográfico : Mortalidad
- ¿Cuál la media y el promedio de mortalidad del conjunto de datos?
- ¿Cuáles son las 3 regiones de Corea con más índice de mortalidad?
- ¿Cuáles son los  promedios de las 3 regiones con más índice de mortalidad?
- ¿Cuáles son las 3 regiones de Corea con menos índice de mortalidad?
- ¿Cuáles son los promedios  de las 3 regiones con menos índice de mortalidad?
- ¿Cómo es el comportamiento respecto al tiempo del índice de mortalidad  en las tres regiones seleccionadas (menor y mayor índice)? 
###### Respecto a indice demográfico : Natalidad
- ¿Cuál es la media y el promedio de natalidad del conjunto de datos?
- ¿Cuáles son las 3 regiones de Corea con más índice de natalidad?
- ¿Cuáles son los promedios  de las 3 regiones con más índice de natalidad?
- ¿Cuál es la región de Corea con menos índice de natalidad?
- ¿Cuáles son los promedios de las 3 regiones con menos índice de natalidad?
- ¿Cómo es el comportamiento respecto al tiempo del índice de natalidad  en las tres regiones seleccionadas (menor y mayor índice)? 
###### Respecto a indice demográfico : Matrimonios
- ¿Cuál es la media y el promedio de matrimonios del conjunto de datos?
- ¿Cuáles son las 3 regiones de Corea con más índice de matrimonios?
- ¿Cuáles son los promedios de las 3 regiones con más índice de matrimonios?
- ¿Cuáles son las 3 regiones de Corea con menos índice de matrimonios?
- ¿Cuáles son los promedios de las 3 regiones con menos índice de matrimonios?
- ¿Cómo es el comportamiento respecto al tiempo del índice de matrimonios en las tres regiones seleccionadas (menor y mayor índice)? 
###### Respecto a indice demográfico : Divorcios
- ¿Cuál es la media y el promedio de divorcios del conjunto de datos?
- ¿Cuáles son las 3 regiones de Corea con más índice de divorcios?
- ¿Cuáles son los promedios de las 3 regiones con más índice de divorcios?
- ¿Cuáles son las 3 regiones de Corea con menos índice de divorcios?
- ¿Cuáles son los promedios de las 3 regiones con menos índice de divorcios?
- ¿Cómo es el comportamiento respecto al tiempo del índice de divorcios en las tres regiones seleccionadas (menor y mayor índice)?

###### Preguntas exploratorias
Con la respuesta a las preguntas descriptivas mencionadas anteriormente, se obtiene un panorama resumido de las características del conjunto de datos, y así enfocarnos en las regiones de intéres, donde posteriormente se reponden a preguntas exploratorias y específicas por cada índice demográfico. Las preguntas exploratorias que se proponen responder son las siguientes:

- ¿Existe una relación estadística entre el índice de natalidad y el índice de matrimonios?
- ¿Existe una relación estadística entre el índice de mortalidad y el índice de divorcios?
- ¿Influye el año en que se realizaron más matrimonios con la natalidad en años posteriores?
- ¿Cómo es el comportamiento del índice de mortalidad en el periodo de 2020 a 2022 (durante la pandemia COIVD-19), respecto a otros años?
- ¿Cómo es el comportamiento del índice de mortalidad en el periodo de 2009 a 2010  (durante la pandemia de gripe A H1N1), respecto a otros años?
- ¿Cómo es el comportamiento del índice de natalidad en el periodo de 2020 a 2022 (durante la pandemia COIVD-19), respecto a otros años?
- ¿Cómo es el comportamiento del índice de natalidad en el periodo de 2009 a 2010  (durante la pandemia de gripe A H1N1), respecto a otros años?
- ¿Cómo es el comportamiento del índice de natalidad durante la pandemia de COVID-19, respecto a la pandemia de gripe A H1N1?
- ¿Cómo es el comportamiento del índice de mortalidad durante la pandemia de COVID-19, respecto a la pandemia de gripe A H1N1?


