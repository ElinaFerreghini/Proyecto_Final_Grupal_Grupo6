<p align='center'>
<img src ="https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png">
<p>

<h1 align='center'>
 <b>PROYECTO FINAL GRUPAL</b>
</h1>
 

# <h1 align="center">**`SISTEMA DE ALERTAS SISMICAS`**</h1>

# <h1 align="center">**Bienvenidos a nuestro proyecto final de la carrera de Ciencia de Datos. En este informe encontrarán el contexto del trabajo, las temáticas que abordaremos, el planteamiento de objetivos y algunos KPIs, cada uno con un breve análisis. Es importante destacar que este informe es un primer acercamiento al tema y no representa el proyecto final, sino más bien un informe inicial que será refinado y desarrollado a lo largo de estas semanas**</h1>


## **Contexto**

Los desastres naturales son eventos impredecibles que pueden resultar en un gran número de muertes, pérdida de propiedades y daños irreparables. Por esta razón, la predicción temprana y las medidas de protección y atención apropiadas resultan urgentes para minimizar su impacto.

Particularmente, los sismos son uno de los fenómenos naturales más devastadores y peligrosos. Aunque se han logrado avances significativos en la predicción de otros desastres naturales, como huracanes y tsunamis, la capacidad predictiva de los sismos sigue siendo limitada, y su principal consecuencia es el peligro para las comunidades que se ven afectadas. Por esta razón, es crucial tener una comprensión clara de cómo se producen los sismos y cómo se pueden predecir.

En este sentido, el análisis de datos desempeña un papel clave en la comprensión de los sismos y en la identificación de patrones y tendencias que pueden ayudar a predecir estos fenómenos o identificar las zonas de mayor riesgo. La recopilación y análisis de datos sísmicos, geológicos, geofísicos y geotécnicos, así como el uso de modelos matemáticos y de aprendizaje automático, pueden proporcionar información valiosa para desarrollar estrategias de prevención y mitigación de riesgos más efectivas.

En definitiva, el trabajo con estos datos es fundamental para comprender mejor los sismos y para tomar medidas que permitan reducir su impacto en las personas y en las comunidades afectadas. Además, es importante que los resultados obtenidos se compartan con las autoridades, los expertos en el campo y la sociedad en general para fomentar la toma de decisiones informadas y promover la conciencia sobre la importancia de la prevención y mitigación de riesgos en las zonas sísmicas

## **Presentación del trabajo**

Nos complace anunciar que hemos sido seleccionados para formar parte del equipo de atención de desastres de un país latinoamericano. En este momento, estamos trabajando en un emocionante proyecto tri-nacional en conjunto con los Estados Unidos (USGS) y Japón (JMA) llamado “Working towards global standardization of seismological networks and effective communication to the civilian community. ” 

Los objetivos de esta alianza son:

<h4>1. Crear una base de datos depurada que contemple los datos de las tres naciones de forma estandarizada:</h4>

Trabajaremos arduamente para crear una base de datos que contemple los datos de las tres naciones de forma estandarizada, lo cual permitirá a las autoridades crear un mecanismo de clasificación más efectivo. Ya nos han advertido que se presentarán algunos "problemas" de outliers, y que en su mayoría no son errores, por lo que seremos muy cuidadosos en el proceso.


<h4>2. Implementar mecanismos de comunicación y alerta a la comunidad civil en un lenguaje intuitivamente interpretable a través de Internet o cellBroadCast:</h4>

Nos enfocaremos en implementar mecanismos de comunicación y alerta que puedan ser comprendidos de forma fácil y rápida por el público en general. Sabemos que es importante para las personas saber si se han producido daños en los edificios o si la salud y la seguridad están en peligro. Por esta razón, traduciremos la información técnica a un lenguaje cotidiano y accesible, para que las personas puedan estar informadas y tomar medidas preventivas.
***********
Estamos emocionados de participar en este proyecto y contribuir a la prevención y mitigación de riesgos en las distintas comunidades. Trabajaremos para lograr nuestros objetivos y ofrecer resultados de calidad a todas las partes involucradas.


## Como lo hacemos?

### Enfoque 1 [Data Analysis focus]

Analizando profundamente la relacion de los sismos con otra u otras particularidades de su pais latinoamericano escogido.

Ejemplos de lineas de investigacion (Solo para que se inspiren. Pueden divagar y escoger lo que se les ocurra, su mente es el limite!):

- Sismicidad secundaria (después de un gran sismo) ¿cómo afecta? ¿Qué ha pasado? Se pueden anticipar medidas si es que hay algo sistemáticamente mal?
- Es aconsejable que haya una reubicación de habitantes en zonas como CDMX que es sabido esta construida en una zona geológicamente inestable y con alta actividad sísmica?
- Derribando (o acentuando) mitos: Tiene que ver el clima con la propensión a sismos de mayor “magnitud” y los cambios estacionales?
- Efectos secundarios no deseables: Sismos y Tsunamis, Problemas en redes eléctricas, incendios…


Entregables tangibles minimos:
Mapa de geolocalizacion de los sismos escogidos que contemple la actualizacion cada hora. 
La informacion que debe tener DEBE ser la escogida en su analisis. NO debe ir informacion cientifica como: Magnitud, Profundidad si esta no esta explicada o se indica por que es relevante.


### Enfoque 2 [Machine Learning Focus]

Aplicar un modelo de clasificacion no supervisada. 
La idea aqui NO sera predecir un sismo, sino, dadas las caracteristicas que tienen los sismos, clasificarlos segun patrones como Peligrosidad Media/Alta/Baja
o cualquier enfoque que quieran aplicar.

Entregables tangibles minimos:
Presentacion de las etiquetas de clasificacion y performancia del modelo.

- - -
<p align="center">
<img src= https://github.com/soyHenry/DS_LABS/blob/main/Proyectos/Proyectos%20Finales/Sistema%20de%20alertas%20sismicas/images/Contexto.png  height="500">
</p>

## **Datasets y fuentes complementarias**

Fuentes de datos obligatorias:
+ Estados Unidos https://earthquake.usgs.gov/fdsnws/event/1/
+ Japon https://www.data.jma.go.jp/multi/quake/index.html?lang=es
+ Observatorio Latinoamericano de su preferencia ***********

Nota: El producto final debe tener en su etapa de *extraccion* los datos en formato JSON o GeoJSON. Formatos de texto como CSV podrian usarse en los pasos intermedios para hacer sus test respectivos de ser necesario, pero no seran admitidos en la entrega final.

Fuentes de datos alternativas
+ Ejemplo de inspiracion de ciencia para la sociedad: https://twitter.com/cfariasvega/status/1586112199524614144?t=ZI428WweSDDuG_m_uWhlDg&s=19

Exitos!! <3

<img src = "https://blog.alertandote.com/wp-content/uploads/2018/04/Scared-Marge-Simpson-GIF-downsized_large.gif" height = 200>

## Disclaimer  
De parte del equipo de Henry se quiere aclarar y remarcar que los fines de los proyectos propuestos son exclusivamente pedagógicos, con el objetivo de realizar proyectos que simulen un entorno laboral, en el cual se trabajen diversas temáticas ajustadas a la realidad.
 No reflejan necesariamente la filosofía y valores de la organización. Además, Henry no alienta ni tampoco recomienda a los alumnos y/o cualquier persona leyendo los repositorios (y entregas de proyectos) que tomen acciones en base a los datos que pudieran o no haber recabado. Toda la información expuesta y resultados obtenidos en los proyectos, nunca deben ser tomados en cuenta para la toma real de decisiones (especialmente en la temática de finanzas, salud, política, etc.).
