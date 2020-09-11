# Algoritmos y programación I

    Los programas describen máquinas

Los **programas** son las máquinas que crean los ingenieros de software, a diferencia de otras ingenierías, *nuestras máquinas se acercan mas a una proposición filosófica que a una aspiradora*. Pero al igual que una aspiradora **los programas dan un resultado al manipularlos**.

Dada su esencia inmaterial **es necesario de artefactos para** ***correr o ejecutar*** **los programas** (*run - execute*). Este soporte es otra máquina: una **computadora**.

Las computadoras y los dispositivos similares son llamados **hardware** mientras que los programas y todo lo relacionado es el **software**


    a material realization of the immaterial machine that you defined
    through your program.

Los programadores escriben programas y los usuarios los ejecutan. Lo que el programador escribe se ejecuta a una velocidad deslumbrante, lo que escribís es lo que obtenés. 

Pero las computadoras no entienden lo que ejecutan, no son inteligentes, solo procesan a grandes velocidades 


    la computadora es como un sirviente devoto e insufrible: infinitamente fiel, casi infinitamente rápido y definitivamente estúpido.

Es vital dar las instrucciones con la mayor sutiliza y cuidado, ya que la computadora no puede corregir los errores y si encuentra uno lo ejecutará miles de veces por segundo.

Es por esto que hay que prever todos los escenarios posibles para prevenir todos los errores posibles.


## Las computadoras

Son maquinas que **almacenan y recuperan información**, realizan **operaciones** con esta información y pueden **intercambiarla** con otros dispositivos.


- **Almacenan y recuperan**: requisito previo, deben poder guardar la información para procesarla y comunicarla. Se guarda en una memoria.
- **Operaciones**: son algo básicas, algunas aritméticas, de sustitución y de comparación. La velocidad de la computadora y el ingenio humano aprovechan estás operaciones para lograr cosas increíbles.
- **Comunicación**: que nos permite entregarle información que luego puede tratarse a través de operaciones y almacenarse, además de compartirla con otros dispositivos como sensores, pantallas u otras computadoras.


    El entorno → Dispositivos de comunicación → Procesador → Memorias

**Las memorias**
Mantienen la información, hay varios tipos y se diferencian por la velocidad de de acceso a la información y por la **persistencia** de esta.

**Procesadores**
Realizan las operaciones y existen diferentes tipos, los llamamos **CPU (**Central Processing Unit)

**Dispositivos de comunicación**
Proveen un medio de comunicación con la computadora y desde la computadora al entorno. Desde las **entradas** (input) a las **salidas** (output) se comunica al procesador y este con las memorias.


## Información y datos

Aquello que almacenamos en memorias, procesamos a través de las operaciones del procesador e intercambiamos a través de los dispositivos de comunicación

Las computadoras no procesan la información directamente, procesan datos. **La información se codifica en forma de datos.**

Reducido a sus componentes vitales (procesador y memorias) la computadora es un dispositivo **embebido** (embedded) en otros dispositivos.


## Memorias

Son dispositivos para almacenar y recuperar información. En las memorias se almacenan los programas por eso se habla de **stored-programs**. Esto que los programas sean susceptibles a diversas transformaciones: igual que los datos


- Los programas se escriben con lenguajes de programación fácilmente entendibles para los humanos.


- Los compiladores, unos programas especiales, traducen el lenguaje de programación a un lenguaje de máquina entendible para el procesador.


    Las propiedades estáticas de un programa son propiedades de su texto fuente (source), que pueden ser analizado por un compilador. Las propiedades dinámicas son las que caracterizan su ejecución individual.

Las computadoras son dispositivos **embebidos** dentro de otros dispositivos. Reciben información mediante sensores y otros dispositivos y devuelven resultados.

El software debe ser **reutilizable**, que sea susceptible a mejoras. **Entendible**, para poder mejorarlo facilmente. **Robusto** para defenderse de inputs inesperados y mas importante, **Correcto**, para producir el resultado esperado.


----------


## Hard Soft y PC’s

El software transforma al hardware, que es una maquina sin un propósito especifico, en una máquina especializada. El software le da un propósito, un fin.

La computadora tiene la cualidad de ser multipropósito, al complementarse con el software se transforma temporalmente en una maquina especifica para una tarea como documentos, hojas de calculo, navegador.

