# DataScience_PI03
Este es un proyecto hecho por Martín Eluney Gómez Piñeiro, para el curso de Data Scients de Henry en la cohorte 5.
Para este proyecto se me dieron las siguientes pautas a seguir:

## Rol a desarrollar
En este contexto, una empresa prestadora de servicios de telecomunicaciones le encarga a usted la realización de un análisis completo que permita reconocer el comportamiento de este sector a nivel nacional. Considere que la principal actividad de la empresa es brindar acceso a internet, pero también es importante considerar el resto de los servicios.

Con el fin de monitorear la eficacia de los objetivos de la empresa, se le pide visualizar en un dashboard el siguiente KPI y establecer 3 KPIs adicionales producto de su análisis:

+ Evaluar el aumento o disminución de la variación porcentual trimestral del servicio de internet, cada 100 hogares por provincia.

## **Propuesta de trabajo (indicaciones)**

`Análisis Exploratorio de los datos`(_Exploratory Data Analysis = EDA_):
Debe incluir un informe en el que explique y justifique el análisis expuesto y los datos utilizados, complementando con las salidas visuales incorporadas en el EDA. La elección de la forma de presentación del reporte es libre.

`Dashboard`:
Debe ser funcional y coherente con el análisis y la historia que vayan a relatar.

`Análisis`: :warning:
No se calificará solamente la producción de gráficos con datos (dashboard), sino también los análisis y conclusiones que encuentren de estos.

`KPIs`:
Se deben sugerir 3 KPIs y deben aparecer en el dashboard. Tenga en cuenta que debe tener relación con el dataset y la historia que está contando, y debe explicar en la presentación el análisis y la funcionalidad de los KPIs sugeridos.

`Repositorio de GitHub`:
El repositorio debe contener un Readme principal donde se presente de forma general **su proyecto**.


## Pasos del proyecto
### **Busqueda de CSV's en ENACOM**
+ Abri la siguiente pagina: https://datosabiertos.enacom.gob.ar/home
+ Entre en las categorías: Telefonía móvil, Telefonía fija, Televisión y Internet
+ Dentro de las categorias visualice y busque los CSV's que crei que me serian utiles para el análisis
+ Descargue los CSV's seleccionados, para luegos llevarlos a un pequeño EDA donde selecionaria de nuevo si me servian o no.

### **Eda**
+ convertí todos los CSV's en dataframes separandolos por categoría (Telefonía móvil, Telefonía fija, Televisión y Internet) para su posterior análisis.
+ Visulaice todos los Dataframes por categorias para saber con que dataframes quedarme y cuales descartar
+ busque valores nulo en los dataframes que decidí quedarme.
+ busque valores duplicados en los dataframes que decidí quedarme.

### **Creacion Del Dashboards**

+ En power bi visualice los datos desde el apartados de Transformar datos donde visualice las tablas mas detalladamente y decidi como llevar a cabo el análisis
+ Cambie el nombre de las columnas de algunos CSV's
+ Cree una portada provisoria.
+ Comence analisando los detos de el servicio de internet.
+ Cree un grafico de lineas para visulizar el acceso de internet cada 100 hogares a lo largo de los años
+ Cree un grafico de barras apiladas para poder ver la media de Mbps contratados a lo largo de los años y sus porcentajes
+ Cree una tabla con la suma de accesos, a internet, totales por año cada cien hogares, por provicias.
+ Cree dos filtros uno de provincias y otro de años para el grafico anterior.
+ Cree un KPI con la variacion trimestral de acceso a inernet
+ Cree un KPI con el objetivo de contratacion de internet para el año 2022.
+ Segui con el analisis de la TV
+ Cree un grafico de lineas para visualizar el acceso a la TV satelital por suscripcion y satelital por año
+ Creeun grafico de barras apiladas para ver el porcentaje que corresponde a la TV satelital y por suscripcion del total por año.
+ Cree un grafico de barras para visulisar el acceso a tv pos suscripcion por provincia.
+ cree dos filtros para el grafico anterior uno para el año y otro para la provincia.
+ Cree 2 KPI's con la variacion trimestral de acceso a TV satelital y por suscripcion.
+ Cree 2 KPI's con el objetivo de contratacion de TV satelital y por suscripcion para el año 2022.
+ Analice la Tlefonía móvil.
+ Cree un grafico de lineas para visualizar el acceso a telefonía móvil pospago, prepago y operativo.
+ Cree un grafico de lineas para visualizar la variacion media de las empresas de telefonía móvil mas importantes.
+ Cree un grafico de dona para ver el numero total de accesos de telefonía móil para pospago, prepago y operativos.
+ Cree un KPI con la variacion trimestral de acceso a telefonía móvil.
+ Cree un KPI con el objetivo de contratacion de telefonía móvil para el año 2022.
+ Por ultimo Analice La telefonia fija.
+ Cree un grafico de areas para ver la representacion del Total de telefonias fijas, las que eran para hogar , las gubernamentales, las comerciales y las de otros.
+ Cree un grafico de lineas para ver la variacion trimestral de el acceso a telefonía fija.
+ Cree un KPI con la variacion trimestral de acceso a telefonía fija.
+ Cree un KPI con el objetivo de contratacion de telefonía fija para el año 2022.

