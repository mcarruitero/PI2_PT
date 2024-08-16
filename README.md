# Proyecto Individual Numero 2 Analisis de Datos

Con el rol de Data Analyst realizo un proyecto sobre las telecomunicaciones en Argentina.
Se explica el proyecto desde el EDA, hasta algunas conclusiones sobre los datos y KPI´s así como el uso de Power BI para el dashboard final.

## Fuente de datos

Se tienen como fuente de datos los siguientes archivos excel de ENACOM
[Dataset principal](https://indicadores.enacom.gob.ar/datos-abiertos)
- Internet.xlsx (obligatorio)

[Dataset ubigeo](https://github.com/mcarruitero/PI2_PT/tree/main/Data)
- ar.xslx

### Data

En la carpeta [Data](https://github.com/mcarruitero/PI2_PT/tree/main/Data) se encuentran los archivos usados para el proceso Analisis EDA.

### Dataframe

En la carpeta [Dataframe](https://github.com/mcarruitero/PI2_PT/tree/main/Dataframe) se encuentran los archivos procesados para el Analisis EDA y el Dashboard.

## EDA (Exploratoy Data Analysis)

Se realiza el preprocesamiento consistenjte en el ETL extracción transformación y carga en Python para su posterior análisis de variables en busca de tendencias, relaciones para la generación de gráficos y conclusiones  del proyecto. En el archivo [AnalisisEDA](https://github.com/mcarruitero/PI2_PT/blob/main/AnalisisEDA.ipynb) se podrán ver la limpieza, transformaciones, gráficos de información, análisis sobre los mismos y las conclusiones en base a lo analizado. Con las conclusiones se plantean 2 KPIs (Key Performance Indicator) con los que se buscarán proporcionar medidas cuantificables del negocio.

## Determinación de los KPIs

Los KPIs en base al análisis realizado, son el acceso a los servicios de internet, la tecnologia utilizada. Por eso se identificaron 2 KPIs personalizados a los objetivos de este proyecto, los que se describen a continuación:

Aumentar en un 2% el acceso al servicio de internet para el próximo trimestre, cada 100 hogares, por provincia.

Aumentar en un 2% el acceso al servicio de internet mediante fibra óptica para el próximo trimestre por provincia.

## Elaboración del Dashboard

El dashboard permite monitorear el rendimiento de una empresa asi como a identificar áreas de mejora y oportunidades de crecimiento para la toma de decisiones en el sector de las telecomunicaciones.

La visualización de los datos se realizó con Power BI. [Dashboard](https://github.com/mcarruitero/PI2_PT/blob/main/PI2_Dashboard.pbix)