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
3.5 Crear los directorios para montar los volumenes logicos
![alt text](image-8.png)
3.6 Verificamos que los volumenes logicos se hayan creado correctamente 
![alt text](image-9.png)
3.7 Configurar para que los volumenes logicos se monten automaticamente al iniciar el sistema
![alt text](image-10.png)



4. Creacion de images Dockerfile

4.1 Crear los directorios y Archivos Dockerfile correspondientes
![alt text](image-11.png)
4.2 Procedemos a configurar los Dockerfile con sus respectivas imagenes 

4.2.1
Apache:
![alt text](image-13.png)
Creacion de la imagen apache : 
![alt text](image-14.png)

4.2.2
MySQL:
![alt text](image-17.png)
Creacion de la imagen MySQL :
![alt text](image-16.png)

4.2.3
Nginx:
![alt text](image-18.png)
Creacion de la imagen Nginx :
![alt text](image-19.png)

4.3 Verificamos que las imagenes se hayan creado correctamente
![alt text](image-20.png)


5. Montar las imagenes creadas en los respectivos volumenes logicos

5.1 
Apache: 
![alt text](image-21.png)

5.2
MySQL:
![alt text](image-23.png)

5.3 
Nginx:
![alt text](image-22.png)


