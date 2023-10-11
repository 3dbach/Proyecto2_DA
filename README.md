# Proyecto2_DA
Proyecto Individual  2 de Henry

# Análisis de Accidentes de Avión

Este proyecto tiene como objetivo realizar un análisis profundo de los accidentes de avión ocurridos desde principios del siglo XX con el propósito de entender sus patrones, tendencias y factores de riesgo. Además, se busca proporcionar recomendaciones y conclusiones que ayuden en la prevención de futuros accidentes.

## Tecnologías Utilizadas

Este proyecto se basa en el lenguaje de programación Python y hace uso de diversas bibliotecas y herramientas, incluyendo:

- Pandas
- Matplotlib
- Seaborn
- Numpy

## Estructura del Proyecto

El proyecto consta de los siguientes archivos y carpetas:

- `proyectoDA.ipynb`: El cuaderno Jupyter que contiene todo el código y análisis.
- `AccidentesAviones.csv`: El conjunto de datos utilizado para el análisis.
- `README.md`: El archivo actual que proporciona información detallada sobre el proyecto.

## Contexto del Proyecto

En este EDA, exploramos el conjunto de datos "AccidentesAviones.csv" con el objetivo de identificar patrones, tendencias y factores de riesgo asociados a los accidentes de avión. Cada columna del dataset se interpreta de la siguiente manera:

**Cada columna del dataset se puede interpretar de la siguiente manera:**

1. **Unnamed: 0**: Este parece ser un índice o un identificador de fila en el conjunto de datos.

2. **fecha**: La columna "fecha" indica la fecha en que ocurrió el accidente, lo que proporciona información temporal para el análisis.

3. **HORA declarada**: La columna "HORA declarada" representa la hora declarada del accidente, lo cual es importante para investigar tendencias horarias de los accidentes.

4. **Ruta**: La columna "Ruta" proporciona detalles sobre la ubicación o ruta del accidente, lo que puede ser relevante para comprender patrones geográficos.

5. **Operador**: La columna "Operador" identifica la compañía u organización que operaba la aeronave involucrada en el accidente.

6. **flight_no**: Si está disponible, la columna "flight_no" contiene el número de vuelo correspondiente al accidente.

7. **route**: La columna "route" describe la ruta del vuelo, lo que ayuda a entender la trayectoria de la aeronave antes del accidente.

8. **ac_type**: La columna "ac_type" especifica el tipo de aeronave que estuvo involucrado en el accidente, lo que es esencial para analizar diferencias entre los modelos de aeronaves.

9. **registration**: En "registration" se encuentra el número de registro de la aeronave, que sirve para identificar de manera única cada aeronave involucrada en los accidentes.

10. **cn_ln**: La columna "cn_ln" proporciona el número de construcción y la línea de la aeronave, lo cual es relevante para la identificación precisa de la aeronave.

11. **all_aboard**: En "all_aboard" se registra el número total de personas a bordo, lo que es un factor crítico en la evaluación de la magnitud de los accidentes.

12. **PASAJEROS A BORDO**: La columna "PASAJEROS A BORDO" detalla el número de pasajeros a bordo, lo que permite distinguir entre pasajeros y tripulación.

13. **crew_aboard**: Indica el número de miembros de la tripulación a bordo de la aeronave en el momento del accidente.

14. **cantidad de fallecidos**: La columna "cantidad de fallecidos" muestra el número total de personas fallecidas en el accidente, lo que es crucial para comprender las consecuencias mortales de cada evento.

15. **passenger_fatalities**: "passenger_fatalities" registra el número de pasajeros fallecidos específicamente.

16. **crew_fatalities**: Muestra el número de miembros de la tripulación que fallecieron en el accidente.

17. **ground**: Esta columna cuantifica el número de personas en tierra que se vieron afectadas por el accidente aéreo.

18. **summary**: La columna "summary" proporciona un resumen o descripción del accidente, lo que permite una comprensión narrativa de cada evento.


## Ejemplos y Visualizaciones

A lo largo del cuaderno `proyectoDA.ipynb`, encontrarás una variedad de visualizaciones que ayudan a comprender mejor los datos y los resultados del análisis. Estas visualizaciones incluyen gráficos de barras, histogramas, mapas de calor de correlación y tendencias a lo largo del tiempo. Se destacan hallazgos clave y se proporcionan explicaciones detalladas.

## Análisis y Conclusiones

El cuaderno `proyectoDA.ipynb` incluye análisis detallados sobre la cantidad de fallecidos, la tendencia de accidentes aéreos a lo largo del tiempo, valores atípicos y valores faltantes. Además, se presenta un análisis de correlación entre variables clave. Las conclusiones se basan en los resultados del análisis y ayudan a comprender factores de riesgo y tendencias en los accidentes de avión.

## Contribuciones

Si deseas contribuir a este proyecto, ¡estás invitado! Puedes abrir problemas (issues) o enviar solicitudes de extracción (pull requests) en caso de que encuentres formas de mejorar el análisis, corregir errores o agregar nuevas funcionalidades.

Esperamos que este análisis profundamente investigado y sus conclusiones ayuden a aumentar la conciencia sobre los accidentes de avión y contribuyan a la prevención de futuros accidentes en la industria de la aviación.
