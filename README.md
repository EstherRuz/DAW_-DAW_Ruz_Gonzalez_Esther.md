# DAW_-DAW_Ruz_Gonzalez_Esther.md
1. Explique con sus palabras que es una petición GET, POST, PUT y DELETE,
remarcando sus diferencias.

GET: los datos que se envian al servidor se escriven en la url, por lo que estan visibles.

POST: los datos que se envian al servidor se encuentran en la solicitud HTTP, no quedan visibles para el usuario.

PUT: crea un nuevo elemento o lo reemplaza.

DELETE: borra un recurso en específico.


2. Cambie del puerto 80 al puerto 4444 el servidor apache2. Muestra desde el navegador
su funcionamiento adjuntando una captura de pantalla.

![Alt text](/abc.png)

3. Explica como activar, desactivar, reiniciar y recargar un servidor de Apache2
explicando la diferencia entre cada uno de los comandos utilizados.

Activar:sudo systemctl start apache2

Desactivar: sudo systemctl stop apache2

Reiniciar: sudo systemctl restart apache2

Recargar: sudo systemctl reload apache2

4. ¿Dónde se encuentran los ficheros de configuración de Apache2?
/etc/apache2

5. ¿Dónde se encuentran los ficheros de ejecución de Apache2?
/etc/httpd/conf/httpd. conf

6. ¿Dónde se encuentran los ficheros de monitorización de Apache2?
/etc/httpd/conf/httpd. conf

7. ¿Qué es un Firewall? ¿Para que funciona? ¿Por qué es necesario?
Es un programa que controla el acceso a la red de un ordenador.

8. Explica con tus palabras las diferentes partes de una URL.

Protocolo: http o https.

Host: identifica el servidor.

Puerto: inica el puerto que se utilizara para acceder al recurso, 443 o 80.

Ruta: localización del recurso en el servidor.

Consulta: permite pasar parametros.

9. Explica el funcionamiento del protocolo HTTP.

Es un protocolo de tipio cliente servidor, el cliente pregunta y el servidor reponde.
