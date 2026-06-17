# Introducción

De los 4 archivos ".csv" anteriores, crear un apartado en el informe que se llame "Introducción" y que liste todas las variables dentro de cada archivo en formato lista.

Ejemplo: 
"En este estudio se analiza un conjunto de datos referido a campeonatos de la Fórmula 1, comprendidos
entre los años 2018 y 2023. Las variables evaluadas fueron:

Archivo 1. carreras.csv
idCarrera: Identificador de la carrera.
año: Año de realización de la carrera.... etc....

=======================================================
# Análisis


Tengo un punto que analizar: "Analizar el estado de finalización de todos los corredores en todas las carreras. Luego, repetir el análisis
considerando sólo los resultados del equipo Mercedes."

Esto siguiente debe  estar en formato ".Rmd"  y solo dentro del apartado "análisis" del informe:

"Análisis
Desarrollo del informe, presentando el código para generar las tablas, medidas resúmenes, gráficos, etc. para
responder a cada una de las preguntas.
Al presentar los resultados obtenidos hacer comentarios analizando lo que se observa en el análisis exploratorio
desarrollado."

Antes que nada, tener en cuenta el material principal (Unidad3) De donde se dictan que tipo de cálculos y tablas debo hacer uso (estrictamente)
Para este análisis debo obtener como resultado una serie de cosas:

1. Determinar si es Univariado o Bivariado
2. Si es Bivariado: hacer uso de una tabla tipo "tibble" como para mostrar los dos tipos de variables.(Antes de calcular los datos)
3. Listo eso, obtener los cálculos necesarios para poder realizar una tabla de frecuencias con las medidas que son solo objetivas al punto de análisis (No extenderse ni agregar datos no requeridos)
4. Presentarlos usando "knitr::kable"
5. Por último armamos un gráfico para mostrar lo previamente calculado (respetando el uso de los gráficos por tipo de análisis como se encuentra el el temario principal)
