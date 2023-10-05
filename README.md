 # <p align="center"> Transito_CABA </p>
### <p align="center">Proyecto de Análisis sobre un dataset de Accidentes con Víctimas en la Ciudad Autónoma de Buenos Aires (CABA)</p>


<p align="justify"> Este proyecto se enfoca en el análisis de un conjunto de datos relacionados con incidentes y víctimas de accidentes de tránsito en el área de la Capital Federal y Gran Buenos Aires (CABA) durante el período comprendido entre 2016 y 2021. El conjunto de datos se presenta en formato xlsx y consta de dos hojas principales denominadas "hechos" y "víctimas". Además, se incluyen dos hojas adicionales que sirven como diccionarios de datos para comprender mejor la estructura y el significado de las variables en el conjunto de datos.
El objetivo principal de este proyecto es realizar un análisis exploratorio de datos (EDA) para investigar y comprender las características clave de los datos contenidos en estas hojas. El EDA implica la aplicación de técnicas estadísticas y visuales para revelar patrones, tendencias y relaciones dentro de los datos. Esto proporciona una base sólida para la toma de decisiones y la generación de información útil.
<p align="center">Descripción del problema</p>

<p align="justify"> Los siniestros de tránsito siguen siendo la causa principal de muerte en jóvenes. El 49% de las víctimas fatales tenían entre 25 y 54 años de edad; mientras que el segundo grupo es el rango etario de 15 a 24 años. La edad promedio de los fallecidos es de 43 años.
El análisis exploratorio de datos (EDA) realizado en el dataset ha revelado una serie de patrones y tendencias significativas.
Un ejemplo notable se evidencia al examinar la cantidad de víctimas por año en el gráfico de líneas y la tabla correspondiente.</p> 

<p align="justify"> En un vistazo general, se puede apreciar una disminución gradual en el número de accidentes a lo largo de los años, lo cual es un indicio positivo de una posible mejora en la seguridad vial. Sin embargo, surge un año que rompe con esta tendencia descendente, específicamente el año 2018, donde se registra la cifra más alta de víctimas fatales en comparación con los años analizados en el datased. Respecto al año 2020 donde igualmente se registraron 81 víctimas fatales, sería un año atípico y se correlaciona directamente con la expansión global de la pandemia del coronavirus (COVID-19). Las restricciones de movilidad y la implementación de medidas de cuarentena durante ese período afectaron significativamente la circulación de vehículos, permitiendo únicamente la movilización de vehículos de emergencia y de seguridad. Esto podría haber influido en la disminución general de accidentes.</p> 
<p align="center">
<img src= https://github.com/carlosab2021/Transito_CABA/assets/86332466/b312d5df-f819-4db0-a84b-c46169f6e37c ></p>

<p align="center">
<img src= https://github.com/carlosab2021/Transito_CABA/assets/86332466/3d7a2bfa-59f3-440f-a1b7-5b45f1bc8ddf ></p>

 
<p align="center">Por otro lado, para observar los datos atípicos se aplicó un gráfico de dispersión por víctimas:</p>
<p align="center">
<img src= https://github.com/carlosab2021/Transito_CABA/assets/86332466/41be3230-bc48-42e3-86fa-1d49dcc24a13 ></p>

 
<p align="justify"> Los valores atípicos identificados en el conjunto de datos corresponden a un total de 19 accidentes en los cuales se registraron 2 víctimas fatales. Además, se destaca un accidente excepcional donde se reportaron 3 víctimas fatales. Este accidente particular está registrado bajo el ID 2017-0035 y ocurrió el 23 de marzo de 2017 a las 05:00:00 horas.
Es importante destacar que este incidente atípico ocurrió en una avenida y la causa registrada involucra la categoría de "AUTO-OBJETO FIJO". Estos tipos de incidentes pueden ser considerados excepcionales debido a la alta cantidad de víctimas fatales involucradas y las circunstancias particulares del accidente.
La identificación de estos valores atípicos es fundamental para comprender la distribución general de accidentes y víctimas en el conjunto de datos y puede servir como punto de partida para investigaciones más detalladas sobre las causas y circunstancias que llevaron a estos incidentes inusuales.

*<p align="justify">Extracto de la noticia referida el hecho, con fines analíticos: El siniestro ocurrió cerca de las 4:20 cuando, por causas que aún se desconocen, el conductor de un Audi A4 negro perdió el control del vehículo que circulaba a alta velocidad y chocó contra un árbol, en la esquina de avenida Tristán Achaval Rodríguez y Azucena Villaflor, en la zona de Costanera Sur. Como consecuencia del impacto dos jóvenes mendocinos murieron en el lugar y un tercer ocupante debió ser trasladado al hospital Argerich del barrio porteño de La Boca, donde cerca de una hora más tarde falleció, según confirmó a Télam el director del Sistema de Atención Médica de Emergencias (SAME), Alberto Crescenti.* </p>

