# Ingenieria
# Tecnologico de estudios superiores de Huixquilucan 
### Ingenieria Mecatronica 
### Asignatura. Control de procesos 
### Asesor. Dr Enrique Garcia Trinidad 
### Alumno. Brayan Adrian Navarrete Maltos

### Control de procesos 
# Introduccion al LabVIEW 
LabVIEW es un entorno de programacion grafica usado por ingenieros y cientificos para desarrollar mediciones sofisticadas, pruebas y sistemas de control. LabVIEW puede integrar una gran variedad de dispositivos de harware. En este curso utilizaremos el hardware de comunicacion serial y el DOQ(Data adquisition) configurando el hardware en el MAX(Measurement Automation Explorer).
Usted puede descargar la version de labVIEW estudiantil para windows MAC por lo que no necesita comprar el software.
LabVIEW es la contraccion de las palabras Laboratory Virtual Instrument.
LabVIEW es un software de desarrollo grafica y flexible creado por national instrument, una compañia que crea productos de hardware y software que le permiten a las computadoras a ayudar a ingenieros y cientificos a tomar mediciones, controlar procesos, analizar y guardar datos.
National instrument fue fundada hace 39 años en Texas apartir de personas que laboraban en la universidad de Texas.
Cientificos e ingenieros en investigacion, desarrollo, produccion, pruebas e industrias de servicio como los semiconductores automotrices, aeroespacial, electronica, quimica, comunicaciones y farmaceutica han usado y continuan usando labview para desarrollar su trabajo como por ejemplo Spacex utiliza LabVIEW para llevar los coetes falcon 9 al espacio  
### Instrumentos virtuales 
Los programas de LabVIEW son llamados instrumentos virtuales o VI(virtual instrument ) labVIEW es diferente de otros lenguajes de programacion como por ejemplo Python o "C" ya que labVIEW utiliza un lenguaje de programacion grafica conocida como lenguaje de programacion "G" para crear programas basados en simbolos graficos. LabVIEW utiliza una terminologia familiar para cientificos e ingenieros, por lo que sus simbolos o iconos graficos son facilmente identificables por inspeccion visual se puede aprender labVIEW incluso si se tiene poca experiencia en la programacion.
# Contenido
### Primer programa en labVIEW
Para poder iniciar con la programacion en LabVIEW y comenzar con nuesro primer programa es necesario ir explicando paso a paso los procedimientos a seguir como se muestra a continuacion.
### Pasos
1.- Ejecutando por primera vez LabView aparecerá un recuadro como se muestra en la siguiente imagen de  Welcome to LabVIEW el cual cancelaremos presionando (x) en la parte superior derecha.<img src="Imagen 1.1.png" />

2.- Posteriormente crearemos una nueva plataforma de trabajo, dándole clic en file –New VI- como se muestra en la siguiente imagen en la parte superior izquierda.<img src="Imagen 2.1.png" />

3.- Al crear un nuevo proyecto podrás ver que existen dos plataformas de trabajo las cuales no están en orden como se muestra en la siguiente imagen.<img src="Imagen 3.png" />

4.- Para que podamos trabajar al mismo tiempo en las dos plataformas, presionando con las teclas ctrl+T se dividirá mita y mitad como se muestra en siguiente imagen y ya estaremos listos para comenzar a trabajar.<img src="Imagen 4.png" />

5.- El objetivo de nuestro primer programa es restar dos numeros dentro de un ciclo while.
Primero hay que identificar como se llaman las plataformas de trabajo, como ya lo hemos notado en la imagen anterior existen dos, la primera que está situado a lado izquierdo es el panel frontal (Front Panel) y la segunda situado a lado derecho llamado Diagrama de bloques (Block Diagram).
En el panel frontal al darle clic derecho sobre la plataforma nos parecerá un recuadro llamado controls el cual contiene diversas herramientas con las cuales se puede trabajar, note que en la parte superior izquierda hay una tachuela la cual si le damos clic sobre ella nos sirve para tener el cuadro abierto y no se cierra mientras se esté trabajando sobre la plataforma este ejemplo se muestra en la siguiente imagen señalado con una flecha azul. <img src="Imagen 5.png" />

