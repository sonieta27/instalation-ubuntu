# Instalación de Ubuntu

# Qué es ubuntu?

Ubuntu es una distribución Linux basada en Debian GNU/Linux, que incluye principalmente software libre y de código abierto.
Puede utilizarse en ordenadores y servidores. Está orientado al usuario promedio, con un fuerte enfoque en la facilidad de uso y en mejorar la experiencia del usuario. Está compuesto de múltiple software normalmente distribuido bajo una licencia libre o de código abierto. Estadísticas web sugieren que la cuota de mercado de Ubuntu dentro de las distribuciones Linux es, aproximadamente, del 52 %,3​4​ y con una tendencia a aumentar como servidor web.

# PROCESO DE INSTALACIÓN

## Instalación de Virtualbox
Descargaremos [Virtualbox](https://www.virtualbox.org/) para el sistema operativo de nuestro ordenador.
## Configuración Virtualbox
Arrancamos Virtualbox y hacemos click en "Nueva": ![](1virtualbox.png)

A continuaicón escribimos el nombre de la máquina virtual, en nuestro caso "Ubuntu". Vemos que se selecciona automáticamente el tipo de sistema a "Linux" y la versión "Ubuntu 64-bit".
# Aqui va la otra imagen que no tengo y falta por hacer:

Configuramos el tamaño de memoria para máquina virtual. Para Ubuntu 22.04 se recomiendan 4GB (4096MB):
# También falta esta imagen

Creamos un disco duro virtual, que se creará como un archivo, y que tendrá un tamaño de 25GB:
![](virtual2.png)

Ya tenemos creada la máquina virtual, solo nos falta introducir el disco virtual del sistema operativo:
# Falta imagen
Nos descargamos previamente el archivo ISO de la distribución Linux que queramos. En nuestro caso hemos elegido la distribución [Ubuntu](https://ubuntu.com/), en su versión 22.04.

El siguiente paso es "montar" la ISO en el lector virtual de la máquinavirtual. Para ello hacemos click en "Configurar" y posteriormente vamos a la sección de "Almacenamiento":
# Falta otra imagen

Hacemos click en "Vacío" dentro del árbol "Controlador IDE", y posteriormente elegimos el archivo ISO desde el icono de "Unidad óptica":

# Otra imagen falta aquí






## Instalación de Ubuntu
vemos la pantalla de Grub y elegimos la opción "Try or Install Ubuntu", y le damos a la tecla "Enter":
![](https://user-images.githubusercontent.com/122264807/224402757-287c1c5f-37e2-4ef4-b22d-2da1107840f4.png)
ELegimos el idioma y hacemos click en "Instalar Ubuntu":
![](https://user-images.githubusercontent.com/122264807/224403161-3de986c8-832b-4afd-8fb5-f36196697682.png)

Elegimos la distribución del teclado:
![](https://user-images.githubusercontent.com/122264807/224403413-bfe8ab27-026f-4c2d-9886-f77b068652ad.png)

Elegimos el tipo de instalación y si actualizaremos o instalaremos software de terceros:
![](https://user-images.githubusercontent.com/122264807/224403730-a45db4cd-83e0-4ce9-b464-d3fd717ef23b.png)
![](https://user-images.githubusercontent.com/122264807/224403916-4ff375fc-4317-4ed3-91f5-dd8c0daa5c77.png)

Elegimos borrar todo el disco y que se instale Ubuntu como único sistema operativo:
![](https://user-images.githubusercontent.com/122264807/224404089-6a54e039-a5a7-46e9-a9a5-4502ae312ae2.png)

































# Referencias 
- "Ubuntu" Wikipedia. DIsponible en: [https://es.wikipedia.org/wiki/Ubuntu](https://es.wikipedia.org/wiki/Ubuntu) (Accedido: 10 de marzo, 2023)