### **Analisis**

Análisis Nacional de acceso a los servicios de telecomunicación

Se me encargo llevar a cabo un análisis a nivel nacional, en Argentina, sobre los principales servicios de telecomunicación, para ayudar a los objetivos de la empresa. Para llevar a cabo este análisis realizare un análisis del Internet, la Televisión, la Telefonía Móvil y la Telefonía Fija.
Este trabajo fue echo con los datos proporcionados por ENACOM, siendo los años mostrados para internet, televisión y Telefonía fija desde 2014 en adelante, y para Telefonía móvil desde el 2012/2013 en adelante. 

+ **Internet:**

  Al analizar el comportamiento de el acceso a internet cada 100 hogares, pude ver un aumento del acceso desde el año 2014 hasta el año 2021, donde el nivel de acceso decrece notablemente hacia el año 2022, incluso por debajo de los niveles vistos en el año 2014.  También hay que hacer hincapié en un aumento leve pero mayor al que se venía viendo, en los años anteriores, del año 2020 al 2021, aumento que se le puede atribuir al momento de pandemia vivido en esa época.
  El decrecimiento de la adquisición de servicios de internet puede dársele en parte al momento post pandémico, donde la gente ya no requiere con tanta necesidad el acceso a internet ya que los trabajos ‘Home Office’ vuelven poco a poco a ser en la oficina de sus respectivas empresas, las clases ya no son online, etc.
  También realice un análisis de la media de Mbps contratados a lo largo del año; como se podía intuir a medida que iba pasando el tiempo, y la tecnología aumentaba, la gente iba contratando servicios con mayor cantidad de Mbps de bajada, pero esta tendencia se vio incrementada por la pandemia y por lo tanto entre los años 2020-2022 la contratación de servicios con más de 30 Mbps aumento considerablemente.
  Además, realice un análisis de la suma total de accesos a internet por provincia, para así saber en que provincias poder hacer hincapié, teniendo en cuenta la población de cada provincia, en donde se deberían realizar campañas, para captar mas clientes potenciales, o bien sabiendo el total de clientes de nuestra empresa y el total de gente que contrata internet si deberíamos llevar a cabo promociones para captar clientes que estén contratando servicios en otra empresa.

  Por último, cree 2 KPI’s donde se muestran la variación trimestral de clientes a nivel nacional de internet y el objetivo de la empresa para el año 2022 (Aumentar un 10% la cantidad total de personas que contraten internet). En estos KPI’s se puede observar como se logro mantener la cantidad de clientes e incluso aumentarlos un 0.46% (Un aumento casi imperceptible) y la disminución del 50% por debajo del objetivo anual, teniendo así una clara advertencia de que la situación es crítica.

+ **Televisión:**

  Para el análisis de Televisión hice una distinción entre la TV contratada por suscripción y la TV satelital.
  Para el análisis del servicio de televisión llevé a cabo primero un análisis año a año de la contratación de TV satelital y TV por suscripción, donde pude observar una pequeña tendencia de aumento en la contratación de TV por suscripción desde el año 2014 hasta el año 2021, donde una vez más se observa una disminución abrupta de las contrataciones llegando a mínimos por debajo de las contrataciones del año 2014; por parte de la TV satelital se observa como poco a poco se iba disminuyendo la contratación de este servicio pero en 2021 la disminución es mucho mayor a la tendencia vista hasta el momento. Estas disminuciones se las podemos atribuir a el incremento de uso de plataformas por internet tanto para el entretenimiento audiovisual como, para lo que respecta a las noticias.
  Luego hice un análisis de porcentaje anual de los servicios de TV satelital y por suscripción para así saber exactamente cuanto terreno le estaba ganando la TV por suscripción a la satelital, viendo de esta forma que, del total de contrataciones de TV por año, la TV satelital pasa de un 28% en el año 2014 a un 21% en el 2022.
  Además, analice el total de contrataciones por suscripción anuales por provincia para ver así las provincias que disminuyeron o aumentaron el consumo a lo largo de los años, además de tener en cuenta así el total nacional de contrataciones y el total de nuestra empresa y ver si nuestra empresa debería llevar a cabo promociones para captar clientes de otras empresas a la nuestra, o simplemente promociones para captar nuevos clientes.
  Por último, cree 4 KPI’s donde se ve la variación trimestral de la TV satelital y por suscripción y los objetivos anuales para estas dos de la empresa. Donde se puede observar como la TV satelital sigue su tendencia de disminuir el consumo a lo largo del trimestre y la TV por suscripción mantuvo su total de clientes. Y con respecto a los objetivos de la empresa (un aumento del 10% en contrataciones de ambos servicios) ninguno fue cumplido. Teniendo que mirar así, si vale la pena seguir prestando servicios de TV satelital o no, y que rumbo tomar para mejorar la situación.