6.-Para seguir con el trabajo seleccionamos en el cuadro de -controls- en la opción de numeric debemos seleccionar las opciones de numeric y la arrastramos dos veces a la plataforma de Front Panel al igual que la opcion de numeric indicator la opcion de numeric indicador se le puede cambiar el nombre dandole click dos veces en este ejemplo lo llamaremos Valor A y la otra opcion la llamaremos Valor B y el numeric indicador lo llamaremos Resultado cabe mencionar que en la plataforma de Front Panel tenemos que tener un boton de stop para parar el ciclo while ya que sin este el programa no funcionaria, para tener obtener este boton debemos de ubicarnos en la opcion de Boolean ya seleccionado esta opcion buscaremos la opcion que dice Stop Botton y la arrastraremos a la plataforma Front Panel como se muestra en la siguiente imagen.<img src="Imagen 6.1.png" /> 

7.- Como ya vimos en imagen anterior los objetos que arrastramos en la plataforma de Front Panel aparecen tambien en la plataforma de Block Diagram, el siguiente paso es ubicarnos en la plataforma de Block Diagram y seleccionar la opcion de Numeric ya seleccionado esta opcion nos aparece una ventanilla en la cual vamos a seleccionar la opcion de subtract al igual que un ciclo while para esto seleccionamos la opcion de Structures ya seleccionado esta opcion nos mostrara otra opcion llamada While loop la cual arrastraremos hacia la plataforma de Block Diagram encerrando todas las opciones que estan en dicha plataforma procedemos a unir dichas opciones como se muestra en la siguiente imagen. <img src="Imagen 7.png" /> 

8.- Para poder ver que el programa funciona correctamente es necesario correr el programa con las herramientas que están en la barra de herramientas, la barra de la flecha es para correr el programa  como se muestra en la siguiente imagen. <img src="Imagen 8.png" />

### Segundo programa (Índice de masa corporal)

1.- Para este programa seguiremos los primeros 5 pasos del primer programa, ya que hemos hecho lo anterior seleccionamos la opción de Numeric para que nos aparezca la opción de numeric control la cual vamos arrastrar 3 veces en la plataforma de Front Panel esto con el fin de llamarlo cada uno como peso, altura y el porcentaje.
Ya echo lo anterior necesitaremos un Vertical Fill Slide esta opcion la encontramos dentro de la opcion de Numeric y la arrastraremos a la plataforma de Front Panel esta opcion no sirve para darle los rangos de de obesidad, sobrepeso y peso normal lo podemos diseñar como se muestra en  siguiente imagen.
Por ultimo debemos de arrastrar un boton Stop esta opcion ya se a explicado con anterioridad como encontrarlo seleccionarlo y arrastrarlo.<img src="Imagen 9.1.jpg" />

2.- Ahora nos ubicaremos en la otra plataforma de block diagram en la cual seleccionamos la opcion de Structures para seleccionar el ciclo While Loop y dentro de este ciclo arrastramos las siguientes opciones primeramente seleccionamos la opcion de numeric y dentro de esta opcion arrastraremos la opcion de constant, ya echo lo anterior anadiremos las operaciones estas las encontramos en la opcion de numeric y dentro de esta arrastraos las opciones de Divide, Add, Square esta ultima la arrastraremos 2 veces y en la opcion de Boolean arrastraremos la opcion not ya que con esta negaremos la union de estas opciones se muestra en la siguiente imagen.<img src="Imagen 10.jpg" />

3,- Corremos el programa dando click en a flecha ubicada en la parte de arriva y como podemos ver tenemos que meter valores en la opcion de numeric control, en las opciones de Peso, Altura, como se mostra en la imagen a continuacion existen dos variabloes que estan en centimetros y metros podemos utilizar cualquiera de estas dos opciones solo hay que tener cuidado con el punto decimal.
Haremos un ejemplo con un peso de 90kg y una altura de 1.75m el resultado se vera reflejado en el Vertical Fill Slide como se muestra en la siguiente imagen. <img src="Imagen 11.jpg" />

### Tercer programa (Parpadeo de un led)

