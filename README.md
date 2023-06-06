# Presupuesto-Abierto-API-de-Consulta-de-Datos-
Código Python consulta a las cuatro tablas de Presupuesto Abierto Argentina




API de Consulta de Datos - Código y Guía de Uso
Este repositorio contiene código en Python que permite la consulta a los cuatro endpoints de la página de Presupuesto Abierto de Argentina (https://www.presupuestoabierto.gob.ar/sici/home) a través de una API y guardar los resultados en archivos CSV. El código utiliza las siguientes bibliotecas:

•	requests: Permite enviar solicitudes HTTP y obtener respuestas de servidores web. Se utiliza para realizar solicitudes a la API y obtener los datos en formato CSV.

•	json: Proporciona funciones para trabajar con datos en formato JSON. Se utiliza para codificar los datos de la solicitud en formato JSON.

•	pandas: Una biblioteca ampliamente utilizada para el análisis de datos en Python. Proporciona estructuras de datos flexibles y eficientes, así como herramientas para manipular y analizar datos. Se utiliza para convertir los datos CSV en una tabla y realizar operaciones de análisis de datos.

•	io: Proporciona herramientas para trabajar con flujos de entrada/salida (I/O). Se utiliza para convertir la cadena CSV en un objeto de archivo que pandas pueda leer.

•	tabulate: Se utiliza para visualizar los datos como si fueran una tabla de Excel, combinado con la biblioteca pandas.

Cómo utilizar el código
1.	Asegúrate de tener Python instalado en tu sistema.
2.	Clona este repositorio o descarga los archivos del código en tu máquina.
3.	Instala las bibliotecas requeridas ejecutando el siguiente comando en tu entorno virtual o terminal.
4.	Abre el archivo consulta_api.py en tu editor de código preferido.
5.	Reemplaza el valor de la variable token con tu token de autorización, que puedes obtener en Presupuesto Abierto (https://www.presupuestoabierto.gob.ar/sici/api-pac).
6.	Ejecuta el código.
7.	Los resultados de la consulta se imprimirán en la consola y los podras guardar  en archivos CSV en el mismo directorio. Los nombres de los archivos CSV corresponden a los diferentes conjuntos de datos consultados: credito.csv, recurso.csv, pef.csv y transversal_financiero.csv.

Configuración de la consulta
El código está preconfigurado para realizar las siguientes consultas:
•	Tabla "Credito": Consulta datos relacionados con los créditos presupuestarios.

•	Tabla "Recurso": Consulta datos relacionados con los recursos financieros.

•	Tabla "Programación y Ejecución Fisica": Consulta datos sobre la programación y ejecución física.

•	Tabla "Transversal Financiero": Consulta datos transversales financieros.

Puedes personalizar la configuración modificando las variables correspondientes en el archivo ‘consulta_api.py’. Asegúrate de proporcionar los valores correctos para las URL de la API y los parámetros de consulta según tus necesidades. Se adjunta archivo Excel "API - Presupuesto Abierto" donde se encuentran las descripciones de todas las columnas y las relaciones existentes entre los endpoints.

Contribución
Si deseas contribuir a este proyecto, siéntete libre de hacerlo enviando solicitudes de extracción. También puedes informar problemas o sugerir mejoras mediante la función de "Issues" en este repositorio.

¡Espero que este código te sea útil para consultar datos a través de la API y trabajar con ellos de manera eficiente!
