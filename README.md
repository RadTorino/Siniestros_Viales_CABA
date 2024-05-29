# Observatorio de Movilidad y Seguridad Vial CABA: Siniestros Viales.

Este proyecto realiza un análisis exploratorio de datos del Observatorio de Movilidad y Seguridad Vial de Ministerio de transporte de la ciudad de Buenos Aires. El objetivo final es presentar un conjunto de dahsboards en PowerBI con información clara e insigths sobre como impactar posivamente en los siniestros viales que suceden en la Ciudad de Buenos Aires. 

## Estructura del Proyecto

### 0. Carpetas
En la carpeta *Datasets* se encuentran los archivos orginales `hechos.csv` y `victimas.csv` así como también los archivos finales (para usarse en el dashboard de PowerBI) y documento con datas del senso para poder acceder a la población general.

### 1. Carga de Dato
El notebook carga los datasets `hechos.csv` y `victimas.csv` para su posterior análisis.

### 2. Exploración de Datos
- **Verificación de valores nulos y duplicados**: Se revisan las columnas de los datasets para identificar y manejar valores nulos y duplicados.
- **Revisión de la estructura de los datasets**: Se muestran los primeros registros para entender la estructura y el contenido de los datos.

### 3. Limpieza de Datos
- **Manejo de valores nulos**: Se reemplazan o eliminan valores nulos en columnas clave.
- **Eliminación de duplicados**: Se eliminan registros duplicados si es necesario.

### 4. Análisis Descriptivo
- **Distribución de siniestros por fecha y hora**: Se analiza la frecuencia de siniestros en diferentes momentos del día.
- **Distribución de siniestros por tipo de calle**: Se analiza la frecuencia de siniestros según el tipo de calle.
- **Distribución de víctimas por edad, sexo y rol**: Se analiza cómo varían las características de las víctimas según la edad, el sexo y su rol en el siniestro.
- **Distribución de víctimas por tipo de vehículo**: Se analiza la frecuencia de víctimas según el tipo de vehículo involucrado.

### 5. Visualización de Datos
Se crean gráficos para visualizar:
- La cantidad de siniestros por hora del día.
- La cantidad de siniestros por tipo de calle.
- La cantidad de víctimas por edad, sexo y rol.
- La cantidad de víctimas por tipo de vehículo.

### 6. Conclusiones
Se identifican patrones y tendencias clave en los datos, y se proponen acciones basadas en los hallazgos, como campañas de prevención dirigidas a grupos específicos.

### 7. Exportación de Datos
Ambos datasets con los cambios realizados se exporta para su uso en un tablero de visualización.

### 8. Dashboards en Power BI

Este proyecto incluye dos dashboards en Power BI para monitorear los siguientes objetivos clave (KPI):

#### Dashboard 1: Reducción de la Tasa de Homicidios en Siniestros Viales
- **Objetivo**: Disminuir en un 10% la tasa de homicidios en accidentes de tránsito en los últimos seis meses en CABA, comparado con los seis meses anteriores.
- **Explicación**: Queremos reducir el número de personas que mueren en accidentes de tránsito. Medimos esto comparando el número de muertes en los últimos seis meses con los seis meses anteriores, ajustado por cada 100,000 habitantes.

#### Dashboard 2: Reducción de Accidentes Mortales de Motociclistas
- **Objetivo**: Reducir en un 7% el número de accidentes fatales que involucran a motociclistas en el último año en CABA, comparado con el año anterior.
- **Explicación**: Buscamos disminuir la cantidad de accidentes fatales que involucran a motociclistas. Comparamos el número de estos accidentes en el último año con el año anterior, y nuestro objetivo es una reducción del 7%.



