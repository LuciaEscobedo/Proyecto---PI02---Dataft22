# Análisis de Datos sobre Siniestros Viales en la Ciudad Autónoma de Buenos Aires (CABA) de 2016 a 2021

## Introducción
Se analiza un dataset que contiene datos de accidentes de tráfico en la Ciudad Autónoma de Buenos Aires (CABA) registrados entre 2016 y 2021. Se entrega un informe EDA detallado y un panel interactivo para facilitar la interpretación y el análisis de la información.

## Ubicación y Contexto
La Ciudad Autónoma de Buenos Aires (CABA) es una de las veinticuatro entidades federales y capital de la República Argentina. Está situada en la región centro-este del país, sobre la orilla occidental del Río de la Plata, en plena llanura pampeana. El Río de la Plata (al este y al norte) y el Riachuelo (al sur) son los límites naturales de la Ciudad Autónoma de Buenos Aires.

La superficie de la Ciudad es algo superior a los 200 km² y su perímetro es de 60 km. Cerca de tres millones de habitantes (3.121.707 habitantes, fuente: Censo 2022) residen en ella, distribuidos en barrios que, desde el punto de vista político-administrativo, se agrupan en quince comunas. La densidad de la población es de más de 15.000 habitantes por kilómetro cuadrado. Las zonas centro y norte son los espacios territoriales más densamente poblados. Según la Dirección General de Estadísticas y Censos, el parque automotor de CABA registró provisoriamente 1.618.874 vehículos (febrero de 2024).

Por estos datos, los siniestros viales son una preocupación de alta urgencia en la Ciudad.

## Datos
**Dataset:** Homicidios que se encuentra en formato de Excel y contiene dos pestañas de datos:

- **HECHOS:** Contiene una fila por hecho con ID único y las variables temporales, espaciales y participantes asociadas al mismo.
- **VICTIMAS:** Contiene una fila por cada víctima de los hechos y las variables edad, sexo y modo de desplazamiento asociadas a cada víctima. Se vincula a los HECHOS mediante el ID del hecho.
- **POBLACION:** Contiene una fila por cada comuna de CABA acompañada por su población. Se vincula a la tabla HECHOS mediante la columna Comuna.

## Tecnologías Utilizadas
- **Python:** Para la extracción y análisis de datos.
- **Librerías de Python:** Pandas, Seaborn, Matplotlib.
- **Power BI:** Para la visualización interactiva de datos.

## Etapas Tecnológicas

### Primera Etapa
Comenzamos con la extracción de los datos, su conversión en dataframes, la verificación de la calidad de los mismos y un análisis exploratorio mediante gráficos y métricas para realizar observaciones. Para esta etapa usamos Python con las siguientes librerías: Pandas, Seaborn y Matplotlib.

### Segunda Etapa
En la segunda etapa confeccionamos un dashboard en Power BI para visualizar los KPIs y las métricas de forma más fluida y comprensible.

## Paso a Paso

### Transformaciones (ETL)
En esta sección, llevamos a cabo la extracción de datos y verificamos su integridad mediante la identificación de valores faltantes, duplicados y nulos. Además, realizamos un análisis de outliers para determinar si estos valores eran simplemente atípicos o si indicaban errores en los datos. Este proceso se aplicó a ambos dataframes.

### Análisis Exploratorio de Datos (EDA)
Para un mejor análisis exploratorio, utilizamos gráficos para métricas específicas, lo que nos permitió identificar datos relevantes y llegar a algunas conclusiones que podrían ser útiles para análisis futuros. Los tópicos analizados fueron:
- **Número total de víctimas fatales por año**
- **Número total de víctimas fatales por mes desde 2016 a 2021**
- **Proporción de Género entre las Víctimas Fatales**
- **Distribución de Víctimas Fatales por Rango Etario**
- **Distribución de Víctimas por Tipo de Vehículo**
- **Distribución de Víctimas por Rol**
- **Distribución de Víctimas Fatales por Grupo Etario y Rol**

### Indicadores Clave de Rendimiento (KPIs)
Se definieron tres KPIs:
1. Reducir en un 10% la tasa de homicidios en siniestros viales de los últimos seis meses en CABA, en comparación con la tasa de homicidios en siniestros viales del semestre anterior.
2. Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año en CABA respecto al año anterior.
3. Reducir en un 5% el índice de riesgo de peatones en el último año en CABA respecto al año anterior.

## Contacto
Para más información, puedes contactarme a través de:

- **Email:** [luchyescobedo@gmail.com](mailto:luchyescobedo@gmail.com)
- **LinkedIn:** [Lucía Escobedo](https://www.linkedin.com/in/lucia-escobedo-b76555202)
