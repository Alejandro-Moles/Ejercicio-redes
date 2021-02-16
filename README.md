# Ejercicio-redes
Lo primero que hice al empezar el ejercicio fue inventarme las 5 redes, que fueron  **1º: 192.168.1.0, 2º 192.14.2.0, 3º 192.50.1.0, 4º 192.160.1.0 y 5º 192.80.1.0**

Después de esto, empece a realizar el primer ejercicio en el que se me pedia que sacara 3 subredes de la primera red con 100 host 30 host y 6 host respectivamenete.
Para ello hice uso de la fórmula que hemos visto en clase **2^m - 2 >= Nº Host** por lo que me salían diferentes subredes que he utilizado, luego he conectado todas esas subredes con un router pero no lo he configurado, ya que no pidían salir fuera. He remarcado la zona de ese ejercicio con un rectángulo verde.

El siguiente ejercicio me pedía 8 ordenadores con DHCP, así que configuré un servidor DHCP para que diese las direcciones ip, la mascara de red y la default Gateway a los 8 ordenadores. Luego he configurado un router para que se puedieran conectar entre si y mas adelante lo he configurado para que se puedieran conectar los routers entre si.
Para ello he inventado una nueva direccion ip **192.15.0.0** para conectar los routers entre si. He marcado la zona de este ejercicio con un tono rosa pastel.

Para el tercer ejercicio se me pedía 4 ordenadores con DHCP, así que el proceso fue igual que en el ejercicio anterior pero con menos ordenadores y con una red diferente.
En el router que he usado para conectar los ordenadores de este ejercicio, he routeado las redes **192.15.0.0**, la red que he inventado para conectar el router del ejercicio anterior y este, **192.20.0.0**, la red que utilizaré para conectar el router del proximo ejercicio  y la red de este ejercicio **192.50.1.0**. He remarcado la zona donde he hecho el ejercicio con un color amarillo pastel.

El siguiente ejercicio me pedía 4 ordenadores con IP fija, un punto de acceso con 5 ordenadores con DHCP. Para este he utilizado la 4º red, primero creé un servidor DHCP, y lo configuré para que diese las direcciones ip, la mascara y la default gateway, más tarde lo conecté con un punto de acceso que a su vez conectaba con 5 portátiles. Luego configure 4 ordenadores a mano para que tubiesen ip fija. Por ultimo conecte todo a un switch que a su vez lo concete a un router. Configuré el router para que conectase a las redes del ejercicio anterior y al de los siguientes, utilice las direcciones ip inventadas para conectar los routers entre si **192.20.0.0**, **192.30.1.0**, y las redes que ya estaban creadas **192.80.1.0**, que es la del proximo ejercicio y **192.160.1.0**, que era la red del ejercicio en si. He remarcado la zona del ejercicio con un color celeste.

Para el último ejercicio se me pedía 5 ordenadores con ip fija, así que configuré los cinco ordenaodres a mano para que tubiesen ip fija, los conecté a un switch que a su vez estaban conectados a un router. Ese router lo configure para que se pudiera conectar con las otras redes. En este router utilice para configularlo las direcciones ip : **192.30.1.0** y **192.80.1.0** que era la del ejercicio en si. Remarqué la zona del ejercicio con un tono salmón.

Después de finalizar los ejercicios se me pedía que hubiese tres servidores web(www.wagner.de, www.albacete.es y www.dilar.com) y un servidor dns que guardase las direcciones ip de estos tres. Pensando que este ejercicio podía ser una simulacion de una red, decidí aprobechar los servidores DHCP que había creado para contener los servidores web y dns por tal de que el coste total fuese más barato.

Asi qué en el servidor DHCP del ejercicio 4 active el servicio DNS y lo configuré para que **192.160.1.2 fuese la ip para la web de www.albacete.es**, **192.14.2.2 fuese la ip para la web de www.dilar.com** y **192.50.1.2 fuese la ip para la web de www.wagner.de**. En este mismo servidor añadi el servicio HTTP para que tubiese la web de www.albacete.es
Luego configure el servidor DHCP para que repartise tambien la direccion ip del servisor DNS y tambien los ordenadores con ip etática para que tubieran la ip de los DNS.

Para la web www.wagner.de utilice el servidor ya creado del ejercicio 3, despúes de configurar el servidor web, tambien configuré el DHCP para que repartiese la direcciones DNS.

Por último para la web www.dilar.com utilicé el servidor del ejercicio 2, configuré el servidor web y luego el servidor DHCP para que tambien repartiese las direcciones DNS.
