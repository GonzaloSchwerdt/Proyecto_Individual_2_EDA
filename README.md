# Proyecto_Individual_2_EDA

Buenas! Soy Gonzalo Schwerdt de la Cohorte 10 de SoyHenry de la carrera DataScience.  

Mi proyecto se basa en el análisis exploratorio de los datos relacionados tanto a tiempos de suceso de los accidentes, mortalidad de los mismos, como de las causas que los originaron.  

Durante la normalización de los datos me di cuenta que la columna "summary" tenía una gran utildiad para determinar la causa de cada uno de los accidentes.   Revisé las webs complementarias pero no definian específicamente la causalidad del siniestro, las mismas eran muy generales. Asi que opté por tokenizar y filtrar las palabras claves presentes en dichos resúmenes, para luego clasificarlas en estas columnas: "desconocido	errores_humanos	fallas_gestion_trafico	fallos_equipos	problemas_disenio	problemas_fabricacion	problemas_mantenimiento	problemas_meteorologicos". Dando como resultado datos muy específicos de los cuales el proyecto se ve con la necesidad para poder responder preguntas pertinentes a la prevención de estos hechos aéreos.
