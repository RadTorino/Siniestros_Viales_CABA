# Análisis Exploratorio de Datos de Siniestros y Víctimas

Este proyecto realiza un análisis exploratorio de datos (EDA) utilizando dos datasets: `hechos.csv` y `victimas.csv`. El objetivo es identificar patrones y tendencias en los siniestros y las características de las víctimas.

## Estructura del Proyecto

### 1. Carga de Datos
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
El dataset `victimas` con los cambios realizados se exporta para su uso en un tablero de visualización.

