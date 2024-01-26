# Ejercicio 1. 

## ¿Qué es la virtualización asistida por hardware o HAV (Hardware Assisted Virtualization)? Comparalo con la técnica de virtualización completa y paravirtualización.Comprueba finalmente, si esta característica está activada en tu ordenador físico e indica como lo has averiguado adjuntado capturas del proceso. Cita al menos una fuente bibliográfica.

La virtualizacón completa simula un PC sin capa intemedia. Dentro de un mismo hardware podemos tener varias maquinas virtuales pero estás máquinas no son conscientes de que tienen un capa inferior. No existe un SO como tal que los gestione si no que se gestionan directamente con algun tipo de software, hypervisor de tipo 1 (siguiendo la misma nomenclatura que en en los apuntes). Sin embargo una paravirtualizacion se da cuando necesitamos un SO base con un gestor(aplicacion/programa) que gestiona las maquinas virtuales. Esta máquina virtual cualga de otro sistema operativo.

Primer paso abrimos el panel de control y pinchamos en programas, después programas y funcionalidades. En la parte izquierda encontramos “Activar o desactivar caracteristicas de windows” lo que desplegará una ventana emergente. En ella buscamos la carpeta “Hyper-V” y comprobamos si está activada.
![Alt text](<img/Ejercicio_01/Panel de control.jpg>)
![Alt text](<img/Ejercicio_01/Progrmas y funcionalidades.jpg>)
![Alt text](img/Ejercicio_01/ActivarOuDesactivar.jpg)
![Alt text](img/Ejercicio_01/ComprobarEstadoCarpetaHyperV.jpg)

Fuentes:

