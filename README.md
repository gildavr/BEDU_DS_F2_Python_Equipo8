# CoDi (Cobro Digital) - Banco de México
## Procesamiento de Datos con Python 2023

### Proyecto Equipo 8
Proyecto final del módulo de Procesamiento de datos con Python Santander 2022 de la Fase 2 del programa de Data Science.



Integrantes del Equipo
- Gilda Villaseñor Ramírez
- Karen Grethel Sánchez Mijangos
- Rocío Velasco Flores
- César Palafox Vázquez
- Edgar Daniel Paulin Noriega

## Resumen ejecutivo

En septiembre de 2019 Banco de México y la Asociación de Bancos de México pusieron en marcha la plataforma CoDi que permite hacer transferencias electrónicas de manera eficiente, segura y en tiempo real mediante dispositivos móviles. Los objetivos principales de esta plataforma son:

- Avanzar hacia la inclusión financiera y la bancarización de los mexicanos
- Facilitar las transferencias electrónicas entre comercios y clientes 
- Disminuir el uso de dinero en efectivo

CoDi funciona a través de teléfonos móviles, en un esquema 24x7 y sin ningún costo. CoDi opera sobre la infraestructura del sistema SPEI (Sistema de Pagos Electrónicos Interbancarios) del mismo Banco de México.

Nos llama la atención que la adopción de este sistema no ha sido la esperada. Por ello exploramos los datos operativos de Banco de México para entender cuál es la situación del sistema CoDi (2019 – 2022). Nos interesa saber por qué, a pesar de los beneficios que ofrece CoDi, no es adoptado masivamente. Para poder generar ideas de qué hacer para que CoDi sea usado por un mayor número de comercios y clientes,  buscamos encontrar en los datos disponibles las causas de no alcanzar la adopción esperada.

En la investigación encontramos una solución en Brasil llamada Pix, ésta es un esfuerzo del Banco Central de Brasil para fomentar la inclusión financiera y la adopción de pagos digitales en América Latina. Al igual que CoDi, a través de Pix se pueden hacer transferencias de pagos electrónicos instantáneas de persona a persona, a un comercio o institución financiera y de gobierno en Brasil. El sistema Pix fue utilizado por 100 veces más personas y comercios a comparación de CoDi; mientras que el monto total transaccionado a través del sistema brasileño es 4,000 veces mayor que los recursos que transitaron a través de la plataforma mexicana; por último, CoDi ha sido utilizado al menos una vez por 0.97% de la población mexicana, mientras que Pix lo ha usado 47% de la población brasileña.
 
Este proyecto es el esfuerzo de la exploración de los datos públicos que Banco de México proporciona en su sitio web. Con ellos pudimos conocer estadísticas del uso de la plataforma CoDi. Para tratar de encontrar posibles causas de la baja adopción del sistema es necesario realizar una búsqueda exhaustiva de datos, o bien, tratar de generar los mismo por medio de encuestas, lo cual queda fuera del alcance del proyecto y se podría desarrollar en un futuro.

El desarrollo de este proyecto se base en el planteamiento de las siguientes preguntas a las cuales hemos dado respuesta con la exploración de los datos:
- ¿Cuáles son las entidades financieras con mayor y menor número de cuentas validadas?
- ¿Cuál es la proporción de cuentas registradas que han realizado al menos un cobro o un pago mediante CoDi?
- ¿Cuál ha sido el promedio por año de las cuentas que han realizado al menos un cobro  y un pago mediante CoDi?
- ¿Cuál es el número promedio de transacciones realizadas por año?
- ¿Cuáles son las entidades financieras con el mayor número de cuentas enviadas y recibidas?  
- ¿Cuál ha sido el monto promedio por año realizado mediante CoDi? 
- ¿Cuál es el porcentaje de dispositivos Android y iOS registrados en CoDi? 
- ¿Cuáles han sido las medidas de tendencia central, los valores máximos y mínimos y los cuartiles para transacciones diarias de al menos un pago y transacciones diarias de al menos un cobro?

El conjunto de datos explorados se puede consultar en el [repositorio de Datasets](https://github.com/gildavr/BEDU_DS_F2_Python_Equipo8/tree/main/Datasets). Las respuestas arrojadas a partir de la exploración de los datos se encuentran en el [Jupyter Notebook del proyecto](https://github.com/gildavr/BEDU_DS_F2_Python_Equipo8/blob/main/Limpieza_de_datos.ipynb).

En el documento [Equipo8_Proyecto_Procesamiento_Datos_Python.docx](https://docs.google.com/document/d/1PoAE28sfDpxFI65ElKtBh4O_AW-XXmqS/edit?usp=share_link&ouid=114296856759997128418&rtpof=true&sd=true) se encuentra el desarrollo del proyecto, desde el planteamiento del problema, soluciones similares, cuestionamientos planteados, razonamientos para la exploración de datos, obtención, limpieza y transformación de los datos.

En conclusión, creemos que en comparación con otras soluciones similares podemos afirmar que CoDi tiene un gran potencial de crecimiento en México. Este proyecto solo expone el uso que ha tenido desde que inició. Puede tomarse como punto de partida para generar interés sobre causas de baja adopción de CoDi y generación de estrategias de promoción y educación para incentivar el uso de servicios financieros como CoDi. 


### Documento y archivos del proyecto
- Repositorio del proyecto [https://github.com/gildavr/BEDU_DS_F2_Python_Equipo8.git](https://github.com/gildavr/BEDU_DS_F2_Python_Equipo8.git)
- Desarrollo del proyecto [Equipo8_Proyecto_Procesamiento_Datos_Python.docx](https://docs.google.com/document/d/1PoAE28sfDpxFI65ElKtBh4O_AW-XXmqS/edit?usp=share_link&ouid=114296856759997128418&rtpof=true&sd=true)
- Datasets [folder de Datasets en Repositorio](https://github.com/gildavr/BEDU_DS_F2_Python_Equipo8/tree/main/Datasets)
- Jupyter Notebook del proyecto. Incluye exploración inicial de datasets, limpieza de datos y resolución de preguntas planteadas. [Jupyter Notebook del proyecto en el repositorio](https://github.com/gildavr/BEDU_DS_F2_Python_Equipo8/blob/main/Limpieza_de_datos.ipynb)
- Jupyter Notebook de Exploración de datos extraídos a través del API del Sistema de Información Económica (SIE) de Banco de México. [Jupyter Notebook de exploración de API en el repositorio](https://github.com/gildavr/BEDU_DS_F2_Python_Equipo8/blob/main/APIBanxico.ipynb)

### Instrucciones de uso del proyecto
- Consultar el Desarrollo del proyecto [Equipo8_Proyecto_Procesamiento_Datos_Python.docx](https://docs.google.com/document/d/1PoAE28sfDpxFI65ElKtBh4O_AW-XXmqS/edit?usp=share_link&ouid=114296856759997128418&rtpof=true&sd=true)
- Para ver los archivos del proyector acceder al Repositorio del proyecto [https://github.com/gildavr/BEDU_DS_F2_Python_Equipo8.git](https://github.com/gildavr/BEDU_DS_F2_Python_Equipo8.git)
- Para correr los Notebooks del proyecto, clonar el Repositorio del proyecto [https://github.com/gildavr/BEDU_DS_F2_Python_Equipo8.git](https://github.com/gildavr/BEDU_DS_F2_Python_Equipo8.git) Este tiene los notebooks y los datasets requeridos. 

