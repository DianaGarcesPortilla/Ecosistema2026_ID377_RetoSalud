
# Aplicación de Modelos de Machine Learning para predecir el nivel de peligro de muerte por Violencia Intrafamiliar y de Pareja 

Problema abordado

La violencia intrafamiliar y de pareja es un evento de interés en salud pública para Colombia. 
En lo corrido del año, a julio de 2026, según el Instituto Nacional de Salud-INS, se han presentado 83045 casos
de violencia de esta naturaleza, donde la violencia física representa el 47.55% (39488 casos).

De los casos de violencia física que registra el INS no todos se denuncian a una autoridad competente 
(fiscalía, policía o comisaría), por lo tanto, según históricos 2014-2025 del 
Instituto Nacional de Medicina Legal y Ciencias Forenses -INMLCF, se han presentado 236840 casos de violencia intrafamiliar-VIF,
438786 casos de violencia de pareja-VP y 3010 casos de homicidios VIF.

En el contexto Colombiano, actualmente se registran y se visualizan estadísticas sobre la violencia VIF y VP (INS y INMLCF), 
pero no se evidencia la aplicación de modelos de aprendizaje computacional para predecir este evento (Muñoz et al., 2023),
que permitan alertar a una persona víctima de violencia previa de VIF y VP sobre su nivel de peligro de muerte, y conectarlas c
on autoridades como la policía y mecanismos de ayuda, como las líneas de atención especializadas para este tipo de violencia, 
para que actúen en consecuencia y en el tiempo requerido al nivel de peligro.

Por lo tanto, el objetivo de este proyecto es aplicar modelos de Machine Learning (Regresión logística, Random Forest, Maquina de vectores) 
para predecir el nivel de peligro de muerte por Violencia Intrafamiliar y de Pareja. ​ 


Bases de datos utilizadas

Se utilizaron las bases de datos abiertos (1 al 3) y la base derivada (4):

1.Violencia intrafamiliar. Colombia, años 2015 a 2024 (35
variables –236840 casos)

2. Lesiones por violencia de pareja. Colombia, años 2015
a 2024 (35 variables –438786 casos).

3. Presuntos homicidios. Colombia, años 2015 a 2024 (32
variables –125284​ casos)

4. Base derivada que proviene de la unión entre las bases de VIF y VP por causas no fatales 2014-2025
con la base de lesiones por causas fatales 2014-abril 2026, para dejar exclusivamente la intersección con homicidios VIF-VF y 
otros tipos de homicidios, y filtrar 101 casos de interés. (71 variables – 225 registros. Entregada por INMLCF.
  
En la carpeta recursos en el archivo presentación se detalla todo el proceso tratamiento y análisis de datos, la aplicación de los modelos de machine learning,
la selección del mejor modelo de predicción y los resultados. En esta misma carpeta, en el demo se explica todo el proceso de construcción del proyecto 
de machine learning, organizado según metodología del ciclo de vida de minería de datos CRISP-DM, y aplicado en la Plataforma Databricks.  



