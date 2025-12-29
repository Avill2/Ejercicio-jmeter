# Ejercicio-jmeter
Prueba de carga de servicio login a la direccion https://fakestoreapi.com/auth/login

Herramienta utilizada
Apache Jmeter 5.6.3
Java JDK 17

Descripcion
En la herramienta ApAache Jmeter contiene una prueba de carga sobre el servicio de autenticacion de la pagina https://fakestoreapi.com, con usuarios parametrizados en un archivo CSV.

Estructura del proyecto
Login_test_jmx--> script de Jmeter
users.csv--> archivo de los usuarios
readme.txt--> instruccion de ejecucion
conclusiones.txt--> resultados y recomendaciones

Pasos para ejecutar la prueba
1.- Instalar JAVA JDK 17 o superior
2.- Descargar la herramienta Apache Jmeter 5.6.3
3.- Abrir Jmeter ejecutando jmeter.bat
4.- Abrir el archivo login_test.jmx
5.- Verificar la ruta del archivo users.cvs en el "CSV Data Set Config"
6.- Agregar los listener al THREAD GROUP (View Results Tree, Summary Report, Aggregate Report)
7.- Presionar el boton start
8.- Dejar la prueba ejecutarse durante un minuto y pararlo.
9.- revisar los resultados en Summary Report y Agregate Report

Escenario de prueba
- 20 usuarios virutales
- 20 transacciones por segundo (TPS)
- tiempo maximo permitido 1.5s-> (1500 ms)
- tasa de erro aceptable menor que al 3%


