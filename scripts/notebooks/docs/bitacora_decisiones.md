# Bitácora de decisiones del proyecto

| N.º | Decisión | Justificación | Efecto en el proyecto |
|---|---|---|---|
| 1 | Conservar los 159.520 registros originales. | Mantener la totalidad de los registros recibidos. | Se conserva el universo de análisis. |
| 2 | Estandarizar nombres de columnas y textos. | Evitar diferencias de escritura y facilitar el procesamiento. | Mejora la consistencia de los datos. |
| 3 | Crear la variable ESTADO_ETL. | Identificar registros NC, RAD y sin clasificar. | Facilita el análisis por estado. |
| 4 | No eliminar automáticamente los dos registros coincidentes en NIT y número de factura. | La coincidencia no demuestra por sí sola que sean duplicados. | Se evita eliminar información sin validación. |
| 5 | Convertir el valor de factura y el año a formato numérico. | Permitir cálculos y agrupaciones. | Facilita la construcción de indicadores. |
| 6 | No imputar automáticamente los valores faltantes. | Evitar asignar valores sin respaldo documental. | Se preserva la información original. |
| 7 | Agrupar resultados por año, unidad y estado. | Facilitar el análisis de los registros y valores. | Alimenta las visualizaciones del dashboard. |
| 8 | Contrastar los resultados con la fuente original. | Comprobar la consistencia del procesamiento. | Se valida el total de 159.520 registros y $369.544.807.950. |

**Nota:** Las decisiones descritas corresponden a los criterios metodológicos del proceso ETL y deben contrastarse con las actividades efectivamente ejecutadas.
