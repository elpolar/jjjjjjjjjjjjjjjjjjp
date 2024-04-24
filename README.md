Cuando te conectes al servidor de ubuntu, lo primero que tienes que hacer es ejecutar el siguiente comando:
**`cd /home/ubuntu`**
Cuando ya estes en esa direccion se veria asi:
![enter image description here](https://i.postimg.cc/0jCxzbvJ/screenshot-828.png)

Cuando estes ahi vas a escribir:
**`screen > ENTER`**
te va a salir como un texto como este:
![enter image description here](https://i.postimg.cc/t4JygqMY/screenshot-829.png)

Presionas **`ENTER`** denuevo
la consola se quedara en negro dentro del directorio donde estabas entonces.
para ejecutar los bots necesarios que necesitas para usar "flexigateway" **tienes que encender 2 bots,  de python y otro de nodeJS.**

 - ***Refrescador de sesiones de flexigateway***: Este bot se encarga de
   refrescar la sesion del sitio web para que funcione el CAMBIO DE
   NUMERO. antes de realizar cualquier llamada.

Para ejecutar este bot tienes que ejecutar este comando:
**`python3 rama.py`**
asi se vera:
![enter image description here](https://i.postimg.cc/KvgDhBZz/screenshot-830.png)

 - ***Liberador de cola de llamadas***: Este bot se encarga de sacar las personas que estan en lista de espera de llamada mejor dicho queue. Entonces, tienes que abrir una sesion nueva del VPS. haciendo esto:
 - ![enter image description here](https://i.postimg.cc/pyN8Lc2d/screenshot-831.png)
   
Click derecho ahi y despues duplicar sesion. De esa manera vuelves a inciar sesion dentro del vps. Vuelves a ejecutar el comando:
**`cd /home/ubuntu`**
Y despues denuevo:
**`screen > ENTER`**
y ahora vas a escribir el comando:
**`node hola2.js`**


Ejecutar bot de telegram:
-
Lo que tienes que hacer es hacer login en el vps. denuevo ejecutas el comando:
**`cd /home/ubuntu`**
Y ahi denuevo:
**`screen > ENTER`**
y ahora vas a ejecutar el comando:
**`python3 telebotx.py`**

Ya con eso el bot de telegram estaria corriendo
