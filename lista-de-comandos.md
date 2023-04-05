
   
   # Listados de comandos

   ### COMANDOS
 
- **Comando touch:** Se utiliza principalmente para crear archivos y cambiar marcas de carpetas.


      ej: touch nombre [archivo-nuevo]


- **comando mkdir:** Comando utilizado para crear directorios o carpetas en linux.


       ej: mkdir [archivo-nuevo]

- **comando cat:** Es la visualizacion de un contenido de un archivo de 
texto. tambien muestra varios archivos.


        ej: cat [archivo-nuevo]
        ej: cat [archivo-nuevo] [archivo-nuevo]


- **comando ls:** Se utiliza para listar archivos o directorios.


        ej: ls [archivo-nuevo]


- **comando ls -l:** Lista un contenido del directorio en forma de columnas incluidas: permisos de contenido, número de enlaces al contenido. propietario del contenido.


       ej: ls -l [nombre archivo-nuevo]


- **comando pwd:** Utiliza el comando pwd para encontrar la ruta de tu directorio de trabajo actual. Simplemente introduciendo pwd te devolverá la ruta actual completa.


        ej: pwd [archivo-nuevo]


- **comando cp:** El comando cd se utiliza para copear archivos o directorios con su contenido.


        ej: cp ["archivo-nuevo"] ["archivo-nuevo2"]


- **comando mv:** Se utiliza principalmente el comando mv para mover archivos,pero tambien es utilizado para para cambiar el nombre a un archivo.


        ej: mv[archivo-nuevo] [archivo-nuevo2]

        ej: mv [nombre-archivo-antiguo2]  [nombre-archivo-nuevo2]


- **comando rm:** es un comando que se utiliza para remover archivos dentro de un directorio.


      rm [archivo-nuevo]


- **comando chmod:** Es un comando que modifica permisos de lecrura, escritura y ejecucion de un archivo o un directorio.


         ej:chmod [opcion] [permiso] [nombre_archivo]*
           : chmod 746 [archivo-nuevo]*


- **comando man:** Proporsiona un comando manual a un usuario de cualquier comando o terminal que pueda estar ejecutando en la terminal.


        ej: man [comando que le quieras ejecutar]


- **comando echo:** El comando echo es utilizado para mostar una linea de texto utilizando la salia estandar.


      ej:echo [opcion y texto] 


- **comando su:** El comando switch user o su permite ejecutar un programa como un usuario diferente. Este cambia la cuenta administrativa en la sesión de inicio de sesión actual. 

      **ej: su [nombre del usuario] [nombre del usuario2]*


- **comando ll:** este comando enumera toda la informacion de un archivo, incluido slos archivos ocultos. mientras que el ls -l enumera solo los  archivos explicitos.


- **adduser:** este comando se utiliza para crear nuevos usuarios en tu linux.


      **ej: [sudo adduser usuario]*


- **addgroup:** es un comando que te permite añadir usuarios nuevos a determinados grupos, pero cada usuario tienen que corresponder con permisos determinados que se les ejecute el super usuario. 


      **ej: [sudo addgroup nombre del grupo]*


- **groupdel:** este comando permite eliminar a los usuarios añadidos a un grupo determinando.


      **ej:sudodel [nombre del usuario]*


- **chown:** el comando chwon puede cambiar al propietario de los archivo. todos los arhitos tiene su propietario, en caso de los archivos nuevos el usuario que crea el archio es el propietario de dicho archivo.


      **ej: sudo chwon [archivo propietario]*


- **cd:** el comando cd se utiliza para poder moverte dentro de un archivo o un directorio del sistema. se puede utilizar para cambiar de directorio especializando una ruta absoluta desde la raiz o una relativa desde tu ubicacion actual.


       **ej: cd archivo-nuevo (relativa) home/archivo-nuevo/trabajos (absoluta).*



- **cd ..:**  el comando cd .. que te sube un nivel superior de tu archivo o directorio de donde estas ubicados.

       **cd .. [archivo o home ]  

- **ls -a:** el comando ls -a te muestra un listado de los contenidos ocultos de los archivos o directorios.

      **ls -a  [listados de archivos o directorios ocultos]

 
   ## Uso del comandos ps


    **PS:** El comando ps produce una instantánea de procesos de ejecucion.Y los resultados de los procesos son estáicos.

    Ej: PID   TTY      TIME   CMD
 
      5425   PTS/2   00:00:00  bash 
      5469   pts/2   00:00:00  ps

  
   ***PS AUX**: Te muestra todos los procesos en el sistema linux

   
   
   ***PS top**: Este comando te ordena un listado del uso del cpu, mostrando el proseso que consume mas recursos colocandose en la parte superior.

   

  ## claves  /   funciones

  ***Ps -k:** te finaliza un proceso que estes ejecutando.

  ***Ps -M:** te ordena la lista por uso de memoria.

  ***Ps -N:**Te ordena una lista de por PID.


  ***Ps -r:**te cambia la prioridad de un proceso.
   
   
   ***KILL**: Este comando es un operativo de unix, kill es utilizado para enviar msj a los procesos ejecutados en el sistema. Por defecto el msj que se le envio da una señal determinada que limpia su estado y sale del proceso.


    Ej: kill 5767


  
    **PS -A:** Te crea una lista ordenada de todos los procesos activos.



   ***Ps -U:** (root u)Este proceso te muestra los permisos del root. 


   ***Ps -T**: el comando ps -T, te imprime los distintos procesos activos que se ejecutan en la termnal.


   ***Ps -C** **NOMBRE-PROCESO*: 
   Este proceso te filtra la lista por nombre del proceso. no obstante, este comando tambien te muestra los procesos hijos del proceso especificado.



   

