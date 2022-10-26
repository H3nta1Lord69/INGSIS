## Sistemas Distribuidos

1. ¿Qué es un sistema distribuido?
2. Objetivo del sistema distribuido
3. Tipos de sistemas distribuidos
4. Conclusiones

#### Conceptos
- Es un conjnto de equipos (servidores) que trabajan de forma coordinada para que actúen como un solo sistema de cara al usuario.
- Múltiples computadores hacen la tarea o tareas que tienen un único objetivo.
- Los podemos definir principalmente en 2 campos:
  - Centralizado
  - Distribuido

### Middleware
Los sistemas distribuidos se organizan a menudo en términos de una capa de software, esto es, vienen colocados de manera lógica entre una capa de alto nivel que consta de ususario y aplicaciones, y una capa subyacente constituida por sistemas operativos y recursos básicos de comunicacíon.

#### Conceptos
Por ejemplo una base de datos distribuida aporta una serie de ventajas:
- La información se almacena físicamente en varios sitios de la red, aunque lógicamente, de cara a un usuario final en una única base de datos. Cuando queramos acceder a la información, vamos a lanzar una consulta e internamente ya sabrá donde está almacenado cada uno de los datos.
- Indepencia al sistema operativo Linux o Windows, la base de datos es de forma distribuida y resulta completamente transparente el sistema operativo para el usuario final.
- La información queda fragmentada y las réplicas aportan alta disponibilidad.

### Ventajas de un Sistema Distribuido
Algunas de las ventajas que aportan son:
- Mayor eficacia
- Mayor tolerancia a fallos:
  - Al estar distribuida la información en nodos, en caso que se caiga un nodo, dicha información se va a encontrar en otros nodos.
- Mayor velocidad y procesamiento distribuido:
  - Cuando se realiza una consulta, los procesamientos se dividen entre todos los nodos que forman un sistema distribuido, en lugar de enviarlos a un único nodo y que el mismo tenga que hacer todo el trabajo.
- Escalabilidad:
  - Si, por ejemplo, se necesitan más procesamientos o añadir más disco duro, en lugar de que los equipos crezcan de forma vertical añadiendo más almacenamiento, RAM o CPU, se añaden equipos de forma horizontal al clúster o sistema distribuido.

### Sistemas distribuidos 
1. Centralizado
   - Cliente -> Servidor Web -> Servidor de BD
2. Distribuido
   - Cliente -> Varios servidores web distribuyendo la información -> Servidores de BD

### Objetivos 🚀
Un sistema distribuido debe hacer que los recursos sean fácilmente accesibles; debe ocultar de manera razonable el hecho de que los recursos están distribuidos por toda la red; debe ser abierto; y debe ser escalable.
- Vertical scalability
- Horizontal scalability

#### Escalabilidad
La escalabilidad de un sistema se puede medir de acuerdo con al menos tres dimensiones; su tamaño 

#### Transparencia en la distribución

#### Nivel de transparencia
Buscar la transparencia de distribución puede ser un buen objetivo cuando diseñamos e implementamos sistemas distribuidos, pero debemos considerarla junto con otros problemas tales como el rendimiento y la comprensibilidad.

#### Sistemas distribuidos de cómputo
Es la utilizada para realizar tareas de cómputo de alto rendimiento. Podemos hacer una distinción entre dos subgrupos: el cómputo en clúster y el cómputo en malla (grid).

#### Sistenas distribuidos de información

#### Sistenas distribuidos masivos
Con la introducción de idspositivos de cómputo móviles y embedidos. Ahora nos enfrentamos con sistemas distribuidos en los cuales la inestabilidad es el comportamiento predeterminado. En estos sistemas, a los que nos referimos

### ¿Qué es el teorema de CAP?