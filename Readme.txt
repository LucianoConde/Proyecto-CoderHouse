(este readme fue creado para la pre-entrega, en el final se cambiaron y corrigieron muchas cosas, como era de esperarse, dejo a partir de la linea 30 el readme actual)

Pre-entrega proyecto final curso de coder

Juego estilo Runner 
la idea no es que sea infinito si no por niveles, en los que aumente la dificultad y cambie el escenario.

hay varios tipos de enemigos, seleccionables con  switch.
los que están en el carril se diferencian en 2: los "kamikaze" y los agresivos
los kamikaze simplemente avanzan a una velocidad media hacia adelante y mueren al ser golpeados una vez
los agresivos son mas grandes, lentos, requieren mas golpes para morir y se dirijen directamente hacia el jugador.
todos los enemigos desaparecen al llegar al final del mapa.
proximamente se diferenciaran tambien por color.

todos los enemigos dan puntaje al ser eliminados. proximamente se tendran en cuenta los puntos al final del juego.

fuera del carril la idea es poner enemigos que disparen con arco hacia puntos aleatorios del camino,
para dificultar el movimiento del jugador. (aun no implementado)


el jugador puede moverse hacia los costados (con A y D) salta (con space) y dispara (con click izquierdo)
cada shuriken hace 10 de daño y tienen un tiempo de recarga.
mas adelante añadiré un canvas con la cantidad de munición y posibilidad de agarrar mas del carril.

el personaje recibe daño si es golpeado por un enemigo, y muere al llegar a 0 de vida (configurable por inspector)

mas adelante pienso implementar una selección de personaje y ya estoy trabajando en el canvas de la vida y las shuriken.


-------------------------------------------------------------

la segunda parte del curso me enfoque mas en corregir errores que iban surgiendo mas que en agregar las cosas que prometí en el anterior readme. por lo que el juego me resultó muy incompleto, pero bueno... en todo caso se las cosas que faltan, como agregarlas y en cambio, se las ventajas que tiene y como funcionan, todo esto gracias al curso y a los compañeros que me guiaron en el proceso y me ayudaron a despejar dudas y demas. comento un poco como terminó el juego por los bugs que aparecieron.

en un principio el juego contaba con varias clases de enemigos, tiempo entre disparos, contador de munición, selección de personajes en la pantalla principal, un enemigo final y estaba pensando en el segundo nivel.

pero el juego dejó de andar por todos lados. en principio dejó de disparar, lo cual fue rarisimo porque no encontraba la causa y no conseguia a nadie que me pudiera dar una mano para descubrirlo.
luego el personaje del jugador dejó de saltar :) tampoco tenia idea por que.
ademas los enemigos dejaron de correr hacia adelante, y se les rompió la animación. cuando el jugador moria los enemigos corrian hacia atras (⁠ノ⁠｀⁠Д⁠´⁠)⁠ノ⁠彡⁠┻⁠━⁠┻
todo esto cuando se abrió la entrega final.

por lo que tuve que decidir entre corregir esas cosas que me tomaron muchisimo tiempo, o agregar de mas y explotar el juego de bugs, haciendolo injugable.

el juego está terminado muy basicamente, ni siquiera aclara el objetivo, el cual es por el momento llegar a 160 puntos eliminando a los enemigos con las shuriken antes de llegar al final del mapa. obviamente esta demasiado incompleto pero al menos se que no tiene errores (no demasiado evidentes al menos) y que se puede jugar una y otra vez para probar todos los finales.

con esto me despido y seguiré subiendo estos dias algunas modificaciones que me quedaron medio pendientes, mi idea es cerrar este proyecto lo mejor posible antes de dedicarme al proximo, el cual quiero que sea para moviles.
