# ACERCA DE GHOST
**Ghost** es un Sistema Operativo programado desde cero en los lenguajes C++ y Ensamblador para la plataforma Intel x86 . 
Esta concebido en torno a un nucleo que tiene muchas cualidades de microkernel.

## Estado
Hemos liberado la version 0.5.4 el 17 de Noviembre del 2016. 

Hemos reescrito mucho codigo desde la ultima revision y hemos corregido muchos bugs. 
EL client-canvas esta terminado y se le da uso en la linea de comandos y en el escritorio. 

Hemos iniciado la implementacion de una linea de comandos compatible con VT100 y con una consola propia, denominada `gosh`. Hemos implementado varias caracteristicas al servidor de ventanas, las cuales incluyen transferencia de eventos al cliente, evento de salida en la ventana principal cuando cerramos un programa y eliminacion de componentes cuando sus procesos mueren, entre otros.

Igualmente, hemos agregado un interprete de JavaScript (`js`) con fundamento en el motor 
Duktape JS.

![Current screenshot of Duktape running](https://ghostkernel.org/files/ghost-0.5.3-jsconsole.png)

## Caracteristicas
- Lines de comandos e interfaz grafica
- Ejecucion en multiprocesador
- Controladores para teclado y mouse PS/2 keyboard, controladores de video VESA
- Kernel escrito desde cero
- Patched GCC, OS specific toolchain
- Implementacion propia de la biblioteca libc 
- Port de la biblioteca libstdc++ 
- Extensive kernel API library (libapi)
- Biblioteca de espacio de usuario en el lenguaje C++ (libuser)
- Sistema de Archivos en espacio de usuario habilitado
- Ejecucion de binarios ELF 
- Diveros mecanismos IPC: tuberias, senales, mensajes, memoria compartida
- Serial COM1 kernel logging
- Virtual 8086 for BIOS calls

## Documentation
See the `documentation` folder for documentation. It contains information
about the technical design as well as building instructions.

## Contact
If you want to get in contact, contribute to the project or have any questions,
feel free to contact me at:

	lokoxe@gmail.com
	
-Max Schlüssel
