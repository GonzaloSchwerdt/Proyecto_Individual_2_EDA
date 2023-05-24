# Proyecto_Individual_2_EDA

Buenas! Soy Gonzalo Schwerdt de la Cohorte 10 de SoyHenry de la carrera DataScience.  

Mi proyecto se basa en el análisis exploratorio de los datos relacionados tanto a tiempos de suceso de los accidentes, mortalidad de los mismos, como de las causas que los originaron.  

Durante la normalización de los datos me di cuenta que la columna "summary" tenía una gran utilidad para determinar la causa de cada uno de los accidentes.   Revisé las webs complementarias pero no definían específicamente la causalidad del siniestro, las mismas eran muy generales. Asi que opté por utilizar aplicar tokens a las oraciones y filtrar las palabras claves presentes en dichos resúmenes, para luego clasificarlas en estas columnas: "desconocido	errores_humanos	fallas_gestion_trafico	fallos_equipos	problemas_disenio	problemas_fabricacion	problemas_mantenimiento	problemas_meteorologicos". Dando como resultado datos muy específicos de los cuales el proyecto se ve con la necesidad, para así poder responder preguntas pertinentes a la prevención de estos hechos aéreos.  
A su vez creé tres nuevas columnas/variables donde clasifica los hechos en mañana, tarde y noche, para verificar si había alguna implicación en los distintos horarios del día; como a su vez si alguno de los tres tendía a tener una mortalidad mas alta que los demás.

# Descripción de Archivos

AccidentesAvionesTRANSFORMED.csv : Es el data set original normalizado.  
AccidentesAvionesFIN.csv : Es una copia de AccidentesAvionesTRANSFORMED, solo que filtra las columnas innecesarias.  
Analisis.pbix : Es el análisis de los datos con Power BI.  
EDA.ipynb: Es el Jupyer Notebook con el Análisis Exploratorio de los datos.
