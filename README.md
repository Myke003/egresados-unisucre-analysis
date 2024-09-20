## Analisis de la distribución de egresados unisucre 2011-2020

La Universidad de Sucre es una institución de educación superior colombiana que ofrece diversos programas con acreditación de alta calidad. En este análisis de datos se analizará un conjunto de datos que contiene un listado de graduados para el periodo 2011-2020.

***Importante***: Cabe aclarar que este estudio se realizó con fines de aprendizaje y puede que no represente las cifras exactas de egresados, ya que yo no tengo ninguna conexión con la universidad y solo es un dataset que encontré en una página. Por lo que, si usted encuentra esto, no recomiendo utilizarlo para un estudio o algo parecido.

**Objetivos de analisis**

El análisis tiene los siguientes objetivos:

- Encontrar el número total de egresados.
- Conocer el número de egresados por año.
- La distribución de los egresados por género.
- La distribución en porcentaje de los egresados por carrera.
- La distribución de los egresados por pregrado y posgrado.

**Estructura del proyecto**
El proyecto sigue la siguiente estructura:

- Proyecto_raiz/
  - data/
    - Listado_de_Graduados_Programas_de_Pregrado_y_Posgrado_Universidad_de_Sucre_20240916.csv
  - notebooks/
    - categorias.py
    - egresados_unisucre_2011-2022.ipynb
  - results/
    - Graduados_por_año.csv
    - Listado_de_graduados_unisucre_limpio.csv
  - README


**Sobre el dataset**

El dataset que se utilizó para realizar el estudio fue recuperado de la página "Datos Abiertos" del gobierno nacional. Pueden descargar el dataset original dando clic al siguiente enlace:  [Listado de Graduados Programas de Pregrado y Posgrado Universidad de Sucre](https://www.datos.gov.co/Educaci-n/Listado-de-Graduados-Programas-de-Pregrado-y-Posgr/pp6t-bhez/about_data).

**Limpieza de datos**

Para la limpieza de datos se comprobó que no hubiera duplicados ni datos nulos. También se corrigieron varios errores ortográficos. Seleccionamos las columnas importantes para el estudio, descartando las que fueron innecesarias, y por último, creamos una nueva columna llamada "Categorías" con el fin de hacer más fácil la visualización de las carreras.

**Analisis de datos**

Para el análisis de datos, se hizo un análisis rápido utilizando Python y matplotlib, y aunque no se ve muy pulido, es lo suficiente para tener una idea sobre los datos y su posterior visualización en un dashboard.

**Visualización de datos**

Para visualizar los datos en un dashboard se utilizó la herramienta "Google Looker Studio" y podrán visualizarlo haciendo clic [aquí](https://lookerstudio.google.com/reporting/73686e9c-6d3b-482f-aeb7-fb6049f7ec2c)

**Comentario personal**
Eso fue todo. Yo sé que no es nada del otro mundo, pero para ser mi primer análisis de datos en Python y Looker Studio, estoy realmente satisfecho.

"Un pequeño paso para el área de Data Science, un gran paso mi :D"