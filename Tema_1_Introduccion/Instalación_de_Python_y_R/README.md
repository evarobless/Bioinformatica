Bioinformática
BIOINFORMÁTICA 26-27
Grado en Biomedicina
© 2023 UAX
00.- Conceptos clave
01.- Hardware
02.- Software
03.- Redes
04.- Conclusiones
05.- ¿Cómo es tu ordenador?
06.- Introducción a la
programación
Confidential & Proprietary
00.- Conceptos clave
Confidential & Proprietary
¿Qué es la Bioinformática?
• Uso y desarrollo de las tecnologías de la información para el análisis e interpretación de los datos que arrojan las diferentes investigaciones
científicas.
• Herramientas para el estudio, comparación y correlación de datos experimentales: relaciones filogenéticas, predicción de dominios,
estructuras …
• Desarrollo de algoritmos y estadísticas necesarias para la comprensión biológica.
• Búsqueda de inconsistencias, aumento de la perspectiva.
• Nuevas teorías, conceptos y perspectivas (¡Nuevas formas de entender la vida!).
• Almacenamiento de información: secuencias de ácidos nucleicos, aminoácidos ….
• Empleo de Internet y la globalización. La Web ha permitido conocer y aprovechar muchos de los avances científicos -> ¡¡¡las disciplinas se
interrelacionan (Biología de Sistemas)!!!!!
• Es un campo en constante crecimiento, todo se actualiza muy rápido. Herramientas nuevas y mejoradas.
uax.com Confidential & Proprietary
HW y SW
• Máquina capaz de procesar o tratar automáticamente, a gran velocidad, cálculos y complicados procesos que requieren una toma rápida de
decisiones, mediante la aplicación sistemática de criterios preestablecidos, siguiendo las instrucciones de un programa. La información
suministrada es procesada para obtener un resultado. Máquina de propósitos y uso general.
• La estructura física y la programación son el soporte material y lógico -> dualidad solidaria.
• Al soporte lógico se le llama Software (SW) y al físico Hardware (HW).
uax.com Confidential & Proprietary
01.- Hardware
Confidential & Proprietary
Hardware: Procesamiento
El hardware realiza las 4 actividades fundamentales: entrada, procesamiento, salida y almacenamiento.
1. Entrada:
• Teclado: teclas de función, teclas alfanuméricas y teclas numéricas.
• Ratón, lápiz óptico.
• Tableta digitalizadora: superficie de dibujo con medio de señalización.
• Entrada de voz: la emisión de voz se convierte en señales digitales.
• Pantallas sensibles al tacto.
• Lectores Código de barras.
• Scanner: convierten texto o imágenes a formas leíbles por una computadora. Si tenemos un OCR (reconocimiento óptico de caracteres)
podemos ingresar información.
uax.com Confidential & Proprietary
Hardware: Procesamiento
2. Procesamiento: esto lo lleva a cabo la CPU (Central Processing Unit), que es la responsable de controlar el flujo de datos y
ejecución de los programas. Realiza todos los cálculos, es el cerebro de la computadora. Tres partes:
• Unidad de control (UC): La UC es el núcleo de la CPU. Supervisa la ejecución de los programas, coordina y controla los cálculos y determina el
orden y prioridad de las instrucciones. También decide a dónde van los resultados de salida.
• Unidad Aritmético/Lógica (UAL): realiza los cálculos (suma, resta, multiplica, divide) y operaciones lógicas (comparaciones). Mueve los datos
entre ella y el almacenamiento. Ella usa los datos y los devuelve al almacenamiento.
• Área de almacenamiento primario: da espacio temporal para almacenar los datos de programas. Dos tipos de memoria primaria:
• ROM (Read Only Memory): solo lectura. En ella se almacenan algunos programas o información necesaria. Están grabados
permanentemente y no pueden ser modificados.
• RAM (Random Access Memory): memoria de acceso aleatorio. La emplea el usuario con sus programas. Es volátil, no permanente. Los
datos proporcionados a la computadora están aquí hasta que se procesan y de ahí se almacenan en el almacén secundario. La RAM está
subdividida en celdas, cada una con una capacidad similar para los datos.
¡La genómica emplea alta carga de
RAM ya que requiere
procesamientos muy rápidos!
uax.com Confidential & Proprietary
¿CPU de 32 o 64 bits?
Podemos tener CPUs de arquitectura 32 o 64 bits. Esto es MUY IMPORTANTE a la hora de instalar cualquier aplicación (siempre
vamos a tener estas dos opciones).
El procesador, el SO, los drivers y el software emplean la misma arquitectura -> hablan el mismo idioma.
Las arquitecturas más empleadas son las de 32 bits (x86), y la de 64 bits (x64, x86-64, AMD64).
Esto se refiere a cómo se almacenan los datos. Los de 32 bits los almacenan en piezas de 32 bits y los otros en 64 bits. Los de 64 bits
trabajan con palabras más grandes en menos tiempo -> más veloces.
En la actualidad, la gran mayoría de los ordenadores son de 64 bits, aunque todavía se da soporte a los de 32 bits.
*Apple es la gran excepción en todo este lío. Ellos empezaron a implementar los 64 bits en 2009 con Snow Leopard, y como tienen el
control de su hardware y sistema operativo poco a poco han ido haciendo de esta arquitectura la única opción en sus equipos de
sobremesa. Por lo tanto, las aplicaciones para estos ordenadores también suelen ser casi siempre sólo de 64 bits.
uax.com Confidential & Proprietary
¿CPU de 32 o 64 bits?
Los de 32 bits solo pueden gestionar 4GB de memoria RAM. Los de 64 bits muchísima más, hasta los 16 exabytes. Tanta memoria en
un portátil de momento no es posible, ej: Versión Pro Windows 10 512 GB RAM.
En 32 bits, puedes tener abiertas unas 3 o 4 aplicaciones. Para más necesitas uno de 64 bits. Generalmente, los de 64 bits son más
veloces, aunque depende de la aplicación y puedes derivar memoria para algunos programas como Photoshop.
uax.com Confidential & Proprietary
¿CPU de 32 o 64 bits?
uax.com Confidential & Proprietary
Hardware: Procesamiento
Tipos de procesadores: Intel, AMD …
https://newesc.com/tipos-de-procesadores-guia-completa/
¿Qué son las GPU o Unidades de Procesamiento Gráfico? Es un procesador especializado para gestionar tareas de alta carga gráfica
como la renderización de imágenes y vídeos. En Bioinformática, el campo de la Biología Estructural sería el que más lo emplearía.
https://www.intel.la/content/www/xl/es/products/docs/processors/cpu-vs-gpu.html
https://softwarelab.org/es/blog/que-es-una-gpu/
uax.com Confidential & Proprietary
Hardware: Almacenamiento
3. Almacenamiento (secundario): almacenamiento definitivo, no volátil como la RAM. El proceso de transferencia de datos a un
equipo se llama procedimiento de lectura, y el de transferencia de los datos al almacenamiento se llama procedimiento de
escritura.
• Almacenamiento magnético: discos flexibles, discos duros (HDD o SDD), cintas magnéticas o cartuchos.
• Almacenamiento óptico: CD ROM (CD Read Only Memory) y WORM (Write Once, Read Many).
• Medios magnético-ópticos: combinan ambas.
• Dispositivos de almacenamiento externo.
• Nube.
https://experience.dropbox.com/es-es/get-
organized/storage-devices
https://www.xataka.com/basics/hdd-vs-ssd
uax.com Confidential & Proprietary
Hardware: Almacenamiento
uax.com Confidential & Proprietary
Hardware: Salida
4. Salida:
• Monitores, pantallas.
• Impresoras…
uax.com Confidential & Proprietary
Otros hardware: Placa Base
Placa madre o mother board: la CPU se instala en la placa madre, que es la tarjeta principal del ordenador. Tiene unos zócalos dónde
se instala el procesador. Es una pieza compuesta por un conjunto de chips y circuitos dónde se conectan las demás partes del equipo.
¡¡¡Es una de las partes de hardware más importante de todas!!! En ella se enlazan las unidades de almacenamiento, procesador, RAM
y otros elementos que permiten el arranque del equipo y el reconocimiento de periféricos. Es la columna vertebral.
uax.com Confidential & Proprietary
Otros hardware: Tarjeta gráfica
Tarjeta gráfica o de video: se encuentra integrada en la placa base o se instala de forma adicional como una tarjeta de expansión.
Dedicadas al procesamiento de datos relacionados con el video y las imágenes. Permiten procesar y recibir muchísima más cantidad
de datos digitales en la pantalla. Poseen su propia RAM y una unidad de procesamiento independiente, para evitar el ralentizamiento
del ordenador.
uax.com Confidential & Proprietary
Otros hardware: Alimentación
Fuente de poder: dispositivo que se coloca en el gabinete de la computadora y que permite transformar la corriente alterna de la
línea electrónica comercial en corriente eléctrica. La Fuente de poder está conectada a las partes más importantes de la
computadora como la placa madre y el disco duro. Envía el voltaje exacto que necesita cada componente para funcionar de forma
ininterrumpida y sin fallos.
uax.com Confidential & Proprietary
02.- Software
Confidential & Proprietary
Tipos de software
Conjunto de instrucciones que las computadoras emplean para manipular datos. Conjunto de programas, documentos,
procedimientos y rutinas asociadas a las operaciones de cómputo. Es el conjunto de instrucciones que hace funcionar al hardware.
1. Lenguajes de programación: indica qué tarea y cómo hacerla. Dan órdenes entendibles para la computadora. La computadora
solo entiende el lenguaje máquina, por lo que los lenguajes de programación actúan como un intermediario. Los hay de bajo y
alto nivel.
2. Software de uso general: gran número de acciones y aplicaciones.
• Procesadores de texto
• Hojas de cálculo
• Bases de datos (agendas)
• Paquetes de presentación
• etc…
uax.com Confidential & Proprietary
Tipos de software
3. Sistemas operativos (SO): es el gestor y organizador de todas las actividades. Marca las pautas según las cuales se intercambia la
información y determina las operaciones elementales que puede realizar el procesador. El SO despierta a la computadora y hace
que reconozca a la CPU, memoria, teclado y demás hardware. Da facilidad para que el usuario se comunique con la computadora,
es una plataforma. Lo más importante del SO es el kernel (núcleo del SO), que controla los recursos del hardware, permite la
ejecución de programas y da un Sistema de archivos. Los SO de la actualidad son:
• Multitarea: permiten ejecutar varios programas a la vez.
• Multiusuario: permiten acceso a usuarios diferentes.
• Multiproceso: funcionan con más de una CPU.
uax.com Confidential & Proprietary
MS-DOS, Windows, MacOS, UNIX-GNU/Linux
03.- Redes
Confidential & Proprietary
Redes de computadoras
Una red es una manera de conectar varias computadoras entre sí, compartiendo recursos e información y siendo conscientes una de
la otra. Tipos:
• Redes LAN (Local Area Network): se produce en un área relativamente pequeña (200 m). Casa u oficina.
• Redes MAN (Metropolitan Area Network): redes en una ciudad, área industrial o varios edificios. WiFi gratuita de ciudades.
• Redes WAN (Wide Area Network): formada por varias LAN interconectadas en una amplia área geográfica (continentes).
ARPANET es la WAN más grande creada por la Secretaría de Defensa de los EEUU. ARPANET se convirtió en la WAN mundial
o INTERNET.
Existen varias teorías relacionadas con el nacimiento de Internet, aunque la más aceptada es que nace en los
60 con el nombre de ARPAnet, como un proyecto militar apoyado por universidades para interconectar
computadores que alertasen a los ejércitos en caso de un ataque. En 1972 se unieron más de 40
universidades, lo que permitió que se masificase y junto con la aparición de UNIX, llegó a los hogares de la
mayoría de la población.
Hoy en día, Internet conecta y ofrece servicios como el WWW o telaraña de información mundial, el e-mail,
el FTP, el chat y hasta comercio electrónico.
https://www.elespanol.com/invertia/disruptores/grandes-actores/investigacion/20220110/internet-
cosas-tecnologia-culmina-viejo-sueno-conectarlo/640686032
0.html
_
https://www.genbeta.com/a-fondo/teoria-internet-muerto-no-podemos-tener-claro-estamos-
interactuando-humanos-algoritmos
uax.com Confidential & Proprietary
Redes de computadoras
https://www3.gobiernodecanarias.org/medusa/ecoblog/dtrugar/files/2019/10/02-redes.pdf
https://decisiontele.com/es/news/1g-5g-evolution-telecommunication-networks.htmluax.com Confidential & Proprietary
Transmisión de datos
La transmisión de datos en las redes puede ser por dos medios:
• Guiados o Terrestres: limitados y transmiten la señal por un conductor físico (ej: fibra óptica, cable coaxial…).
• Inalámbricos o Aéreos: ilimitados y transmiten las señales electromagnéticas por microondas o láser.
uax.com Confidential & Proprietary
https://www.xataka.com/historia-tecnologica/1-000-millones-de-metros-de-cable-submarino-son-los-responsables-de-que-tengas-internet-en-casa
https://www.submarinecablemap.com/
uax.com Confidential & Proprietary
04.- Conclusiones
Confidential & Proprietary
Bionformática
Empleamos las tecnologías de la información para captar, organizar, analizar y distribuir información biológica para responder
preguntas complejas en la biología.
Tratamiento de datos de las biociencias.
Adquisición, almacenamiento, procesamiento, distribución, análisis e interpretación de la información biológica.
En la actualidad, la parte más importante de la bioinformática es el análisis e interpretación de los datos de las moléculas biológicas,
un proceso que se denomina biología computacional. Se podría decir, de hecho, que la bioinformática se encarga de la parte
lingüística de la genética. Los objetivos fundamentales son identificar genes y proteínas, determinar sus funciones, establecer
relaciones evolutivas y predecir su conformación.
La bioinformática utiliza técnicas informáticas que se aplican en otros campos, como la inteligencia artificial, y que incluyen el
reconocimiento de patrones, los algoritmos de aprendizaje automático y la visualización de datos. También es la base actual de la
biotecnología y gracias a ella será posible desarrollar fármacos más eficaces, tratamientos genéticos e incluso avanzar en la lucha
contra el cambio climático, lo que convierte a los bioinformáticos en un perfil digital de futuro.
uax.com Confidential & Proprietary
uax.com Confidential & Proprietary
https://github.com/vsbuffalo/bds-files
uax.com Confidential & Proprietary
05.- ¿Cómo es tu ordenador?
Confidential & Proprietary
Windows
• Configuración -> Sistema -> Información/Detalle
• Ejecutar dxdiag en el buscador
MacOS
sistema
• Menú Apple -> Preferencias del sistema -> General -> Acerca de -> Informe del
uax.com Confidential & Proprietary
06.- Introducción a la programación
Confidential & Proprietary
Lógica de programación
Ordenadores, móviles y otros dispositivos electrónicos funcionan realizando una serie de operaciones en un orden determinado.
A la lista de órdenes se llama programa.
Para darle esas órdenes se emplea un lenguaje de programación.
A la lista de operaciones que resuelven algún problema paso a paso se le llama algoritmo -> conjunto de tareas ordenadas.
Primer algoritmo:
1. Salir de la clase
Segundo algoritmo
1. Preparar un vaso de leche
uax.com Confidential & Proprietary
Diagramas de flujo
Los algoritmos pueden
representarse de varias formas, con
frases, gráficos etc..
Una de las maneras más habituales
es con diagramas de flujo.
Generalmente tenemos que tomar
decisiones (bucles if).
Hay que tener cuidado de no
cometer errores pensando muy
bien lo que se hace en cada uno de
los bloques o pasos.
uax.com Confidential & Proprietary
Bloques entrada y salida
En algunos algoritmos pedimos
datos o sacamos datos por la
pantalla, para ello utilizamos el
bloque Entrada / Salida.
uax.com Confidential & Proprietary
Ejercicio
Realiza el diagrama de flujo correspondiente al algoritmo con los siguientes pasos:
Te pregunta un número entre 1 y 10
https://app.diagrams.net/#
Comprueba si está entre 1 y 10
Te pregunta otro número entre 1 y 10
Dale a decidir más tarde para no
tener que registrarte
Comprueba si está entre 1 y 10
Te da el resultado de sumas los dos números
uax.com Confidential & Proprietary
Estructuras de repetición
A veces necesitamos repetir ciertas acciones varias veces por lo que existen estructuras de repetición o bucles. Dos tipos principales:
1. Repetición para siempre (bucles while).
• No tiene bloque de FIN. Solamente acaba cuando cambia una condición.
2. Repetición de un número determinado de veces (bucle for).
Realiza el diagrama de flujo correspondiente al algoritmo con los siguientes pasos:
Mandar a un robot subir 20 escalones
Primero tiene que subir la pierna derecha y luego la pierna izquierda
Cuando llegue al último escalón, el robot tiene que detenerse
uax.com Confidential & Proprietary
Lenguajes de programación
• El lenguaje de programación nos permite crear algoritmos en un lenguaje entendible para un ordenador.
• Los equipos se comunican con lenguaje máquina (unos y ceros, datos binarios)-> lenguaje de bajo nivel.
• Lenguaje de programación-> lenguaje de alto nivel (permite ser traducido a lenguaje máquina y además ser comprensible para
las personas).
• Compilador o intérprete: traduce a código máquina las órdenes del lenguaje de programación.
