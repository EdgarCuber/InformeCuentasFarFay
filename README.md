# InformeCuentasFarFay
FarFay
Proyecto 1 - INFORME DE CUENTAS AUTOMATIZADO
Inicio de proyecto 17/01/2022
Descripción general del proyecto: 
Script para Google Sheets utilizando Apps Script de Google (parecido a JavaScript) que recolecta y fusiona las bases de datos de cuentas de los operadores en un archivo en una sola base de datos para su posterior análisis haciendo uso de ingeniería de datos para Business Intelligence y posterior envió automático a las 23:00 horas por medio de correo a los directivos.
Objetivo:
Conocer y contrastar el verdadero trabajo de los operadores un día después, así como la microsegmentación de cuentas y conocimiento de los activos por parte de los supervisores, enlaces y directivos.
Requerimientos indispensables:
•	Conocimiento de JavaScript preferente Apps Script Google.
•	Conocimientos básicos-intermedios lenguajes de consulta SQL preferente “Query” lenguaje de Google.
•	Conocimiento intermedio de Estadística y probabilidad.
•	Generación de Tablas dinámicas o su modificación.
•	Conocimiento de Google Sheets  (Avanzado preferentemente).
•	Uso de fórmulas y funciones (Avanzado Preferentemente).
•	Expresiones regulares (Indispensable).
Funcionamiento – Implementación
Desde la Interface IDE de AppScript se hace una llamada a la función main que ejecuta a su vez las funciones GetCounts CDMX y Cancún que obtienen los valores de las bases de datos individuales de cuentas de los operadores con un id único y las junta en un libro de análisis para su posterior auditoria automatizada y muestreo en un dashboard armado con tablas dinámicas que obtienen la información mediante Query avanzados a las bases de datos de cuentas compiladas, posteriormente el script de manera automática y programada envía en reporte en PDF a los correos especificados en el código.
