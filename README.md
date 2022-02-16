# Análisis de Estadísticas de Nacidos Vivos del Hospital Manuel Uribe Ángel en Envigado, Antioquia
(Aplicación de Metodología CRISP-DM)
<br/>
<br/>
_Presentado por [Pilar Camargo Márquez](https://www.linkedin.com/in/pilarcamargo/) (1201656) y [Andrés Lindarte Niño](https://www.linkedin.com/in/andr%C3%A9s-lindarte-709876113/) (1201397)_
<br/>
ELECTIVA: Big Data / [Ing. Marcela Mejía](https://www.umng.edu.co/documents/20127/0/MARCELA+MEJIA.pdf/68fee29d-ffa5-de8f-4254-af01df420479?t=1599703431196)
<br/>
Ingeniería en Multimedia
<br/>
Facultad de Ingeniería
<br/>
Universidad Militar Nueva Granada
<br/>
Bogotá D.C., Colombia


### INTRODUCCIÓN
La E.S.E Hospital Manuel Uribe Angel es una institución prestadora de servicios de salud que, en garantía al derecho de acceso a la Información Pública (establecida en la Ley 1712 de 2014) y alineado a la política de Gobierno Digital de MinTIC, promueve la transparencia y el acceso a la información pública a través de la apertura, la reutilización de los datos públicos, el uso y la apropiación de las TIC. A continuación se comprueba el análisis del conjunto de datos que contiene los nacimientos reportados por el Hospital Manuel Uribe Ángel, con una cohorte de enero 2018 hasta septiembre 2019 del municipio de Envigado del departamento de Antioquia.



### FICHA TÉCNICA
<div align="center">
    <img src="https://raw.githubusercontent.com/justoneye/NacidosVivos-HospitalManuelUribeAngel/master/PPT/Diapositiva04.JPG" alt="Ficha Técnica para Estudio " width="100%"/>
</div>



### ELECCIÓN DE BASE DE DATOS
Teniendo en cuenta los parámetros de selección de la base de datos (dimensión mínima de 10 variables y 500 observaciones) así como su procedencia (de libre escogencia y orígen), además de una inspección acerca de la naturaleza de la mismas y las posibles preguntas de negocio a resolver; tras una búsqueda de posibles data frames alojadas en el sitio web gubernamental de Datos Abiertos (https://www.datos.gov.co) administrada por el Ministerio de Tecnologías de la Información y Comunicaciones (MinTIC), se ha seleccionado la base da datos “Nacidos Vivos en Hospital Manuel Uribe Angel”: https://www.datos.gov.co/Salud-y-Protecci-n-Social/Nacidos-Vivos-en-Hospital-Manuel-Uribe-Angel/udqu-ifxr.



### OBJETIVOS
General: Identificar las condiciones de salud que influyen en el número de Nacidos Vivos del Hospital Manuel Uribe Ángel del municipio de Envigado, Antioquia.
<br/>
Específicos:
- Indagar sobre posibles relaciones entre datos que puedan ayudar al Hospital a mostrar el panorama actual de las condiciones de salud que pueden influir en el número de nacidos vivos y su calidad de vida.
- Intentar predecir posibles escenarios que permitan al Hospital hacer planes de acción y contingencia para determinadas situaciones de riesgo en la salud neonatal.
- Solucionar las preguntas planteadas a través de las diferentes técnicas de análisis y limpieza para análisis de bases de datos.
- Implementar correctamente los pasos de la metodología Cross Industry Standard Process for Data Mining (CRISP-DM).
- Aplicar los conocimientos técnicos y analíticos adquiridos a lo largo del semestre.



### PREGUNTAS 
<div align="center">
    <img src="https://raw.githubusercontent.com/justoneye/NacidosVivos-HospitalManuelUribeAngel/master/PPT/Diapositiva09.JPG" alt="Preguntas" width="100%"/>
</div>



### APLICACIÓN DE METODOLOGÍA
De acuerdo con las pautas del método CRISP-DM, esta fue la consecución de pasos para el desarrollo, ejecución y despliegue del proyecto:



### ANÁLISIS DE DATOS 
Tras la implementación y ejecución de la solución planteada y el posterior análisis de resultados de los datos obtenidos en el data frame para esta aplicación se llegaron a las siguientes conclusiones:

#### 1. ¿Cuáles son las características promedio de la madre gestante y el recién nacido?

<div align="center">
    <img src="https://raw.githubusercontent.com/justoneye/NacidosVivos-HospitalManuelUribeAngel/master/PPT/Diapositiva27.JPG" alt="Pregunta 1" width="100%"/>
</div>


#### 2. ¿Cuál es la diferencia de desempeño entre el primer y segundo test de Apgar?

<div align="center">
    <img src="https://raw.githubusercontent.com/justoneye/NacidosVivos-HospitalManuelUribeAngel/master/PPT/Diapositiva28.JPG" alt="Pregunta 2" width="100%"/>
</div>

#### 3. ¿Existe una relación entre la edad de las madres y los embarazos prematuros?

<div align="center">
    <img src="https://raw.githubusercontent.com/justoneye/NacidosVivos-HospitalManuelUribeAngel/master/PPT/Diapositiva29.JPG" alt="Pregunta 3" width="100%"/>
</div>


#### 3. ¿Existe una relación entre la edad de las madres y los embarazos prematuros?

<div align="center">
    <img src="https://raw.githubusercontent.com/justoneye/NacidosVivos-HospitalManuelUribeAngel/master/PPT/Diapositiva29.JPG" alt="Pregunta 3" width="100%"/>
</div>

#### 4. De 200 embarazos en un mes determinado, ¿cuántos serán de madres gestantes de 21 años o menores?

<div align="center">
    <img src="https://raw.githubusercontent.com/justoneye/NacidosVivos-HospitalManuelUribeAngel/master/PPT/Diapositiva30.JPG" alt="Pregunta 4" width="100%"/>
</div>

_Pendiente:  0.23290013053335476
<br/>
Intercepción:  7.942872191815312
<br/>
array([54.5228983])
<br/>
0.8359589089188763_


#### 5. ¿Se puede predecir el peso de un recién nacido según su tiempo de gestación y su talla?

<div align="center">
    <img src="https://raw.githubusercontent.com/justoneye/NacidosVivos-HospitalManuelUribeAngel/master/PPT/Diapositiva31.JPG" alt="Pregunta 5" width="100%"/>
</div>

_Pendiente:  116.2127800441558
<br/>
Intercepción:  -5202.7233875116735
<br/>
array([2657.39729424])
<br/>
0.6699870584973598_



### CONCLUSIONES 
Tras la implementación y ejecución de la solución planteada y el posterior análisis de resultados de los datos obtenidos en el data frame para esta aplicación se llegaron a las siguientes conclusiones:
- Como primera instancia y haciendo una revisión de los datos promedio obtenidos del estudio, podemos afirmar, a priori,  la ausencia de datos atípicos con respecto a las características de la madre y su recién nacido. Tampoco encontramos picos negativos en la diferencia del test de Apgar, lo cual nos da la certeza que, dentro de los primeros cinco minutos de vida, el bebé es apto para sobrevivir y desarrollarse separado de su madre, además de presentar un esquema de salud positivo. Teniendo en cuenta las condiciones promedio de un parto es posible hacer proyecciones tanto de las madres gestantes y sus recién nacidos como la composición familiar nuclear del municipio de Envigado cuya información podría repercutir incluso en la toma de decisiones administrativas y financieras del municipio.
- Podemos afirmar, que las madres gestantes que presentaron embarazos prematuros, son madres cuyas edades están por debajo de los 26 años, que es el promedio de edades dado por el estudio. Lo cual nos indica que un embarazo a edad temprana (dentro de la población donde se realizó el estudio) es más proclive a ser prematuro.
- La mayoría de las variaciones del test de Apgar ayudan a mostrar que la mayoría de los recién nacidos son viables, y aunque los cambios considerables son de tener cuidado y constante vigilancia se puede decir que las condiciones tanto el hospital como las familias son las suficientes para garantizar los primeros meses de vida.
- Dados los datos que se poseían para trabajar, decidimos hacer una predicción muy próxima a los meses siguientes del estudio, que no se han realizado. Teniendo en cuenta que: Las madres jóvenes son más proclives a dar a luz prematuramente y el segundo dato con mayor número de casos de partos prematuros es veintiún (21) años, cuántos partos de madres gestantes, dentro de una población de doscientos (200) serán de veintiún años o menos. Esta relación nos dio un estimado de 54 embarazos prematuros con un score del 83%. 
- Es menester y consideración del hospital incluir o depurar los datos que considere necesarios para completar o depurar esta base de datos.
- Esta información es vital para el hospital pues de esta y su correcta manipulación y análisis pueden surgir diferentes propuestas para solucionar problemáticas y mejorar la toma de decisiones médicas, administrativas y de salubridad. Sin embargo, aunque el alcance de los datos y sus correlaciones sean meramente especulativas, también se corre un riesgo a la hora de decidir ampliar el rango de la información a suministrar, entre ellos el tiempo computacional de procesamiento, dificultades en la homologación de la información, tratamiento de datos personales, entre otros; esta decisión final debe tomarla el Hospital como organismo emisor de los mismos.
- Es importante reconocer la relevancia de esta clase de estudios, cuyo verdadero alcance final no podrá ser totalmente calculado pues esta clase de estudios pueden tener una repercusión considerable en el municipio.


### Referencias 

<div align="center">
    <img src="https://raw.githubusercontent.com/justoneye/NacidosVivos-HospitalManuelUribeAngel/master/PPT/Diapositiva39.JPG" alt="Referencias" width="100%"/>
</div>
