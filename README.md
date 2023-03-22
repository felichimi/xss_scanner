# xss_scanner

Este script hecho en Python escanea un sitio web en busca de XSS y guarda la información en un archivo de texto. El script se ejecuta de manera recursiva en todos los links del mismo dominio y utiliza múltiples hilos para agilizar el proceso.

------------------------------------

Dependencias

> pip install requests

> pip install beautifulsoup4

------------------------------------

Uso

> python xss_scanner.py [url] [-t threads] [-c cookie]

url: La URL del sitio web que desea escanear.

threads (Opcional): La cantidad de hilos que se utilizarán. El valor default es 1.

cookie (Opcional): La cookie que se utilizará para los requests.



------------------------------------
TO DO LIST
* opcion de pasarle una lista de payloads
* codigo mas modular
* mejor gestion de errores
* mejorar la salida del codigo
------------------------------------
