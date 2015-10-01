Variables estáticas
En informática una variable estática es una variable que ha sido ubicada estáticamente y cuyo tiempo de vida se extiende durante toda la ejecución del programa. Normalmente una variable estática tiene un ámbito más amplio que otras variables. La terminología "variable estática" se basa en C y C++, pero también se usa en muchos lenguajes de programación derivados. 

Ciclos de vida de las variables
• Variables de instancia (u objeto):
– Se crean cuando se crea el objeto que las contiene.
– Se inicializan por defecto si no se hace de modo explícito:
0 para números, "false" para booleano, "null" para objetos.
– Se destruyen cuando el recolector de basura de Java no encuentra referencias activas para el objeto.
• Variables estáticas (o de clase):
– Se crean cuando la clase se usa por primera vez.
– Se inicializan por defecto si no se hace de modo explícito:
0 para números, "false" para booleano, "null" para objetos
– Suelen existir para el resto del programa (salvo que no esté cargado).
• Variables locales (o de bloque):
– Creadas en la sentencia en la que están definidas.
– No se inicializan por defecto. Contienen datos imprevisibles.
– Se destruyen al salir del bloque (en la llave final).

Memoria dinámica
Es memoria que se reserva en tiempo de ejecución. Su principal ventaja frente a la estática, es que su tamaño puede variar durante la ejecución del programa. (En C, el programador es encargado de liberar esta memoria cuando no la utilice más). El uso de memoria dinámica es necesario cuando a priori no conocemos el número de datos/elementos a tratar.
Clase
Una clase se puede considerar como un patrón para construir objetos.

Objeto
Un objeto es una unidad que engloba en sí mismo datos y procedimientos necesarios para el tratamiento de esos datos.

Constructores de instancias
Los constructores de instancias se usan para crear e inicializar cualquier variable de miembro de instancia cuando se usa la expresión new para crear un objeto de una clase.

Herencia
Es la capacidad de crear nuevas clases basándose en clases previamente definidas, de las que se aprovechan ciertos datos y métodos, se desechan otros y se añaden nuevos.

Sobrecarga
La sobrecarga se refiere a la posibilidad de tener dos o más funciones con el mismo nombre pero funcionalidad diferente. Es decir, dos o más funciones con el mismo nombre realizando acciones diferentes. El compilador usará una u otra dependiendo de los parámetros usados. A esto se llama también sobrecarga de funciones.

Shadowing
Se llama shadowing al hecho de que en una clase una variable miembro y una variable local definida en un método miembro, se llamen igual.