- [Diferencias entre Virtualización completa y Paravirtualización en Computación en la nube (huawei.com)](https://forum.huawei.com/enterprise/es/Diferencias-entre-Virtualización-completa-y-Paravirtualización-en-Computación-en-la-nube/thread/667217820116729856-667212887476809728)
- [Virtualización completa y paravirtualización: diferencias - Certitec ](https://certitec.eu/virtualizacion-completa-paravirtualizacion-diferencias/)


# Ejercicio 2. 

## Realiza la siguiente actividad atendiendo a los siguientes puntos:

### 1. Investiga los requisitos mínimos necesarios para instalar Windows 11 e índicalos en la actividad, asi como la webgrafía o bibliografía de donde sacaste la información.
	
Los requisitos minimos para instalar windows 11 son.
- CPU: 1Ghz o más de velocidad con 2 o más núcleos. En la pagina de microsoft podemos acceder a una lista de CPU compatibles con este sistema.
- RAM: 4GB
- Almacenamiento: 64GB.
- Firmware del sistema: UEFI(Interfaz unificada de Firmware Extensible) Es necesario que el dispositivo(placa base + procesador) sea compatible con el arranque seguro1. En algunos casos en necesario actualizar (flashear) el firmware de la placa base, es necesario ver cada caso particular.
- TPM2: Necesaria la versión 2.0. 
- Tarjeta gráfica: Compatible con DirectX 12 o posterior con el controlador WDDM 2.0.
- Pantalla: Al menos de 720p y una diagonal mayor a 9”.
- Otros: Conexion a internet para actualizar el equipo. Si queremos actualizar el equipo a Win11 es necesario que esté ejecutandose Windows10

(El arranque seguro asegura que solo se ejecuten en el arranque software firmado. Esto evita que se ejecute software malicioso.)
(TPM son las siglas de Trusted Plataform Module, es un chip que debe venir instalado en tu placa base.Permite el alamacenamiento seguro y generación de claves criptográficas.)

Fuentes:

-[Windows 11 requisitos del sistema - Soporte técnico de Microsoft ](https://support.microsoft.com/es-es/windows/windows-11-requisitos-del-sistema-86c11283-ea52-4782-9efd-7674389a7ba3)
-[Requisitos de procesador de Windows | Microsoft Learn](https://learn.microsoft.com/es-es/windows-hardware/design/minimum/windows-processor-requirements)
-[Qué es el TPM y cómo comprobar si tu ordenador lo tiene para poder instalar Windows 11 (xataka.com)](https://www.xataka.com/basics/que-tpm-como-comprobar-tu-ordenador-tiene-para-poder-instalar-windows-11)
-[Windows 11 y inicio seguro - Soporte técnico de Microsoft](https://support.microsoft.com/es-es/windows/windows-11-y-inicio-seguro-a8ff1202-c0d9-42f5-940f-843abef64fad)


 ### 2. Crea una máquina virtual que se llame win11_nombre (siendo nombre tu nombre) de acuerdo a los requisitos donde instales este sistema operativo Windows 11. 

 #### 2.1  Documenta el proceso mediante capturas gráficas: tanto el  proceso de creación de la máquina como el de instalación del Sistema operativo.

 Partimos de la base de tener instalado [Oracle VM Virtual Box](https://www.virtualbox.org/wiki/Downloads). Para poder crear una máquina virtual necesitamos descargar el SO, para esto descargaremos la [ISO de Windows 11 desde](https://www.microsoft.com/es-es/software-download/windows11)la página de Microsoft.

 - Una vez abrimos el programa pulsamos en "*Nueva*".
![Alt text](img/Ejercicio_02/000.jpg)
![Alt text](img/Ejercicio_02/001.jpg)
-En la nueva ventana que nos abre, especificaremos el nombre y la ISO que vamos a usar para cargar el sistema operativo en esta máquina virtual. Elegimos la opcion desatendida(Si esta opción está activa el propio software se encarga de instalar por completo el SO si la tenemos desactivada tendremos que realizar nosotros todo el proceso a mano).
![Alt text](img/Ejercicio_02/002.jpg)
-En la siguiente ventana deberemos especificar los requisitos que vamos a destinar a este sistema. Como hemos comprobado anteriormente al menos necesitamos 4GB de memoria RAM y don núcleos 
![Alt text](img/Ejercicio_02/003.jpg)
Creamos un disco duro virtual para la maquina con, al menos 64 GB, 80 GB.
![Alt text](img/Ejercicio_02/004.jpg)
Por ultimo el programa nos enseña un resumen con las especificaciones de nuestra máquina virtual.
![Alt text](img/Ejercicio_02/005.jpg)
-Cuando pulsamos el boton terminar nuestra máquina esta creada y aparecera en la parte izquierda de la ventana. Pulsando el botoón  Iniciar  pondremos nuestra máquina en marcha.
![Alt text](img/Ejercicio_02/006.jpg)
Al pulsar iniciar aparece una nueva ventana, esta será nuestra máquina virtual y como no tenemos instalado windows todavía comenzaremos a instalarlo como si de una máquina completa ser tratase.Elegimos el idioma y pulsamos siguiente.
![Alt text](img/Ejercicio_02/007.jpg)
![Alt text](img/Ejercicio_02/008.jpg)
Aquí debemos introducir nuestra clave de producto, en este caso como es una prueba omitimos este proceso. La clave la introduciriamos en el campo señalado con la flecha pero nosotros pulsaremos en el area del circulo sobre *No tengo clave del producto.*
![Alt text](img/Ejercicio_02/009.jpg)
![Alt text](img/Ejercicio_02/010.jpg)
![Alt text](img/Ejercicio_02/011.jpg)
![Alt text](img/Ejercicio_02/012.jpg)
![Alt text](img/Ejercicio_02/013.jpg)
![Alt text](img/Ejercicio_02/014.jpg)
![Alt text](img/Ejercicio_02/015.jpg)
![Alt text](img/Ejercicio_02/016.jpg)
![Alt text](img/Ejercicio_02/017.jpg)
![Alt text](img/Ejercicio_02/018.jpg)
![Alt text](img/Ejercicio_02/019.jpg)
![Alt text](img/Ejercicio_02/020.jpg)
![Alt text](img/Ejercicio_02/021.jpg)
![Alt text](img/Ejercicio_02/022.jpg)
![Alt text](img/Ejercicio_02/023.jpg)
![Alt text](img/Ejercicio_02/024.jpg)
![Alt text](img/Ejercicio_02/025.jpg)
![Alt text](img/Ejercicio_02/026.jpg)
![Alt text](img/Ejercicio_02/027.jpg)
![Alt text](img/Ejercicio_02/028.jpg)
![Alt text](img/Ejercicio_02/029.jpg)
![Alt text](img/Ejercicio_02/030.jpg)
![Alt text](img/Ejercicio_02/031.jpg)
![Alt text](img/Ejercicio_02/032.jpg)
![Alt text](img/Ejercicio_02/033.jpg)
![Alt text](img/Ejercicio_02/034.jpg)
![Alt text](img/Ejercicio_02/035.jpg)
![Alt text](img/Ejercicio_02/036.jpg)




