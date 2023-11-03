# Unidad didáctica 01. Hardware de un sistema informático
## Módulo: Sistemas informáticos
### Tarea 5. Hardware de un sistema informático

- **Nombre:** MATEO 
- **Apellido1:** CARBALLO 
- **Apellido 2:** ALONSO

#### Ejercicio 1. En clase hemos visto algunos Factores de forma de las placas base, pero hay más. Investiga sobre el factor de forma BTX (Evolución, año lanzamiento, dimensiones, esquema gráfico, número de puertos de expansión... ):

El formato BTX (Balanced Technology Extended) es un factor de forma que evolucionó desde el ATX por Intel. Este formato soluciona problemas como la refrigeración de los procesadores al proporcionar un camino más recto y mejorar el flujo de aire a través de los componentes.

- Fue presentado en el año 2004.
- La compatibilidad entre las placas de formato ATX y BTX es casi nula, salvo en la fuente de alimentación que permite usar una fuente ATX en una placa BTX.
- El desarrollo de este formato se detuvo en el año 2006.

<img src=img/Ejercicio1_1.png alt="Imagen_1_1" width="500">
<img src=img/Ejercicio1_2.png alt="Imagen_1_2" width="500">
<img src=img/Ejercicio1_3.png alt="Imagen_1_3" width="500">
<img src=img/Ejercicio1_4.png alt="Imagen_1_4" width="500">
<img src=img/Ejercicio1_5.png alt="Imagen_1_5" width="500">

