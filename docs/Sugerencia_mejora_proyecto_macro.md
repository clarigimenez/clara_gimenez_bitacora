# Sugerencia de mejora: Proyecto Macro

*por: Equipo Sociedad*

El trabajo está muy completo y las conclusiones están bien comunicadas. Todo estaba bien subido y documentado en el repositorio de GitHub y pudimos clonarlo sin problemas. Proponemos una sugerencia menor de consistencia sobre el período de una de las tendencias.

El trabajo declara como período de análisis 2006-2018 para la actividad, sin embargo, la tendencia de actividad de las secciones 5 y 9.9 se calcula con la serie completa del archivo, 2000-2018. Usar la serie completa de cada variable es una decisión válida y está justificada en el código, pero el período no queda aclarado. Donde se nota es en Montevideo: en el gráfico 9.2 su actividad sube entre 2006 y 2018, mientras que en el gráfico 9.9 aparece con tendencia negativa. Los dos resultados son correctos, pero miden períodos distintos.

Vemos dos opciones:

- **Aclarar el período:** mantener el cálculo como está y agregar "2000-2018" en el título del gráfico 9.9 y en la nota de la sección 5.
- **Recortar a 2006:** si prefieren que todo el trabajo hable del mismo período. En ese caso cambian algunas conclusiones que dependen de esa tendencia, como la cantidad de departamentos donde crece la actividad y su relación con la pobreza.

En el script Sugerencia_mejora_proyecto_macro.ipynb se pueden ver las dos versiones comparadas.
