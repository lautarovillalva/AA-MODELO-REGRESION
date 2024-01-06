Resultados Aprender 2016 y 2017
Detalle de los resultados Aprender por partido y materia.

Datos Abiertos PBA/Dataset/Recurso/Resultados Aprender 2016 y 2017


Objetivo de las Evaluaciones Aprender :

Proporcionar información sobre el nivel de conocimiento y habilidades de los estudiantes en relación a estos estándares educativos.

Contexto: 

La Evaluación Nacional Aprender, permite conocer los logros de aprendizaje de las y los estudiantes de nivel primario y secundario de todo el país en las áreas de conocimiento escolares: Lengua, Matemática, Ciencias Naturales y Ciencias Sociales. También, brindar información de contexto de los estudiantes, directivos y docentes.

Aprender se realiza desde el año 2016 en adelante, es una prueba estandarizada. Esto significa que se aplican los mismos instrumentos a todos/as los/as estudiantes del mismo grado o año, en las mismas condiciones, para luego valorar los resultados con los mismos criterios. Este tipo de evaluación se realiza de acuerdo con normas que garantizan la homogeneidad del proceso evaluativo y de los resultados obtenidos.

El sistema de evaluación Aprender utiliza la Teoría de Respuesta al Ítem (TRI) para medir el desempeño de los estudiantes en relación a un conjunto de conocimientos y habilidades previamente definidos, que incluyen los Núcleos de Aprendizaje Prioritarios y los diseños curriculares jurisdiccionales.
Para administrar las pruebas, se utilizan 72 ítems diferentes en cada año y disciplina. Dado que sería difícil para un estudiante responder a todos estos ítems, se construyen 6 modelos de cuestionarios, cada uno con 24 ítems, algunos de los cuales se superponen entre los modelos.

Los puntajes obtenidos en las pruebas Aprender se encuentran en una escala TRI que es arbitraria, con un valor medio de 500 y un desvío estándar de 100. Esto significa que los puntajes TRI por sí mismos no indican cuántas respuestas correctas un estudiante ha dado o su nivel de habilidad. En cambio, la interpretación de los puntajes se realiza en términos de niveles de desempeño. En el caso de Aprender, se utilizan cuatro niveles de desempeño: por debajo del básico, básico, satisfactorio y avanzado. Estos niveles se determinan mediante el Método Bookmark, que implica la participación de docentes seleccionados aleatoriamente de diferentes jurisdicciones y sectores de gestión. Estos docentes, en los Talleres Bookmark, definen los puntos de corte y describen cada uno de los niveles de desempeño para cada disciplina y año evaluado.

Problema: 
A Partir de los datos que proporcionan los resultados de Aprender hay varias preguntas de investigación y problemas que podrían abordarse.

* Predicción del desempeño académico futuro: Desarrollar un modelo predictivo que utiliza datos porcentuales para predecir el nivel de desempeño(“porcentaje”) futuro de los estudiantes en diferentes municipios y materias para cada tipo de resultado (“básico”, “avanzado”, “satisfactorio”, “por debajo del nivel básico”).Esto podría ayudar en la planificación y asignación de recursos. Además, se analizará los datos para dar respuesta a las siguientes problemáticas: 
  * Evaluación del desempeño educativo por municipio y materia, al analizar y comparar el nivel de desempeño de los alumnos en diferentes municipios y materias, se podría ayudar a identificar áreas de mejora en el sistema educativo de diferentes regiones como también identificar zonas que necesiten recursos y programas educativos hacia esas áreas.
  * Tendencias en el desempeño a lo largo del tiempo, investigando cómo fue evolucionando el desempeño de los estudiantes en diferentes materias a lo largo de los años. ¿Hay mejoras o empeoramientos en el desempeño académico?
  * Variaciones en el desempeño por área de conocimiento, analizar si existen áreas de conocimiento específicas en las que los estudiantes tienden a tener un mejor o peor desempeño en diferentes municipios. Esto podría ayudar a adaptar los planes de estudio para aquellas áreas que lo requieran.


Variable Objetivo: "porcentaje"

La columna “porcentaje” representa la distribución de los respondientes para cada clase de la columna “resultado” de cada “materia” en cada partido en los años 2016 y 2017.

Se analizará la variable objetivo de la siguiente forma para dar respuesta a las problemáticas planteadas: 


Descripción del dataset desde la fuente:


Descripción del dataset utilizando Python:
* El dataset cuenta con:
* Columnas: 7 (“nombre_partido”, “id_partido”, “año”, “materia”, “respondientes”, “resultado” y “porcentaje”)
* Filas: 3264
* La columna “id_partido” posee valores nulos.


Transformaciones
* Eliminar "id_partido”: Es una columna que hace referencia a “nombre_partido”. Se considera redundante y además posee valores nulos.
* Transformar la columna "porcentaje" a float: El dataset tiene el punto decimal con “,” y Python no interpreta esa columna como float. Se deberá reemplazar la coma por el punto y cambiar el tipo de dato.
* Unificar valores de la columna "resultado". Existen valores de la columna “resultado” que se encuentran en mayúscula y otros en minúscula (Ejemplo: ‘avanzado’ y ‘Avanzado’).



Fuentes: 
* Documento metodológico Aprender
* Resultados Aprender 2016 y 2017
