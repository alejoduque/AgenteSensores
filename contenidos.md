

# Plan de trabajo y contenidos


<a id="org7728eff"></a>

## 9:00 a.m a 10: 00 a m. Inicio y presentación de los participantes y del proyecto. ¿Qué es la Ciencia de Barrio? Lo que aprendimos después de Fukushima.


<a id="orgcda35e9"></a>

### No necesita presupuesto


<a id="orgbabc986"></a>

### No requiere un aval académico ni estatal


<a id="orgaeabe05"></a>

### No requiere primaria, ni bachillerato, ni maestría, ni phd


<a id="org1d744a3"></a>

### Requiere tiempo


<a id="org7de9609"></a>

### Requiere persistencia


<a id="org0dde7f2"></a>

### Requiere estudio


<a id="orge6120a2"></a>

## 10:00 am a 11:00 am. La partícula pm 2.5 ¿Qué es? ¿De dónde viene? ¿Cómo nos afecta?


<a id="org5287b33"></a>

### Mucho mas pequeña que uno de los pelos que sirve de filtro en la nariz, relación 70 a 2.5, como la relación entre una persona (1.80mts) y un edificio de 50 metros.


<a id="orgb71c342"></a>

### Puede viajar en el torrente sanguineo e incrustarse en cualquier parte.


<a id="orgb4adcb8"></a>

## 11:15 am a 12:30m. Presentación de las visualizaciones en proyección sobre un mapa y las cuestiones concernientes al tema de la calibración de los sensores.


<a id="org0befa7e"></a>

### Graficar valores sobre una línead de tiempo (chronograf)


<a id="org7c368ea"></a>

### Graficar valores sobre un mapa

-   Recorridos <http://daquina.io/aqaviz/>

-   Estaciones <http://daquina.io/aqaVizEstaciones/>


<a id="orgfaa7e74"></a>

### Es posible calibrar el sensor .. pero:

-   No requiere ser calibrado para divertise.

-   No se requiere un formula uno para ir de paseo.

-   No se requiere validación académica

-   No se requiere validación del estado porque no emitimos alertas oficiales, declaramos nuestras propias crisis ambientales no oficiales.


<a id="orgd898178"></a>

## 12:30 p.m. a 1:30 p.m. Almuerzo


<a id="orgaafb295"></a>

## 1:30 p.m a 3:00 p.m. El hardware desarrollado por un/loquer. Cómo utilizarlo.


<a id="org11e76e3"></a>

### Modo sin internet v.0.2

Se usa el branch versión 2 <https://github.com/unloquer/AQA/tree/version2> permite salvar a la memoria flash y no espera conexión a wifi para poder reportar datos a los leds.


<a id="orgf21c0ff"></a>

### Modo con internet v.0.3

Se debe conectar a una red wifi

-   Conexión a wifi

    Al encender el ESP crea una red llamada ESP<un numero que cambia>, se apunta un navegador a la dirección 192.168.4.1  que resuelve en un mini portal que permite la configuración wifi.
    Al tener acceso a wifi el dispositivo empieza a emitir dos flashes de los leds con el código de colores ICA.
    Cuando el dispositivo se localiza (esta listo el GPS) empieza a transmitir a la base de datos y emite flashes más rapidos.


<a id="org5cee5c8"></a>

## 3:00 p.m a 4:00 p.m. Salida a realizar la primera captura de datos.


<a id="org946d0c5"></a>

## 4:00 p.m a 5 p.m Visualización de datos.


<a id="org35ec748"></a>

### Chronograf

verificar las mediciones guardadas en la base de datos (influxdb) de los recorridos
Crear un dashboard con reporte gráfico de las mediciones
Exportar los datos de las mediciones según la consulta de deseada, por ejemplo 1 hora de mediciones (exporta en format .csv)
Hacer una petición al API para ser consumida por otras aplicaciones TODO: ¿es chronograf el que crea el API o es influxdb?


<a id="orgff80089"></a>

### Shiny

Crear un mapa y consumir los datos de influxdb para por ejemplo mostrar  los recorridos que se hicieron.


<a id="orgf737177"></a>

## 5:00 p.m a 6:00 p.m. Resolver problemas y afinar sistemas para asegurar la óptima utilización de los dispositivos.


<a id="orga553a2f"></a>

# ¿Cómo se esta sumando unloquer al problema de la calidad del aire?


<a id="org4aee52b"></a>

## ¿Es relevante un dispositivo que le muestre a la **persona** la calidad del aire que respira en **ese  momento**?


<a id="org99b5dcb"></a>

## ¿De que sirve compartir esas mediciones a una red ciudadana?


<a id="orgdca845a"></a>

### ¿Los datos históricos me permiten enterarme de los momentos (meses, dias, horas) en que mejora la calidad del aire?


<a id="org3e80d83"></a>

## ¿Qué poder tengo sobre mi aire?