**Fuentes**:
- [BTX (electrónica) - Wikipedia](https://es.wikipedia.org/wiki/BTX_(electr%C3%B3nica))
- [Tipos de placas base: AT, ATX, LPX, BTX, Micro ATX y Mini ITX](https://www.profesionalreview.com/2018/08/22/tipos-de-placas-base-at-atx-lpx-btx-micro-atx-y-mini-itx/)
- [Características técnicas de las Motherboards con tecnología BTX](https://studylib.es/doc/3272409/caracter%C3%ADsticas-t%C3%A9cnicas-de-las-motherboards-con-tecnolog%C3%AD...)
- [Motherboard Formato BTX | PDF](https://www.scribd.com/document/306504702/Motherboard-Formato-BTX)

#### Ejercicio 2. Busca en internet los diferentes tipos de zócalos: PGA, ZIF, BGA, Slot, LGA y haz una breve definición y acompaña esta con una fotografía . Finalmente indica : ¿En qué tipo de zócalo se instalaban los antiguos procesadores Pentium II o Pentium III?:

El zócalo de la CPU (Socket) es un sistema electromecánico de soporte de conexión eléctrica instalado en la placa base. Existen varios tipos de zócalos, como LGA, PGA, ZIF, BGA y Slot.

| Zócalo | Definición | Fotografía |
| ------ | ---------- | ---------- |
| LGA (Land Grid Array) | Contiene los pines en lugar de tenerlos en el procesador. |<img src=img/Ejercicio2_1.png alt="Imagen_1_1" width="500"> |
| PGA (Pin Grid Array) | Caracterizado por su forma cuadrada o rectangular. Los pines están alineados. | <img src=img/Ejercicio2_2.png alt="Imagen_1_1" width="500"> |
| ZIF (Zero Insertion Force) | Actúa como un seguro para que no ejerza presión al instalar o extraer el procesador. | <img src=img/Ejercicio2_3.png alt="Imagen_1_1" width="500"> |
| BGA (Ball Grid Array) | Se encuentra en procesadores unidos permanentemente a la placa base. | <img src=img/Ejercicio2_4_1.png alt="Imagen_1_1" width="500"> <img src=img/Ejercicio2_4_2.png alt="Imagen_2_4_2" width="500">|
| Slot A | Usado en los primeros procesadores de AMD. | <img src=img/Ejercicio2_5_1.png alt="Imagen_2_5_1" width="500"><img src=img/Ejercicio2_5_2.png alt="Imagen_2_5_1" width="500">|

Los procesadores Pentium II o Pentium III solían instalarse en zócalos Slot.

**Fuentes**:
- [Zócalo de CPU - Wikipedia](https://es.wikipedia.org/wiki/Z%C3%B3calo_de_CPU)
- [Tipos de socket en placa base: todos los usados por Intel y AMD](https://www.profesionalreview.com/2018/08/23/tipos-de-socket-en-placa-base...)
- [Slot A - Wikipedia](https://es.wikipedia.org/wiki/Slot_A)
- [AMD Athlon - Wikipedia](https://es.wikipedia.org/wiki/AMD_Athlon)

#### Ejercicio 3. Visualiza el siguiente vídeo y contesta: 

**Respuestas**:
- ¿Qué tipo de zócalo usan los procesadores Intel? ```LGA```
- ¿Qué significan el número que va al lado del modelo de socket? ```Representa el número de pines del procesador (ejemplo: LGA 1151 tiene 1151 pines).```
- ¿Son compatibles los procesadores con los zócalos Intel de manera retrospectiva? ```No, debido a diferencias en el número de pines entre generaciones.```
- ¿Qué tipo de zócalo usan los procesadores AMD? ```PGA, con pines en el procesador.```
- ¿Son compatibles los procesadores AMD con los zócalos de manera retrospectiva? ```Depende del BIOS de la placa, en algunos casos sí, en otros no. Si lo permite siempre es montar un procesador nuevo en un placa anterior.```

**Fuente**: pccomponentes

#### Ejercicio 4. Entra en la página web en.wikichip.org y contesta:

- ¿A qué generación pertenece un procesador i5-6200U? ```Pertenece a la sexta generación de procesadores llamada SKYLAKE.```
- ¿Qué zócalo emplea un procesador Intel i7 de la 7th generación? ```Utilizan el zócalo LGA 1151.```
- ¿Qué zócalo emplea un procesador AMD Ryzen 7? ```Los procesadores Ryzen 7 utilizan el socket AM4.```
- ¿A qué generación corresponde la denominada "Rocket Lake"? ```Corresponde a la undécima generación de procesadores de Intel.```
- ¿En qué año se lanzó la 5ª Generación de procesadores Intel y cuál es su nombre en clave? ```La 5ª Generación de procesadores Intel, conocida como "Broadwell," se lanzó en junio de 2015.```
- Dentro de las microarquitecturas de AMD, ¿cuál es la sucesora de Excavator y en qué año apareció? ```La sucesora de Excavator es Zen, que apareció en 2017.```

**Fuentes**:
- [Historia y evolución de los procesadores Intel Core](enlace_historia_procesadores_intel)
- [Rocket Lake - Wikipedia](https://es.wikipedia.org/wiki/Rocket_Lake)

#### Ejercicio 5. Proceso POST

**Video 1**:
- ¿Dónde están almacenadas las instrucciones de POST? ```Las instrucciones POST (The Power On Self Test) están almacenadas en la BIOS (Basic Input Output System) una memoria ROM, que guarda sus valores aun perdiendo tension y una vez escrita no puede volver a escribirse.```
- Según el vídeo, ¿qué es lo primero que chequea el proceso POST? ```La primera comprobacion que hace es sobre la cpu, memoria RAM y tarjeta grafica.```
- ¿Cuáles son las teclas que normalmente te permiten entrar en el programa de configuración de la BIOS? ```Las teclas F2 y F11 son las mas comunes para entrar a los ajustes de la BIOS```

**Video 2**:
- ¿Dónde podemos buscar información sobre el significado de cada combinación de pitidos POST? ```En el manual del fabricante de la placa base.```
- ¿En qué tipo de memoria se almacena el código de la BIOS? ```En una memoria ROM.```
- ¿Dónde se guardan las configuraciones de usuario como las configuraciones de hardware, la secuencia de arranque o la fecha y hora del sistema? ```La configuracion que hagamos hecho sobre la BIOS(ajustes personales diferentes a los que tiene por defecto) se guardan en un chip llamado CMOS una memoria volatil(que necesita energia para guardar sus datos). Cuando se apaga el PC se alamacena gracias a una bateria para esta tarea(bateria CMOS)```
- ¿Se pueden perder los datos de esas configuraciones por falta de alimentación constante? ```Si, las coniguraciones personalizadas se pierden puesto que se alamcenan en una memoria volatil. Si por ejemplo metemos la pata configurando algo en nuestro pc y no nos arranca una opcion seria llevar todo a fabrica desconectando esta bateria y volviendo a colocarla. Si hacemos esto perderiamos tambien la fecha y hora actualizadas.```

**Artículo 1**:
- En una placa basada en IBM BIOS, ¿qué significa un pitido continuo? ```Si la placa emite un pitido continuo puede deberse a varios motivos.
    • Sin alimentacion en alguno de los componentes.
    • Algun error en la tarjeta de memoria.
    • Un corto en algun lugar de la placa.```
- ¿Qué Beep Code tiene un problema con el teclado la BIOS de IBM? ```Tres pitidos largos.```
- ¿Con qué Beep Code se indica un problema en la tarjeta gráfica en las BIOS AMI? ```Un pitido largo seguido de dos pitidos cortos.```
- En las BIOS Phoenix, ¿qué significa 1 beep (pausa) - 1 beep (pausa) - 3 beeps? ```Indica una placa base defectuosa o un error de lectura/escritura en el CMOS.```

**Fuente**: [Códigos de sonido del BIOS: AMI y Phoenix](https://es.stealthsettings.com/bios-bip-codes-ami-phoenix.html)

#### Ejercicio 6. Contesta a las siguientes preguntas después de leer el siguiente artículo:
[Enlace Articulo](https://www.profesionalreview.com/2020/06/14/2-o-4-modulos-de-memoria-ram/)

En relación a las características de los módulos de memoria, ¿qué requisitos deben cumplir para que pueda emplearse la tecnología Dual-Channel o Quad-Channel?
```Para sacar todo el provecho a esta funcionalidad los modulos deben de ser identicos en prestaciones(capacidad, velocidad de reloj) y tener una placa base que lo soporte.```
¿Para qué tipos de sistema informático está pensado el Quad-Channel? 
```El quad channel se usa en servidores y workstation. Cualquier uso personal esta sobredimensionado.```
¿Y el Dual-Channel? 
```Para uso domestico. Para cualquier proposito individual como ofimatica, navegacion, juegos, etc. Para el uso promedio de cualquier persona es suficiente.```
Dentro de Intel, ¿qué modelo de socket soporta el Quad-Channel?
```Los dedicados a servidores LGA 2066```
Dentro de AMD ¿qué modelo de socket soporta el Quad-Channel? 
```AMD tiene procesadores en su gama de CPU para servidores que soportan 8 y 12 canales. Estas se denominan ThreadRipper y Epyc respectivamente.```
**Fuentes**:
- [Especificaciones de procesadores | AMD](enlace_amd_procesadores)
- [AMD EPYC™ 9754 | AMD](enlace_amd_epyc)
- [AMD Ryzen™ Threadripper™ PRO 7995WX | AMD](enlace_threadripper)

#### Ejercicio 7. Vete a la página oficial de MSI y busca la placa Creator X299.

- ¿Soporta la tecnología Quad-Channel? Sí, soporta Quad-Channel con memorias RAM DDR4 de hasta 4266 MHz de frecuencia de reloj. ```Si la soporta. En las especificaciones del fabricante podemos leer claramente que permite quad channel con memorias RAM DDR4 de hasta 4266 Mhz de frecuencia de reloj.```
- ¿Cuál es el máximo de memoria que puede alcanzar en tecnología Dual-Channel? Hasta 256 GB en Quad-Channel, lo que implica que cada módulo de memoria debe ser de 64 GB. ```En las especificaciones del fabricante podemos leer que el maximo de memoria son 256 en quad channel. Esto implica que cada modulo de memoria debe de ser de 64GB. Con 64 Gb por cada memoria y dos memorias conectadas nuestras RAM seria de 128GB.```
- Si tengo 4 módulos de memoria idénticos, ¿cómo los colocaría en los slots? Consulta el manual del fabricante para obtener el orden correcto de llenado de los slots.```Esta es una captura del propio manual del fabricante e indica que orden de llenado de los slots de memoria RAM deberemos seguir para cada una de las configuraciones. Lo que he hecho ha sido entrar en la pagina del fabricante buscar el producto. Y buscar sus manuales en formato PDF y desde el indice ir a la seccion de los slots para memoria RAM.```
- Si solo tienes un módulo de memoria, ¿en qué slot debes instalarlo? 
```Como nos indica el fabricante La primera posicion que debemos ocupar es la C1.```

<img src=img/Ejercicio7.png alt="Imagen7" width="500">

**Fuente**: [Manual de la placa base MSI Creator X299](enlace_manual_msi)

#### Ejercicio 8. Accede a la página del fabricante de placas MSI y localiza la motherboard Gigabyte GA-H97-HD3 rev 1.0. Con la información disponible resuelve las siguientes cuestiones:

Placa base: 
- ¿Qué factor de forma tiene la placa base?```Debido a su forma rectangular y a que tiene varios puertos para PCI-E el formato de forma es ATX.```

Procesador:
- Socket: 
```LGA, los pines esta en el socket, para procesadores del fabricante INTEL.```
- ¿Con qué procesadores es compatible la placa base? (Basta con que te refieras a la microarquitectura y/o generación)
```A la quinta generacion de Intel ```

Memoria:
- ¿Qué módulos de memoria soporta la placa?
```Soporta hasta 4 modulos DDR3 con un total de 32 GB (4x8GB)```
- ¿Qué cantidad máxima de memoria soporta?
```32GB ```
- ¿Dispone de tecnología multicanal?
```Si, puede trabajar en Dual-Channel.```
- ¿Qué chipset monta la placa base?
```H97```
- ¿De cuántas ranuras de expansión dispone y de qué tipo?

```-1 PCI Express x16 velocidad x16 (PCIE 3.0) esta ranura es de tipo x16 (la mas grande) y funciona aprovechando todo el ancho de banda. Usando tegnologia PCIE 3.0 .```

```1 PCI Express x16 velocidad x4. Esta ranura tiene la misma forma que la anterior pero comparte el ancho de banda con otras ranunas de expansion, las x1. Si instalamos una tarjeta en esta ranura las no podremos instalarlas en las x1. Estas ranuras quedarian inutilizadas. ```

```2 PCI Express x1. Estas ranuras usan la tecnologia PCIE 2.0. Normalmente se usan para conectar tarjetas de red, wifi, etc.```

```2 PCI La tecnologia mas antigua de todas anterior a la PCI E. ```

- ¿Qué otros conectores internos puedes identificar?

```Conector para USB, conectores de audio, conectores para discos duros SATA, conectores de alimentacion(ventiladores, placa, cpu), conectorr de USB 3.0, varios conectores para luces frontales y botones frontales.```

¿Qué conectores externos puedes encontrar?

```2 puertos usb, conector PS2(raton teclado), vga, DVI-D Dual link, HDMI, 4 puestos usb 3.0, rj45, conectores jack 3,5 para audio y microfono.```

¿Cómo descargarías los drivers para la placa base?
```Usando cualquier buscador. Introducimos el nombre de la placa en el buscador y pinchando el enlace de la pagina web del frabicante. Suelen tenerlo en formato PDF para descargar gratuitamente.```

[Manual de la placa anterior](https://www.gigabyte.com/latam/Motherboard/GA-H97-HD3-rev-10/support#support-manual)

[Fuente](https://www.gigabyte.com/Motherboard/GA-H97-HD3-rev-10/sp#sp)

#### Ejercicio 9. Busca información en internet de los siguientes conectores. Adjunta una fotografía del conector en la placa base o en el frontal del pc, otra foto del cable que necesita (si no necesitase cable escribe no existe)y haz una breve descripción de estos indicando a qué dispositivos podemos conectar en ellos :


| Conector              | Fotografía del Conector | Fotografía del Cable | Uso                                     |
|-----------------------|-------------------------|----------------------|-----------------------------------------|
| Puerto HDMI           | [Imagen HDMI](enlace_imagen_hdmi)      | No existe            | Transmisión de Audio y Video en alta definición. PANTALLAS                  |
| Conector LAN RJ45     | [Imagen RJ45](enlace_imagen_rj45)        | No existe            | Interconexión de ordenadores en red. PC, impresora, TV, etc.                    |
| Conector DVI          | [Imagen DVI](enlace_imagen_dvi)         | No existe            | Transmite video digital desde el PC al monitor. MONITOR                   |
| Conector corriente ATX 4 pin | [Imagen ATX 4-pin](enlace_imagen_atx_4pin) | No existe        | Alimentación de la CPU. CPU                          |
| Conector SATA         | [Imagen SATA](enlace_imagen_sata)       | [Imagen Cable SATA](enlace_imagen_cable_sata) | Conecta discos duros a la placa. HDD, SSD            |
| Conector IDE          | [Imagen IDE](enlace_imagen_ide)         | [Imagen Cable IDE](enlace_imagen_cable_ide) | Conecta unidades ópticas a la placa. LECTORES, GRABADORES DE CD Y DVD |
| Conector PCI          | [Imagen PCI](enlace_imagen_pci)         | No existe            | Ranura de expansión para conectar tarjetas. TARJETAS DE SONIDO, TARJETAS DE RED, TARJETAS WIFI |
| Conector PCI Express x16 | [Imagen PCI-E x16](enlace_imagen_pci_express_x16) | No existe   | Ranura de expansión de alta velocidad para tarjeta de video. TARJETA DE VIDEO (GRÁFICA) |
| Conector DDR          | [Imagen DDR](enlace_imagen_ddr)         | No existe            | Conecta módulos de memoria RAM con el procesador. MEMORIAS RAM           |