1.- Para poder visualizar el parpadeo de un led en LabVIEW, hacemos los primeros 5 pasos que hicimos en el primer programa ya echo esto no situaremos en la plataforma de Block Diagram para seleccionar los siguiente elementos un Greater Than 0? ubicado dentro de la opcion de Coparison, despues otro elemento con el cual vamos a trabajar es el Quotient y remainder ubicado en la misma opcion de Comparison, Despues vamos a encerrar todos esto elementos en un ciclo loop ubicado dentro de la opcion de Structures, para poder unir todos estos elementos tenemos que ubicarnos en la plataforma de Front Panel para seleccionar la opcion de Round LED al hacer esto nos aparecera en la plataforma de diagram block otro elemento, para poder hacer que el led aprenda y apague debemos de agregar un Wait Until Next ms Multiple que esta dentro de la opcion Timming a esta opcion debemos de añadirle una constante ya que esta va a indicar el perido en el cual se va aprender y apagar para esto debemos de seleccionar la opcion Numeric Constant que esta adentro de la opcion Numeric a esta opcion le daremos una constante de 500. Para finalizar debemos de seleccionar la opcion de True Constant en la opcion de Boolean en la plataforma de Block Diagram en la siguiente imagen se muestra como debe de ir conectados todos los elementos de la plataforma de Diagram Block. <img src="Imagen 19.jpg" />

2.- Al correr el programa podermos ver en la plataforma de front Panel el led prende y apaga. Si modificamos la contante de 500 por un numero menor podemos ver que este pre y apaga mas rapido. <img src="Imagen 20.jpg" />

### Cuarto programa (Parpadeo de un led. Interfaz de LabVIEW y ARDUINO)

1.- Para poder hacer la interfaz entre el LabVIEW y ARDUINO es necesario descargar unas librerias la de toolkits linx y visa en este link se explica como hacer dicha interfaz https://www.youtube.com/watch?v=p5qlwufUeEM.
Ya que tengamos instaladas la librerias hacemos los primeros 5 pasos del primer ejercicio para despues ubicarnos en la opcion de Tools, ya desplejada esta opcion nos va aparecer varias opciones la que nosotros seleccionaremos se llama MarkerHub la cual nos va a desplazar la opcion de LINX, seguido de posicionarnos en esta tendremos la opcion de linx Firmware Wizard, en la siguiente imagen se ven los pasos ya mencionados. <img src="22630287-ae29-44ae-a9e4-5675a9bc5f25.jpg" />

2.- Ya seleccionada la opcion de linx Firmware Wizard seleccionaremos el tipo de arduino que utilizaremos, en mi caso estoy utilizando el arduino uno.   <img src="Imagen 13.jpg" />

3.- Ya seleccionado el arduino le damos en siguiente y nos abrira la siguiente ventana en la cual comunicaremos el puerto serial de donde se comunicara la computadora con el arduino en este caso esta conectado al com 6. <img src="Imagen 14.jpg" />

4.- Ya vinculado con el Com 6 le damos siguiente a todo lo que nos aparesca asta que nos aparesca cargando como se muestra en la siguiente imagen. <img src="Imagen 15.jpg" />

5.- Ya que se haya cargado nos aparecera otra pestaña en la cual daremos click en la opcion de Launch Exaple. <img src="Imagen 16.jpg" />

6.- Al darle click a la opcion anterior nos mostrara la pantalla principal la cual ya podremos trabajar haciedo la interfaz entre LabVIEW y arduino <img src="Imagen 17.jpg" />

7.- Para corroborar que nuestro arduino esta bien conectado con la interfaz del LabView hacemos una pequeña prueba conectando una resistencia seguida de un led y directo a tierra. como se muestra en la siguiente imagen, ya conectado la electronica corremos el programa y damos click sobre el led que se muestra en la plataforma de Front Panel y podemos ver que el led va a prender.    <img src="Imagen 18.jpg" />          

8.- Ya que hemos visto como hacer la interfaz del arduino con LabVIEW modificamos el codigo para que el led prenda y apage en pequeños periodos de tiempo, para ello modificamos el tercer programa y lo añadimos a la plataforma que ya habiamos mencionado en los pasos  de tal manera que las conecciones queden tal y como esta en la siguiente imagen. <img src="Imagen 21.jpg" />  

9.- Al correr el programa veremos como relacionando el tercer programa con l interfaz de arduino podemos llevarlo a la parte fisica con el led.  <img src="Imagen 18.jpg" />   




