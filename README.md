# expandswap
Esta pequeña aplicación permite expandir temporalmente la memoria de intercambio o swap través de la creación de un archivo montado temporalmente como una partición. 
Esta ampliación se pierde al reiniciar el sistema.

De Wikipedia:

    La mayoría de los sistemas operativos modernos poseen un mecanismo llamado memoria virtual, que permite hacer creer a los programas que tienen más memoria que la disponible realmente. Como en realidad no se tiene físicamente toda esa memoria, algunos procesos no podrán ser ubicados en la memoria RAM.
    En este caso es cuando es útil el espacio de intercambio: el sistema operativo puede buscar un proceso poco activo, y moverlo al área de intercambio (el disco duro) y de esa forma liberar la memoria principal para cargar otros procesos. Mientras no haga falta, el proceso extraído de memoria puede quedarse en el disco, ya que ahí no utiliza memoria física. Cuando sea necesario, el sistema vuelve a hacer un intercambio, pasándolo del disco a memoria RAM. Es un proceso lento (comparado con usar sólo la memoria RAM), pero permite dar la impresión de que hay más memoria disponible.

En gnu-linux la swap suele encontrarse en una partición dedicada que se crea al momento de la instalación del sistema operativo.

    Normalmente se recomienda que el tamaño de la partición SWAP sea del mismo tamaño o del doble de la cantidad de memoria RAM que tenemos en la PC

Me ha pasado de estar realizando tareas verdaderamente exigentes en términos de memoria de trabajo, en donde la cantidad asignada a la partición swap casi se satura. Buscando en inet. encontré esta solución e hice una pequeña aplicación para facilitar los comandos de terminal que se utilizan.

De esta página (https://www.ajpdsoft.com/modules.php?name=News&file=article&sid=254) saqué la información necesaria para hacer la aplicación; en la misma se encuentran también los pasos a seguir para que dicha ampliación funcione de manera permanente. Aunque lo recomendable siempre es aumentar el tamaño de la partición swap y no este método.

Si esta app te pareció interesante o querés hacer algun comentario, por favor dejá un mensaje en el blog!
https://thenerdyapprentice.blogspot.com/2020/05/programa-para-expandir-temporalmente-la.html

Saludos!
