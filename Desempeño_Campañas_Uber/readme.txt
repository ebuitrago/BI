Problema:

Uber es una empresa que proporciona vehículos de transporte con conductor a sus usuarios, haciendo uso de una aplicación móvil. 

Para este caso ficticio, tenga en cuenta los siguientes supuestos:

●	Uber maneja cinco categorías de viajes: UberX, UberPool, UberConfort, UberGreen y UberBlack. 
●	Estamos en octubre de 2014 y disponemos de los datos de viajes entre abril y septiembre de este año, realizados en Nueva York.
●	Cada categoría de viaje tiene un precio único, que no depende ni del tiempo del trayecto ni la distancia recorrida.

Con estos supuestos en mente, la empresa le ha pedido evaluar el desempeño de dos campañas realizadas. La primera campaña consiste en bajar el precio de los viajes en horas valle, es decir en horas de baja demanda, en todas las categorías de viajes. La segunda tiene como fin impulsar el crecimiento de los viajes de UberPool, y consiste en un descuento para esta categoría, sin importar el horario.

Con el fin de mitigar el riesgo de posibles efectos negativos que no se tenían previstos, se tiene la política de implementar las campañas por zonas, aplicando las promociones en una zona a la vez para luego decidir si es buena idea aplicarlo a las demás. Es por esto que se eligió Jersey City como lugar de prueba de la primera promoción. En esta zona se han aplicado reducciones en el precio de todos los viajes en horas de baja demanda (entre las 00:00 y las 11:00) desde junio hasta septiembre. En cuanto a la segunda promoción, se seleccionó Brooklyn como zona de pruebas, en donde se han aplicado reducciones de precio a los viajes de UberPool desde agosto hasta septiembre.

El análisis solicitado tiene como objetivo determinar si las campañas tuvieron buenos resultados, determinar si se deben aplicar en todas las zonas y dar recomendaciones, para lo cual le han suministrado los precios y margen de ganancias de cada categoría de viaje en cada uno de los tres escenario:

Categoría del viaje	Escenario sin promociones	Promoción 1 (precio y margen en horas valle)	Promoción 2
	Precio	Margen	Precio	Margen	Precio	Margen
UberX	9.99	40%	8.99	36%	9.99	40%
UberPool	6.99	30%	6.49	27.85%	4.99	21.42%
UberConfort	14.99	50%	13.99	46.66%	14.99	50%
UberGreen	12.99	60%	11.99	55.38%	12.99	60%
UberBlack	16.99	60%	15.99	56.47%	16.99	60%
Además de esta información, le han proporcionado los datos de los viajes desde abril hasta septiembre, los cuales se encuentran en los archivos “datos_abril.csv”, “datos_mayo.csv”, “datos_junio.csv”, “datos_julio.csv”, “datos_agosto.csv” y “datos_septiembre.csv”. Cada uno corresponde a un mes y todos incluyen las siguientes columnas:

●	Date.Time: Fecha y hora de solicitud del viaje
●	Lat: Latitud de punto de inicio del trayecto
●	Lon: Longitud del punto de inicio del trayecto
●	Category: Tipo de viaje (UberX, UberPool, UberConfort, UberGreen, UberBlack)
●	Zone: Zona para realizar pruebas. Está marcada como “Jersey City”, “Brooklyn” y “Other” si no corresponde a ninguna de las dos primeras

Como último detalle, un aspecto que preocupa al equipo de marketing es que las reducciones de precio causen efectos de canibalización de productos, por lo que le solicitan tenerlo en cuenta al momento de realizar los análisis.

Evaluación: 
Se evaluarán tres aspectos en el proyecto:
●	Modelos matemáticos / pruebas estadísticas: 30%
●	Diseño de tableros de control (dashboards) para la toma de decisiones y que respondan a las necesidades de la organización: 30%
●	Reporte gerencial: 40%
El proyecto se puede desarrollar en grupos de máximo tres personas y debe ser enviado a más tardar el viernes 28 de mayo al correo dlopezc12@ucentral.edu.co, con el asunto “Proyecto 2”. En este correo se deben incluir los nombres de los integrantes del grupo y siguientes entregables:

1.	Código de los modelos o pruebas estadísticas implementadas (R o Python).
2.	Archivos para visualizar tablero de control (puede ser archivo Power BI, Google Data Studio, R o Python).
3.	Reporte gerencial que incluya metodologías implementadas, hallazgos encontrados, recomendaciones para el manejo de su información, recomendaciones para la empresa, discusión de limitaciones y alternativas a su solución.
4.	Presentación en la cual se muestre el proceso de exploración de datos y el análisis de los modelos o pruebas estadísticas implementadas. Además, debe incluir pantallazos de la visualización, explicando la importancia de cada elemento en esta, como los KPIs y gráficas. Esta presentación se expondrá en la clase del viernes 28 de mayo.

Bibliografía

Datos tomados de Uber Pickups in NYC de DATA SOCIETY y posteriormente modificados. Las promociones y sus efectos son ficticios, así como las categorías de los viajes y observaciones adicionales generadas aleatoriamente.
https://data.world/data-society/uber-pickups-in-nyc.
