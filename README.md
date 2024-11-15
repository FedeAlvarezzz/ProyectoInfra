# ProyectoInfra
Proyecto en el cual vamos a hacer uso de contenedores y maquina virtual


Bitácora de Proyecto Final

1. Creación de discos duros

 En este proceso, configuraremos un total de 9 discos duros para una máquina virtual. Se crearán 6 discos de 6 GB y 3 discos de 3 GB. Accederemos a la configuración de la máquina, seleccionaremos la opción para agregar discos y definiremos el tamaño de cada uno según los requisitos. Finalmente, asignaremos cada disco a la máquina virtual para que estén listos para su uso.
 ![alt text](image.png)


 2. Creación de RAIDS

2.1 Primero se verifica que los discos se hayan creado correctamente con el comando lsblk
 ![alt text](image-1.png)
2.2 Procedemos a crear los RAIDS requeridos para el proyecto
![alt text](image-2.png)
2.3 verificamos que los RAIDS se hayan creado correctamente
![alt text](image-3.png)




3. Creacion de Volumenes Lógicos

3.1 Creacion de volumenes físicos (pv)
![alt text](image-4.png)
3.2 Creacion de Grupo de Volumenes (VG)
![alt text](image-5.png)
3.3 Creacion de Volumenes Logicos (lv)
![alt text](image-6.png)
3.4 Formateamos los volumenes logicos con el tipo de archivo ext4
![alt text](image-7.png)