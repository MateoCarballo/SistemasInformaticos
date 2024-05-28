# Unidad didáctica 03. Introducción a los sistemas en red
## Módulo: Sistemas informáticos

### Tarea 1. Componentes de una red

En clase hemos visto diferentes componentes y medios de transmisión, pero hay algunos aspectos que únicamente se abordaron por encima. A continuación, realiza una investigación en Internet sobre los siguientes temas:

#### 1) Switch
- **¿Qué es un switch PoE?**

    Las siglas de switch PoE vienen del Inglés Power-over-Ethernet, que traucido sería algo como alimentado a través de Ethernet. La diferencia y principal ventaja respecto a un switch convencional es que además de transmitir datos proporciona alimentacion electrica a los aparatos que estén conectados a él. Podemos diferenciarlos entre activos y pasivos. Los primeros controlaran la tension de salida de la PSE (Fuente de alimentación). Los segundos darán una tensión constante.

    Existen 4 estándares de conformidad:

    1.PoE

    2.PoE+

    3.PoE++ y UPoE

    ![alt text](img/Estandares_PoE_Tabla.png)

    **TP-Link TL-SG1005LP es un switch con 5 puertos Gigabit Ethernet, 4 de ellos PoE+, admite alimentación de hasta 30W por cada puerto PoE.**
    ![alt text](img/switch_PoE.png)
- **¿Cuáles son sus ventajas y sus inconvenientes?**

    Desde la popularización del internet de las cosas (IoT) este tipos de switches se han hecho muy populares. La mayor ventaja de estos dispositivos respecto a un switch convencional es que la instalacion es más simple, necesitamos menos cables para implementar la misma instalación, y esto implica un menor coste. Mejora considerablemente la gestion de cables y permite una mayor flexibilidad ante futuras modificaciones, puesto que no necesitamos un punto de conexión a red electrica cerca. 

    Una gran desventaja es que dependemos de la fuente de corriente, si por algun motivo se avería todos los dispositivos conectados quedarían inutilizados. Los dispositivos tienen un limite de distancia de trabajo de unos 100 metros.

- **¿Qué son los puertos SFP y para qué se utilizan?**

    Los puertos SFP (Small Form-Factor Pluggable) también conocidos como GBIC (Gigabit Interface Converter) son módulos conectables en caliente, sin apagar el dispositivo que los contiene, que se utilizan para transferir datos entre switches y otros dispositivos conectados. Se utilizan porque permiten elegir entre diferentes modulos para poder elegir entre distintos medios y velocidades de conexión.

    Ha habido 4 partes/tecnologías remarcables que son:

    - **SFP** , que es una version mejorada del GBIC con velocidades entre 100Mbps y 4Gbits/s.
    - **SFP+** velocidades de hasta 10Gbitps.
    - **SFP28** mismo factor de forma que el SFP+ pero velocidades hasta 25Gbitps.
    - **QSFP+** 4 canales simultaneos hasta 10Gbitps cada uno.
    - **QSFP28** 4 canales simultaneos hasta 25Gbitps cada uno.

    ![alt text](/img/evolucion_sfp.jpg)
    ![https://www.fibermall.com/es/sale-421317-1000baselx-sfp-1310nm-10km.htm#](img/modulo_SFP.png)
    ![alt text](img/modulo_QSFP.png)
    ![alt text](img/switch_puertos_QSFP28.png)
- **Fuentes**

    - [Switch PoE](https://www.vadavo.com/blog/switch-poe-que-es-y-que-tipos-hay/)
    - [Puertos y conectores SFP](https://www.fibermall.com/es/blog/what-are-the-sfp-and-qsfp-ports-of-switches.htm#:~:text=Los%20puertos%20SFP%20permiten%20a,de%20alta%20velocidad%20entre%20servidores)
    - [Tecnolgía FSP](https://community.fs.com/es/article/sfp-vs-sfp-vs-sf-p28-vs-qsfp-vs-qsf-p28-what-are-the-differences.html)

#### 2) Vimos lo que es un punto de acceso. Ahora, investiga:
- **¿Qué es un repetidor y para qué se utiliza?**
- **¿En qué se diferencia de un punto de acceso?**

#### 3) Esquema de Red Doméstica:
Utilizando los dispositivos intermedios vistos en clase, elabora un esquema sencillo de la red de tu casa. No es necesario que utilices las mismas imágenes o colores que el ejemplo proporcionado, pero debes incluir toda la información relevante en el esquema.

![alt text](img/Esquema_red_domestica.png)

La direccion que necesitamos introducir en el navegador para acceder al router es la ip local que aparece en el esquema, sino tambien es muy cómun que por defecto tenga la direccion 192.168.0.1, esta direccion podemos cambiarla desde el mismo router al acceder a el.

Desde el router podemos asignar una direccion IP fija en funcion de la direccion MAC, unica para cada tarjeta de red. En realidad este router tiene varias frecuencias Wi-Fi de trabajo 2,4 GHz y 5GHz. La de mayor frecuencia es más rapida pero como parte negativa tiene menor alcance y le afectan más los obstaculos la otra es algo mas lenta. inapreciable para uso cotidiano, pero alcanza mejores distancias de funcionamiento y es mas estable si existen obstaculos entre el punto de acceso y el dispositivo que se conecta.

#### 4) Cable de Par Trenzado:
- **¿Qué tipos hay y en qué se diferencian?**
- **Existen diferentes categorías de cables de par trenzado. ¿Cuáles son? ¿Cuáles son sus características?**


### Formato de Entrega
El documento debe entregarse en formato .PDF.

### Evaluación
No hay una extensión mínima, pero se valorarán aspectos como la presentación de los datos, el formato, el uso de imágenes explicativas, la correcta citación de fuentes y la inclusión de información de interés.
