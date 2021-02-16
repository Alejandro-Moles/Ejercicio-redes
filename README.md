# Ejercicio-redes
Lo primero que hice al empezar el ejercicio fue inventarme las 5 redes, que fueron  **1º: 192.168.1.0, 2º 192.14.2.0, 3º 192.50.1.0, 4º 192.160.1.0 y 5º 192.80.1.0**

Después de esto, empece a realizar el primer ejercicio en el que se me pedia que sacara 3 subredes de la primera red con 100 host 30 host y 6 host respectivamenete.
Para ello hice uso de la fórmula que hemos visto en clase **2^m - 2 >= Nº Host** por lo que me salían diferentes subredes que he utilizado, luego he conectado todas esas subredes con un router pero no lo he configurado, ya que no pidían salir fuera. He remarcado la zona de ese ejercicio con un rectángulo verde.

El siguiente ejercicio me pedía 8 ordenadores con DHCP, así que configuré un servidor DHCP para que diese las direcciones ip, la mascara de red y la default Gateway a los 8 ordenadores. Luego he configurado un router para que se puedieran conectar entre si y mas adelante lo he configurado para que se puedieran conectar los routers entre si.
Para ello he inventado una nueva direccion ip **192.15.0.0** para conectar los routers entre si. He marcado la zona de este ejercicio con un tono rosa pastel.

Para el tercer ejercicio se me pedía 4 ordenadores con DHCP, así que el proceso fue igual que en el ejercicio anterior pero con menos ordenadores y con una red diferente.
En el router que he usado para conectar los ordenadores de este ejercicio, he routeado las redes **192.15.0.0**, la red que he inventado para conectar el router del ejercicio anterior y este, **192.20.0.0**, la red que utilizaré para conectar el router del proximo ejercicio  y la red de este ejercicio **192.50.1.0**. He remarcado la zona donde he hecho el ejercicio con un color amarillo pastel.

El siguiente ejercicio me pedía 4 ordenadores con IP fija, un punto de acceso con 5 ordenadores con DHCP. Para este he utilizado la 4º red, primero creé un servidor DHCP, y lo configuré para que diese las direcciones ip, la mascara y la default gateway, más tarde lo conecté con un punto de acceso que a su vez conectaba con 5 portátiles. Luego configure 4 ordenadores a mano para que tubiesen ip fija. Por ultimo conecte todo a un switch que a su vez lo concete a un router. Configuré el router para que conectase a las redes del ejercicio anterior y al de los siguientes, utilice las direcciones ip inventadas para conectar los routers entre si **192.20.0.0**, **192.30.1.0**, **192.80.1.0** y **192.160.1.0**, que era la red del ejercicio en si. He remarcado la zona del ejercicio con un color celeste.