<p align="center">
<img src= https://github.com/carlosab2021/Transito_CABA/assets/86332466/8012b81d-8541-4e75-b5fd-f931bfeb2bf3 >Fuente:https://www.eldia.com/nota/2017-3-23-7-54-29-impactante-choque-en-puerto-madero-2-muertos</p>


Si dentro de esos datos se hace foco a los accidentes con víctimas fatales ocurridos los fines de semana donde además obtenemos los hechos ocurridos en la franja horaria de la madrugada obtenemos lo siguiente:
 <p align="center">
<img src= https://github.com/carlosab2021/Transito_CABA/assets/86332466/60c99906-ceb5-419b-aeed-c4375f70251c)

Del total de 717 accidentes, el 28,17% ocurrieron los fines de semana de los cuales el 21,29% pertenecen a la franja horaria de la madrugada (01:00 a las 05:59). 
<p align="center">
<img src= https://github.com/carlosab2021/Transito_CABA/assets/86332466/aba83abd-3f47-45c2-a886-36ff4eed4f17 ></p>

<p align="center">En cuanto al tipo de calle, de los 717 accidentes 442 fueron en la AVENIDA o sea un 61,64%.</p>
<p align="center">
<img src= https://github.com/carlosab2021/Transito_CABA/assets/86332466/27ecf279-bc80-46ef-9f44-b8d9684a0954></p>

<p align="justify"> Es interesante observar que, al analizar los accidentes por acusados, se puede notar lo siguiente:
•	Los accidentes con víctimas fatales se dividen en varias categorías de acusados, y los tres más comunes son AUTOS, PASAJEROS y CARGAS.
•	AUTOS representan la categoría más grande con 210 accidentes, lo que equivale al 29.28% del total.
•	PASAJEROS son responsables de 178 accidentes, lo que constituye el 24.82% del total.
•	CARGAS también es una categoría significativa con 150 accidentes, representando el 20.92% del total.
•	Además de estas categorías principales, hay otros tipos de acusados como MOTO, OBJETIVO FIJO, MULTIPLE, BICICLETA, SD (Sin Datos) y TREN, que conforman el resto de los accidentes.
Este análisis proporciona una visión clara de las categorías de acusados más frecuentes en los accidentes con víctimas fatales y destaca la importancia de centrar los esfuerzos en la prevención de accidentes en estas categorías principales, como AUTOS, PASAJEROS y CARGAS, para reducir la incidencia de víctimas fatales en accidentes de tránsito. </p>
<p align="center">
<img src= https://github.com/carlosab2021/Transito_CABA/assets/86332466/940e1e9c-0c08-4e17-8d07-a1915e941c17></p>

<p align="justify"> En la muestra de víctimas de accidentes de tránsito, la mayoría de las víctimas son de sexo masculino (526), representando un número significativamente mayor en comparación con las víctimas de sexo femenino (164). Esto podría sugerir diferencias en los patrones de accidentes de tráfico entre géneros o en la exposición al riesgo de accidentes. </p> 

<p align="center">
<img src= https://github.com/carlosab2021/Transito_CABA/assets/86332466/547657c5-4b09-4c3e-bed6-1da9010fa932></p>

 
<p align="justify">En gráfico de Líneas se observa, una tendencia diminutiva con respecto a los accidentes con víctimas donde el acusado es AUTO, mientras que PASAJEROS posee un comportamiento irregular aumentando considerablemente en el año 2018. Asimismo, el aumento que se observa de OBJETIVO FIJO, en el año 2017, se debe al dato atípico ya mencionado en el gráfico de dispersión.</p>
<p align="center">
<img src= https://github.com/carlosab2021/Transito_CABA/assets/86332466/f0f7062b-2f7b-4a49-8faf-5a0cc505eec4></p><p align="center"><img src=https://github.com/carlosab2021/Transito_CABA/assets/86332466/d7a9dc2a-88b7-4b78-9285-a28c2a612d83></p>

     
<p align="justify">En el gráfico de mapa, se contextualizan los accidentes con víctimas fatales por las principales Avenidas de CABA, como Gral Paz, Libertador, Ricardo Balbin, Remedio de Escalada, Independencia, Rivadavia, entre otras, ya que registran porcentualmente la mayor cantidad de accidentes. Se observan las ubicaciones por coordenadas de Latitud y Longitud en estas avenidas, lo que podría servir para tomar algunas medidas de prevención específicas en estas vías clave. Este análisis es fundamental para identificar áreas de mayor riesgo y planificar estrategias de prevención más efectivas en las avenidas más transitadas de la ciudad.</p>
<p align="center">
<img src= https://github.com/carlosab2021/Transito_CABA/assets/86332466/7c7a39f4-2453-4a80-8e9b-bd722af599f0></p>


