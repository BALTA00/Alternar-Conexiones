# Alternar-Conexiones
Alterna tus conexiones en Windows, cuando una conexión se cae, deshabilita y cambia a la próxima conexión


# ¿Qué es lo que hace este programa?
El programa cada 1 minuto chequeará si tenemos conexión consultando la página google.com, si tiene respuesta esperará un minuto más, y así sucesivamente hasta que no tenga respuesta, o sea hasta que detecte que se nos cae la conexión, una vez no haya conexión deshabilitará la conexión llamada "LAN" y habilitará la conexión llamada "BAM", luego de pasar 1 hora revisará si ya llegó la conexión "LAN", sino ha llegado volverá a usar la conexión BAM, y volverá a probar en una hora, así sucesivamente hasta que por fin nos llegue la conexión LAN, y si se vuelve a caer repite el ciclo.
