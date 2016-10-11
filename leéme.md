# Alternar-Conexiones
Alterna tus conexiones en Windows, cuando una conexión se cae, deshabilita y cambia a la próxima conexión


# ¿Qué es lo que hace este programa?
El programa cada 1 minuto chequeará si tenemos conexión consultando la página google.com, si tiene respuesta esperará un minuto más, y así sucesivamente hasta que no tenga respuesta, o sea hasta que detecte que se nos cae la conexión, una vez no haya conexión deshabilitará la conexión llamada "LAN" y habilitará la conexión llamada "BAM", luego de pasar 1 hora revisará si ya llegó la conexión "LAN", sino ha llegado volverá a usar la conexión BAM, y volverá a probar en una hora, así sucesivamente hasta que por fin nos llegue la conexión LAN, y si se vuelve a caer repite el ciclo.

# ¿Cómo usarlo?

Usarlo es muy simple, solo debes dirigirte a conexiones de red y editar el nombre de tus conexiones.
Para ir a conexiones de red puedes escribir en el buscador de Windows "Conexiones de red", o puedes simplemente presionar Inicio + R, luego que se abra el recuadro ejecutar pegar ahí lo siguiente: ncpa.cpl y dar click en aceptar.

Una vez se encuentren entre sus conexiones renombren su conexión principal como "LAN", y su conexión de respaldo como "BAM", y listo, solo tendrán que ejecutar el programa, dejarlo abierto y el hará el resto.


Quien quiera donar algo, puedo hacerlo a mi dirección de bitcoins:

1MbU7QfJn9iZMoJCSuZtKCyQdn13sqSLAM
