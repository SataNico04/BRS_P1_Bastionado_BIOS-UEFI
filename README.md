# Bastionado BIOS/UEFI

El bastionado de la BIOS/UEFI es el proceso de asegurar la configuración inicial de un ordenador para prevenir accesos no autorizados. 
Dado que la BIOS/UEFI controla el hardware antes de que arranque el sistema operativo, es un punto crítico de seguridad. 
Bastionarla implica protegerla con contraseñas, habilitar funciones como el arranque seguro (Secure Boot) y desactivar dispositivos innecesarios. 
Esto reduce el riesgo de ataques que intentan comprometer el sistema desde sus niveles más bajos, garantizando un entorno más seguro desde el inicio.

En esta primera parte de la práctica, vamos gestionar una BIOS emulada para hacerla lo más segura posible. En este caso estoy usando la BIOS de un 
portátil lenovo:

![IMAGEN_BIOS](exp_bios.png)

Esto es lo que veremos si entramos correctamente en la BIOS de nuestro sistema(puede variar con cada equipo, pero son bastante parecidos)

![PESTAÑAS_BIOS](herramientas.png)
En esta primera imagen, veremos las pestañas a las que podemos acceder para configurarlas.

![INFORMACION_BIOS](informacion.png)
En la parte central, podremos ver información u opcciones a configurar, en este caso vemos información de las BIOS con la versión, la fecha, etc; números de serie, mac, velocidad de la CPU...

![COMANDOS_BIOS](comandos.png)
Y en la parte inferior, tenemos los atajos de teclado que podremos usar en cada momento con su descripción.

Una vez visto lo *principal* de la BIOS, vamos a pasar ahora a la configuración en busca de hacerla más segura.
