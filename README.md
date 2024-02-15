# Covid19_Analyts
Proyecto de análisis de datos oficiales acerca de la pandemia para obtener ingishts y aprender de los efectos de la misma en el mundo y El Salvador

## Problema de Negocio
Una entidad gubernamental del sistema de Salud en el Salvador enfrenta el desafío de comprender y analizar la propagación del COVID-19 para tomar decisiones informadas y eficaces en la gestión de la pandemia. Como científico de datos, analizaré los datos relacionados con el COVID-19 y presentar insights a través de visualizaciones que respondan a las siguientes preguntas clave:
1. ¿Cómo ha evolucionado el Covid-19 en El Salvador en comparación con el impacto observado a nivel global?

2. ¿Cuál ha sido la evolución de los nuevos casos diarios reportados de Covid-19 en El Salvador a lo largo del tiempo?

3. ¿Cuál es la evolución del índice de letalidad del Covid-19 en El Salvador, comparado con los países con los índices históricos más elevados?

4. Desde una perspectiva demográfica, ¿cuáles son las características que tienen un mayor impacto en el índice de letalidad de un país?

## Herramientas Utilizadas
Para la realización del proyecto se uso lo siguiente:

1. Python
2. Pandas
3. Numpy
4. Maplotlib
5. Seaborn
6. Sklearn

## EDA: Análisis Exploratorio de Datos 
Para este proyecto, utilizaremos datos proporcionados por la World Health Organization (WHO) para rastrear la propagación del Covid-19 a nivel mundial. Además, obtendremos información demográfica a nivel mundial por parte de United Nations.

### Los DataFrame a trabajar
El DataFrame df_covid_limpio contendrá los datos filtrados durante el proceso de Análisis Exploratorio de Datos (EDA) sobre la propagación del virus obtenidos de la WHO
<p align="center">
  <img src="https://github.com/EdwinGarcia9/Covid19_Analyts/assets/130804905/b18136fa-83e6-4487-8685-c153caa0e3b5" alt="codeimage-snippet_9">
</p>
El DataFrame df_population_limpio contendrá la información demográfica a nivel mundial filtrada durante el proceso de Análisis Exploratorio de Datos (EDA), obtenida de las United Nations.
<p align="center">
  <img src="https://github.com/EdwinGarcia9/Covid19_Analyts/assets/130804905/df940aca-56f7-4eae-aabc-9cb85d2b9f2d" alt="Descripción de la imagen">
</p>

## Resultados
1. ¿Cómo ha evolucionado el Covid-19 en el Salvador en comparación con el impacto observado a nivel global?
<p align="center">
  <img src="https://github.com/EdwinGarcia9/Covid19_Analyts/assets/130804905/95f1b68c-a96b-44a1-b1bd-3727c66cab35">
</p>
<br>
El Salvador aún con 201,853 casos confirmados de Covid-19 a comparación de los demás países tiene la menor cantidad de casos confirmados y esto se debe a que el país tuvo unas medidas sanitarias muy previsorias en tiempos de pandemia no obstante no estaba excepto en la presencia de casos aunque es muy mínima en comparación a los demás países, también tenemos que recalcar que la cantidad de población de El Salvador es muchísimo menor a la población de los demás países en el top 10 de distribución de casos.
<br>
<br>
<p align="center">
  <img src="https://github.com/EdwinGarcia9/Covid19_Analyts/assets/130804905/7c10ae6b-7633-487b-854c-d092a7ec5042" alt="Descripción de la imagen">
</p>
La progresión de los casos de COVID-19 en El Salvador, en comparación con otros países, se mantiene constante a lo largo del tiempo. A diferencia de China, que experimentó un aumento significativo entre diciembre de 2022 y enero de 2023, y de otros países que muestran un incremento casi constante en el número de casos, El Salvador ha logrado mantener un control eficaz de la propagación del virus. Este éxito se atribuye a las medidas sanitarias implementadas desde el inicio de la pandemia. Además, la menor densidad poblacional en El Salvador, en comparación con otros países de mayor extensión territorial, ha contribuido a un monitoreo más efectivo y controlado de la confirmación de casos.
<br>
<br>
2. ¿Cuál ha sido la evolución de los nuevos casos diarios reportados de Covid-19 en el Salvador a lo largo del tiempo?
<p align="center">
  <img src="https://github.com/EdwinGarcia9/Covid19_Analyts/assets/130804905/08c17808-2cd7-49bd-a073-fc38d4c6c5a9">