+ **Telefonía móvil:**

  Para el análisis de Telefonía móvil hice una distinción entre los tipos de servicio que se pueden prestar prepago, pospago y operativos.
  Comencé con un análisis año a año de la contratación de los servicios desde el año 2013 al año 2022, donde observé una disminución moderada en la contratación de estos desde el año 2013 al año 2021 donde la disminución se hizo mucho mas grande hacia el año 2022. Los servicios mas usados a lo largo del año son los operativos por delante y los prepagos muy pegados en cuanto a total de contrataciones siendo el pospago muy ampliamente superado por estos. Llegados a este punto donde la disminución de contratación en gran medida, se observa del año 2021 al 2022 ya no podemos culpar a nada por esta disminución tan grande más que a la economía del país y el bajo poder adquisitivo de la población.
  Además, realice una observación del aumento o disminución de los clientes de las principales empresas de Telefonía móvil del país, viendo así que, a excepción de Nextel que a partir del año 2017 no funciono más, para el año 2022 la variación de clientes es mínima, siendo Personal quien va en aumento, Claro en decremento y Movistar a pesar de estar por debajo de la media también en aumento.
  Por último, realice una visualización de los números totales de contrataciones de cada servicio para saber exactamente cuanto era para cada uno. Viendo así que a pesar de que el servicio de pospago es significativamente menor en cuanto a números con respecto a los otros dos servicios, sigue significando un numero grande de contrataciones.
  Para terminar, cree dos KPI’s uno para ver la variación trimestral de telefonía móvil y el objetivo anual para 2022 de la empresa (Aumentar un 10% la contratación del servicio), observando que casi no hubo variación en las contrataciones trimestrales y que el objetivo de la empresa nuevamente no pudo ser cumplido quedando un 76% por debajo de este. 

+ **Telefonía fija:**
  Comencé el análisis viendo una comparación del total de contrataciones del servicio de telefonía fija y los tipos de clientes, siendo la telefonía fija en hogares la más significativa, la telefonía en comercios y la telefonía gubernamental muy poco significativas, y habiendo una categoría más llamada otros, donde se encuentran unos pocos clientes, siendo así el tipo de cliente menos significativo de todos. Además, se puede observar como la telefonía fija fue en aumento hasta el año 2016 donde empezó a disminuir en contratación cada año más, hasta llegar a 2021 donde el decremento de contrataciones se haces mucho mayor yendo hacia el año 2022. Esta tendencia al decremento anterior al año 2021 puede atribuirse al comienzo de la telefonía fija a quedar obsoleta como tecnología siendo reemplazada poco a poco por la telefonía móvil. A partir de el año 2021 esta tendencia a disminuir ya no es atribuible a esto por la gran diferencia con respecto a años anteriores.
  También analice la variación de contratación a loa largo de los últimos 4 trimestres, habiendo un decremento notable del primer al segundo trimestre, un aumento moderado del segundo al tercer cliente y un decremento moderado del tercer al cuarto trimestre.
  Por último, cree 2 KPI’s uno con el objetivo anual de la empresa (aumentar 10% la contratación del servicio) y la variación trimestral de contratación del servicio, siendo esta ultima casi nula disminuyendo tan solo un 0.16%; y con respecto al objetivo de la empresa nuevamente no fue cumplido y se estuvo un 77% aproximadamente por debajo de este, demostrando nuevamente la situación crítica en la que nos encontramos.

#### **Conclusión**
La prestación de servicios de telecomunicación esta en crisis desde el año 2021, hay que encontrar una solución para dar vuelta esta situación, aunque algunos servicios muestran que comienzan a estabilizarse o incluso a aumentar poco a poco, hay que buscar medidas para poder aumentar la adquisición de los servicios que presta nuestra empresa, teniendo en cuenta el bolsillo del cliente y la situación económica del país, deberíamos disminuir los precios de nuestros servicios en una mediada que logre captar nuevos clientes sin causarnos perdidas. 
Además, hay que considerar si la prestación de algunos servicios sigue siendo útil para la empresa o solo son perjudiciales por las perdidas que representan a futuro, como puede ser la TV satelital o la telefonía fija, y en caso de mantenerse buscar formas para que estas perdidas potenciales no sucedan, viendo como promocionar el servicio