<a id="orga2e625f"></a>

### ¿Las personas que estan tomando desiciones para cambiar esa situación estan muy lejos?


<a id="org86b22ab"></a>

### ¿A qué velocidad podemos esperar los cambios?


<a id="orgcfe6e41"></a>

### ¿Sirve la metáfora de la reja ?

Una persona habita con una ventana en un primer piso que da a la calle, a varios vecinos les han roto la ventana para robarles frutas y otras pertenencias, el gobierno dice que tiene pactos y programas para disminuír la delincuencia en la ciudad gradualmente hasta lograr índices parecidos a alguna ciudad tranquila de un país desarrollado, la persona no sabe si esperar a que el gobierno mejore la inseguridad o poner una reja en su ventana.


<a id="org31aec32"></a>

### ¿La máscara sírve?

-   ¿Las partículas pm25 son mas pequeñas que un pelo de la nariz? 25 a 70     :log:


<a id="org7a21042"></a>

### ¿Puedo saber dónde esta mejor el aire?


<a id="orgd908ce5"></a>

## ¿Puedo usar el pretexto del problema de la calidad del aire en medellín para aprender de  matemáticas?


<a id="orgf8a6647"></a>

### ¿De Antropología?

-   ¿Es un problema nuevo en la ciudad? ¿no?  <http://www.universocentro.com/NUMERO86/Humossetenteros.aspx>


<a id="orgf80988a"></a>

### ¿De Programación?


<a id="org729d10b"></a>

### ¿De Biología?

-   El Guáimaro, Sogamoso <https://actualidad.rt.com/actualidad/266121-arbol-magico-colombia-titan-polucion>


<a id="org5c75d44"></a>

## ¿Cómo me sumo?


<a id="org74612c6"></a>

### ¿Puedo donar un sensor a un hospital infantil?


<a id="org566ed49"></a>

### ¿Puedo resolver alguno de los problemas de programación?  <https://github.com/unloquer/AQA/issues>


<a id="orgd1de743"></a>

### ¿Puedo medir la calidad del aire en una fábrica cerca a mi casa?


<a id="org69f489f"></a>

### ¿Puedo ayudar a saber si los foggers sirven para disminuir el material particulado?


<a id="orgdc5dda0"></a>

### ¿Puedo conversar sobre el tema en un foro? <https://comunidad.unloquer.org/>


<a id="org2d3dc9c"></a>

# ------

Encontraremos una forma de estructurar la información para abrazar el problema de la calidad del aire.
Se presentarán algunos componentes que pueden serivir para construir las funciones, se inicia mencionando algunos tipos o entes involucrados, luego las operaciones que se pueden aplicar entre ellos,  fnalmente algunas estructuras de control. 


<a id="orgfe91c9d"></a>

# Elementos


<a id="orgc123a56"></a>

## Tipos


<a id="org8397925"></a>

### Aire

Es afectado por Viento, Calentamiento, Emisión
Afecta la Respiración
Puede ser Medido


<a id="org1e13007"></a>

### Automotores de combustible fósil

Emiten Material Particulado, suben la temperatura


<a id="org40becbe"></a>

### Material Particulado <http://rama.edomex.gob.mx/caracteristicas>

-   PM2.5 se depositan por difusión

-   PM10 partículas respirables se depositan por sedimentación

-   PM1


<a id="orgdfac934"></a>

### Animales

-   Humanos

    Generan Emisiones de Material Particulado
    Generan Calentamiento
    Son afectados por Material Particulado
    Pueden Medir 
    Pueden disminuir o aumentar las emisiones


<a id="org2659cea"></a>

## Operaciones


<a id="org07c2618"></a>

### Emisión


<a id="org1aefb98"></a>

### Medición


<a id="org1842826"></a>

### Respiración


<a id="orgdd69b12"></a>

### Viento


<a id="orgadf7289"></a>

### Calentamiento


<a id="orgbb02fcc"></a>

## Estructuras de control


<a id="org092e4e5"></a>

### Alertas


<a id="orga702d42"></a>

### Estandares (ICA) <http://www.metropol.gov.co/CalidadAire/Paginas/ica.aspx>


<a id="org156d06c"></a>

### PIGECA


<a id="org3667182"></a>

### POECA


<a id="orgb6f7ce0"></a>

# Funciones


<a id="orgbcad9d4"></a>

## Sensor mide el aire


<a id="org5b6500f"></a>

### Técnicas de Medición <http://rama.edomex.gob.mx/tecnicas_medicion>


<a id="org402bd2b"></a>

## Visualizar datos


<a id="orgd763c94"></a>

### Como serie de tiempo:

-   Linea

-   Candles

-   Rastros geolocalizados


<a id="org186ea70"></a>

### Como promedios:

-   Mapa de Calor

-   Estala ICA en Mapa

-   Hexabin