Aunque el software sea una construcción intelectual, sin materia, tiene la capacidad de interferir en la realidad o en las personas que lo utilizan.

Este software es información empaquetada que se interpreta en un contexto, dado por el hardware que lo ejecuta y el usuario que lo utiliza.


## Organización de una computadora

Llevan adelante tres tareas, almacenan y recuperan información, aplican operaciones sobre esta información y pueden intercambiarla. Para todo esto requieren tres componentes. 

Una memoria para guardar la información, un procesador para realizar las operaciones y los dispositivos de comunicación para poder intercambiarla.


## Sobre algoritmos

El software lo creamos para solucionar problemas, la transferencia de información, el reconocimiento de imágenes y la traducción de estas en información por ejemplo. 

Para crear estas soluciones empleamos a los **algoritmos**, una forma de descomponer el problema en sub-problemas menores, para componer finalmente la solución.

La solución no sera el reconocimiento de la imagen, sino los pasos o tareas que ira siguiendo el software para devolvernos la información deseada.


## Sobre lenguajes

El **lenguaje de programación** es la herramienta para describir las soluciones que desarrollamos, las tareas que debe resolver paso a paso el Hardware. 

Son lenguajes con reglas bien definidas, una forma de comunicarse con el hardware y con el resto de programadores, ya que es información empaquetada, la solución a un problema.

Una **sentencia**, describe uno de los pasos a seguir y tiene una **semántica** o significado determinado. Para construirla es necesario seguir una **sintaxis** estricta, con sus formas y reglas. 


## El software

Esta construido por un conjunto de sentencias escritas en un lenguaje de programación. A todo este conjunto de sentencias lo llamamos **código fuente** (source code).

Este código fuente, se traduce a un conjunto de instrucciones llamado **código binario**. El hardware habla en un lenguaje muy primitivo, de bajo nivel. Los lenguajes de programación se escriben en un lenguaje de alto nivel, comprensible para humanos.


## Compilador e intérprete

Un compilador es un software que traduce el código fuente en un lenguaje ejecutable por el hardware, el lenguaje de máquina o código binario. Lo traduce para un hardware determinado.

Un interprete permite ejecutar en un hardware sentencia a sentencia, traduce instrucción por instrucción el lenguaje de programación al lenguaje de máquina. 

El compilador traduce una sola vez y el interprete se traduce cada vez que se ejecuta cada instrucción. Pero siempre es necesario traducir el lenguaje de alto nivel al de bajo nivel.


## Programación orientada a objetos

Un objeto es una máquina de software, es inmaterial. Se construye con información y tiene métodos para controlarla, para realizar las operaciones con la información.

Existen diferentes tipos de objetos que se determinan por la información que contienen y las operaciones que nos disponen.  Dos objetos del mismo tipo son exactamente iguales, varían su información y el estado a lo largo del tiempo.

**Creación de objetos**

Para este propósito utilizamos el lenguaje de programación Java a través de su intérprete.


    > new BatallaEspacial();

Esta sentencia crea un objeto, la *palabra reservada* **new** indica que estamos creando un nuevo objeto, se acompaña con el nombre del tipo y una serie de paréntesis. BatallaEspacial es el tipo de objeto.


    > new Nave();

Crea un nuevo objeto de tipo Nave, esto simplemente lo crea, el problema es que no lo podemos manipular, no podemos utilizar sus operaciones o métodos para interactuar con la información que tiene. 


    > Nave exploradora;

Se **declara** una variable que permite recuperar la información del objeto desde la memoria para manipularlo. 

Las variables son entidades que tienen la capacidad de guardar un valor, apuntan a un espacio en la memoria donde se aloja el valor.

Tienen un **nombre** que las identifica, almacenan un **valor** y tienen un **tipo** que determina las características del valor que almacenan.


    > exploradora = new Nave();

Se **asigna** un valor a la variable creada, el valor es un objeto. Se utiliza el signo de igualdad para asignar un valor a una variable. El valor que se le asigna es el resultado de una **expresión**, en este caso la creación de un objeto, el objeto como tal.


    > Nave kamikaze = new Nave();

En este caso se **inicializa** una variable se declara y asigna una valor inicial en una misma sentencia.


    > exploradora.despegar();

Se **invoca** una de las operaciones o **métodos** que puede realiza el objeto Nave, estas operaciones están definidas en el tipo. A través del operador punto se *invoca* ******un *método*.














