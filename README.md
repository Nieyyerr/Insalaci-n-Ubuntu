# Instalacion-Ubuntu
## ¿Que es Ubuntu?
  es una distribución Linux basada en Debian GNU/Linux, que incluye principalmente software libre y de código abierto. Puede utilizarse en ordenadores y servidores. Está orientado al usuario promedio, con un fuerte enfoque en la facilidad de uso y en mejorar la experiencia del usuario. Está compuesto de múltiple software normalmente distribuido bajo una licencia libre o de código abierto. Estadísticas web sugieren que la cuota de mercado de Ubuntu dentro de las distribuciones Linux es, aproximadamente, del 52 % y con una tendencia a aumentar como servidor web.5
  # Procesos de instalacion
 
  - Descargaremos VirtualBox para el sistema operativo de nuestro ordenador.
  ## Configuración de Virtual Box
 
  - Arrancamos VirtualBox y hacemos click en "Nueva"
 
  - Escribimos el nombre de la máquina virtual, en nuestro caso "ubuntu"
 
  ![inicio2](./inicio2.png)
 
  - Debemos indicarle la memoria principal (RAM) que tendrá nuestra máquina virtual. En este caso Ubuntu recomienda escoger un tamaño mínimo de 2048MB
 
  ![inicio3](./inicio3.png)
   
  - Creamos un disco duro virtual, que se creara como un archivo, y que tendrá un tamaño de 25 GB
   
   ![inicio4](./inicio4.png)
   
  - Elegimos del tipo de disco duro virtual del tipo VDI
   
   ![inicio5](./inicio5.png)
   
  - Le indicamos que el fichero del disco duro virtual crezca dinámicamente, a medida que necesitemos más espacio
   
   ![inicio61](./inicio61.png)
 
  - Configuramos el tamaño del disco duro virtual 25GB, ya que es el tamaño recomendado en la instalación de Ubuntu 22.04
   
   ![inicio62](./inicio62.png)
   
  - Ya tenemos creada la máquina virtual, solo nos falta introducir el disco virtual del sistema operativo
 
  ![inicio7](./inicio7.png)
 
  - Nos descargamos previamente el archivo ISO de la sitribución LInux que queremos. En nuestro caso hemos elegido la distribución en su versión 22.04
 
  ![ISO](./ISO.png)
 
  - El siguiente paso es "montar" la ISO en el lector virtual de la máquina virtual. Para ello hacemos click en "Configurar y posteriormente vamos a la sección "almacenamiento". Una vez abierto el "almacenamiento" pulsaremos donde pone vacío, justo debajo de "Controlador: IDE", pulsaremos en el disco azul de la derecha del todo y haremos click en "Seleccionar un archivo de disco". Buscaremos el archivo de Ubuntu que nos hemos descargado anteriormente.
 
  ![1](./1.png)

  - Por último le damos a "Iniciar" en la máquina virtual
 
 
  ## Instalación Ubuntu
  - Al darle a "Iniciar", obtendremos esta pantalla:
 
  Pulsaremos en probarlo y más adelante lo instalaremos. Y elegiremos uno de los idiomas.
 
  - Elegimos el idioma y hacemos click en "Instalar Ubuntu"
 
  ![cap 4](./cap_4.png)
 
 
  - Elegimos la distribución del teclado
   ![cap 5](./cap5.png)
   
  - Elegimos el tipo de instalación y si actualizaremos o instalaremos sofware de terceros
   ![V1](./V1.png)
   
  - Elegimos borrar todo el disco y que se instale Ubuntu como único sistema operativo
   ![V2](./V2.png)
   
   - Igresamos nuestros datos personales y damos a "continuar"
   
   
   - Una vez acabados todos los pasos, comenzará la instalación.
     ![v3](./v3.png)
   
# Referencias
  "UBUNTU". Wikipedia.Disponile en: https://es.wikipedia.org/wiki/Ubuntu (Accedido: 6 de marzo, 2023)
  ![Screenshot_20230327_101741](https://user-images.githubusercontent.com/122264831/227883220-d1cecf92-0d83-4731-a0bf-2d3f90885c0e.png)

  ## Instalación Software![Uploading Screenshot_20230327_101741.png…]()

  
  #Terminal
  
 #sudo apt update
 
 ##sudo apt get-install audacity!
 [Screenshot_20230329_094212](https://user-images.githubusercontent.com/122264831/228462152-d667a64d-03ac-4a4e-965f-54cb53b008eb.png)
 
 /h![VirtualBox_Ubuntu 3_30_03_2023_13_28_50 AUDACITY](https://user-images.githubusercontent.com/122264831/228822458-6f585b13-daa3-4db2-b806-6247cb08604c.png)
ome/marnie/Pictures/Screenshot_20230329_094321.png

Instalación de Wordpress con EasyPanel
Objetivos

Instalar y documentar el proceso de instalación de Wordpress mediante Easypanel en nuestra máquian virtual.
Pasos

1. Realiza la instalación de EasyPanel en la máquina virtual de Ubuntu y haz una captura del panel de control en la URL http://localhost:3000

sudo su

cu![VirtualBox_Ubuntu 3_30_03_2023_13_27_06](https://user-images.githubusercontent.com/122264831/228822793-6f626964-a7ab-439e-8a12-2a5e892cf5c1.png)
rl -sSL https://get.easypanel.io | sh
 
 
 