<p align="justify"> Por último, se presenta tres indicadores clave de rendimiento (KPIs) cruciales para evaluar la seguridad vial y la efectividad de las medidas de prevención en la Ciudad Autónoma de Buenos Aires (CABA). Estos KPIs se han seleccionado cuidadosamente para abordar aspectos específicos de la seguridad vial y brindar una visión integral de la situación actual. A continuación, se presenta el fundamento detrás de cada uno de estos KPIs:
KPI 1: Reducción del 10% de accidentes con víctimas fatales en el último semestre:
Este indicador se centra en evaluar la eficacia de las políticas y acciones implementadas en el último semestre para reducir la cantidad de accidentes con víctimas fatales en CABA. La seguridad vial es una preocupación constante, y esta métrica nos permitirá medir si se ha logrado un avance significativo en este período en comparación con el semestre anterior. </p>

<p align="center">
<img src= https://github.com/carlosab2021/Transito_CABA/assets/86332466/898e201e-e695-472e-a5c5-11559c6880c1></p>

 <p align="justify"> Este KPI se centra en el análisis del último semestre del año más reciente registrado en nuestro conjunto de datos, lo que permite adaptar este análisis a otros años y períodos para llevar a cabo evaluaciones comparativas. Los resultados muestran una notable tasa de reducción del 42% en accidentes viales con víctimas fatales durante este último semestre. 
KPI 2: Reducción del 07% de víctimas por accidente de motos en el último año en comparación al año anterior:
Las motocicletas son vehículos particularmente vulnerables en accidentes de tráfico. Este KPI evalúa si las medidas tomadas en el último año han contribuido a reducir el número de víctimas en accidentes de motos. Esta métrica es fundamental, ya que se enfoca en un grupo específico de usuarios de la vía y permite monitorear el impacto de las políticas dirigidas a mejorar la seguridad de los motociclistas. </p>

<p align="center">
<img src= https://github.com/carlosab2021/Transito_CABA/assets/86332466/0867a5e2-6da9-445a-a54d-afaf904f998b></p>

<p align="justify"> Este KPI se enfoca en los accidentes que involucran a víctimas que viajaban en motocicletas, y los resultados revelan un preocupante aumento del 64% en el último año analizado en nuestro conjunto de datos. Este incremento podría ser atribuido a diversos factores, siendo uno de los más destacados la notable proliferación de motocicletas en las calles de la Ciudad Autónoma de Buenos Aires (CABA).
 KPI 3: Reducción del 12% de accidentes con víctimas fatales ocurridos en Avenidas:
Las avenidas suelen ser vías de tráfico rápido y alto flujo vehicular. Evaluar la cantidad de accidentes con víctimas fatales en estas vías es transcendental, ya que pueden representar un alto riesgo. Este indicador se enfoca en medir la efectividad de las medidas implementadas para reducir los accidentes con víctimas fatales en las avenidas de CABA, con el objetivo de mejorar la seguridad en estas zonas específicas.</p>

<p align="center">
<img src= https://github.com/carlosab2021/Transito_CABA/assets/86332466/2ceddeea-54b2-4798-b654-f21455903d32></p>


<p align="justify"> Este KPI se centra en la reducción de accidentes con víctimas fatales ocurridos específicamente en avenidas, los resultados muestran un aumento del 17% en la cantidad de accidentes en este tipo de vías durante el último año analizado en comparación con el año anterior.
El objetivo establecido era reducir la cantidad de accidentes en un 12%, lo que habría requerido una disminución significativa en el número de incidentes en avenidas. Para alcanzar este objetivo, habría sido necesario evitar 15 accidentes en el último año. Estos resultados indican que, en lugar de una disminución, hubo un aumento en la frecuencia de accidentes en estas áreas específicas de la Ciudad Autónoma de Buenos Aires (CABA).
Esta situación pone de manifiesto la necesidad de implementar estrategias y medidas de prevención adicionales en las avenidas de CABA, con el objetivo de reducir la incidencia de accidentes y garantizar la seguridad de los usuarios de estas vías. Es fundamental evaluar las causas subyacentes de este aumento y desarrollar soluciones efectivas para abordar este desafío en particular. 
Estos KPIs proporcionan una visión holística de la seguridad vial en CABA y ayudarán a evaluar el progreso hacia la reducción de accidentes y víctimas fatales. Su seguimiento constante permitirá tomar decisiones informadas para mejorar aún más la seguridad en las calles de la ciudad. </p>

Links de interés :[Visitar GitHub](https://github.com/carlosab2021/Transito_CABA)

Se agrega al proyecto el archivo eda2.ipynb, donde se observa el paso a paso de las extracciones de los datos.  