</p>
<br>
<p align="center">
  <img src="https://github.com/EdwinGarcia9/Covid19_Analyts/assets/130804905/4c4fac80-798b-4c6c-9cf3-d7dd00942958">
</p>
<br>
La evolución del COVID-19 en El Salvador ha sido influenciada por la respuesta del gobierno, manteniendo control en los primeros años. La variante Ómicron introdujo desafíos, con un repunte en abril de 2022 y un rebrote en agosto. Sin embargo, hacia finales de 2023, se observó una drástica reducción en los casos reportados, atribuible a medidas sanitarias y conciencia pública. Se destacan discrepancias en las fechas de reporte, sugiriendo posibles deficiencias en el sistema de notificación de casos.
<br>
<br>
3. ¿Cuál es la evolución del índice de letalidad del Covid-19 en El Salvador, comparado con los países con los índices históricos más elevados?
<p align="center">
  <img src="https://github.com/EdwinGarcia9/Covid19_Analyts/assets/130804905/0a9b10b9-3b9f-4cbd-a77c-e8e41804562c" alt="Descripción de la imagen">
</p>
<br>
El análisis del índice de letalidad del COVID-19 en El Salvador revela patrones interesantes y contrastantes en comparación con otros países. A lo largo de la pandemia, El Salvador ha mantenido consistentemente un índice de letalidad más bajo que la mayoría de los países, con un máximo registrado del 5.36%, ocurrido casi al inicio de la pandemia. A medida que la pandemia avanzaba, este índice disminuyó significativamente, llegando a un promedio cercano al 3.1% durante el punto álgido en el año 2021, aunque el surgimiento de la variante Omicron generó preocupaciones adicionales en el año 2022, El Salvador logró mantener su índice de letalidad relativamente bajo, alcanzando un mínimo del 2.14%. Esta tendencia de mantener un índice de letalidad más bajo y experimentar una disminución gradual a lo largo del tiempo, incluso en medio de la presencia de variantes más contagiosas, contrasta con la situación observada en otros países con mayores índices de letalidad.

<br>
<br>
4. Desde una perspectiva demográfica, ¿cuáles son las características que tienen un mayor impacto en el índice de letalidad de un país?
<br>
<p align="center">
  <img src="https://github.com/EdwinGarcia9/Covid19_Analyts/assets/130804905/14f2f2c6-70bd-4cb6-b2e5-a97a24e09015" alt="Descripción de la imagen">
</p>
<br>
Basado en el análisis de las características demográficas y su impacto en el índice de letalidad del COVID-19, se puede decir que la expectativa de vida emerge como el factor más relevante, representando el 28.46% de la variabilidad en el índice de letalidad. Esto sugiere que los países con una mayor expectativa de vida pueden tener una mejor capacidad para enfrentar y mitigar los efectos del virus, posiblemente debido a un sistema de salud más robusto y una población más saludable en general. La densidad poblacional también muestra una influencia significativa, representando el 26.67% de la variabilidad en el índice de letalidad. Este hallazgo resalta la importancia de considerar la densidad de población al evaluar el riesgo y la propagación del virus. Los países con una alta densidad poblacional pueden enfrentar mayores desafíos en el control de la transmisión del virus y la prestación de atención médica adecuada a los pacientes afectados, estos resultados subrayan la compleja interacción entre factores demográficos y la incidencia de enfermedades infecciosas como el COVID-19. Comprender cómo estas características demográficas influyen en la letalidad del virus es crucial para formar políticas de salud pública y estrategias de mitigación efectivas.

## Conclusión
El Salvador, a pesar de formar parte del continente americano, el continente con mas muertes registradas, ademas se observaron irregularidades en el registro de los casos reportados, no obstante ha destacado por tener uno de los menores números de casos confirmados y fatalidades relacionadas con el COVID-19. Este éxito se atribuye al manejo eficiente de las medidas sanitarias y de prevención implementadas por las entidades gubernamentales. Además, el país fue uno de los primeros en América Latina en asegurar y administrar dosis de vacunas contra el virus, lo que contribuyó significativamente a la protección de su población. El cierre temprano de aeropuertos y la menor densidad demográfica en comparación con otros países también han sido factores determinantes en la contención del virus en El Salvador.





