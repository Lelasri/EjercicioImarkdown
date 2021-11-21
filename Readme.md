## **Ejercicio propuesto para utilizar la terminal y markdown**

### En este archivo voy a especificar los enunciados de los ejercicios propuestos y explicaré cómo se harían. 

#### **1. Debemos actualizar el sistema operativo Ubuntu**



- **Sincronizar la base de datos local y el repositorio.**
Para ello escribiremos lo siguiente en la terminal de Ubuntu: *sudo apt update*

- **Visualizar los programas a actualizar.**
Aquí veremos un mensaje de Ubuntu en el que se nos dice que hay que hacer: *run 'apt list --upgradable'*.

- **Actualizar nuestro sistema operativo.**
Escribimos en la terminal el mensaje que ha aparecido y ya lo tendríamos actualizado.



#### **2. Determinar con un comando cuál es nuestra posición en el árbol del usuario**



- Tanto en Ubuntu como en cygwin lo que hacemos es listar los directorios que tenemos escribiendo: *ls*



#### **3. Visualizar con un comando el árbol del usuario desde */home/nuestrousuario*/**



- En este caso en Ubuntu escribimos *tree*.



#### **4. Crear en */home/nuestrousuario*/ un folder llamado *ejercicios*.**



- Esto lo hacemos en Ubuntu escribiendo: *mkdir Ejercicios*


- En cygwin vamos a llamarlo *EjercicioImarkdown*, y lo creamos así: *mkdir EjercicioImarkdown*.



#### **5. Verificar que lo hemos creado en el lugar correcto y su posición en el árbol**



- En Ubuntu comprobamos escribiendo: *cd* que estamos en la home, y luego escribimos: *tree*. Allí vemos que aparece nuestra carpeta.

- En cygwin lo comprobamos de la misma manera, pero listamos con *ls* para ver que aparece. 



#### **6. Movernos a la carpeta *EjercicioImarkdown* y verificar con el comando que estamos ahí.**



- Esto lo hacemos escribiendo: *cd EjercicioImarkdown*

- Después verificamos que estamos dentro de la carpeta escribiendo el comando: *pwd*



#### **7. Creamos un archivo de texto dentro del folder *EjercicioImarkdown*, escribimos: *texto*, y lo salvamos adecuadamente con el nombre *parte_1*.**



- En Ubuntu esto lo hacemos escribiendo en la terminal: nano *EjercicioImarkdown/texto* 

- Después hacemos CONTROL + x y lo guardamos como: *parte_1*



#### **8. Retrocedemos a */home/nombreusuario/* utilizando el comando de retroceso, o bien el comando de path absoluto. Verificamos con un comando nuestra posición.**



- En este caso, para retroceder escribiríamos: *cd --*

- Si lo hiciéramos con la ruta absoluta, escribiríamos: *cd /home/nombreusuario/* , o simplemente *cd*.



#### **9. Con el comando y los parámetros adecuados generamos un listado**



- En este caso para generar un listado escribimos: *ls* 



#### **10. Con el comando anterior agregamos otro parámetro y visualizamos los archivos ocultos también**



- Lo que hacemos es escribir el siguiente comando: *ls -a*



#### 11. **Desde */home/nuestrousuario* creamos otro archivo de texto llamado: *parte_2*, escribimos un texto y lo salvamos.**



- Tanto en Ubuntu como en cygwin esto lo hacemos escribiendo primero: cd , para así volver a nuestra home. Allí escribimos: *nano parte_2* . Una vez dentro de nano escribimos *texto 2*, y lo salvamos con control X. Luego Y, y guardamos el nombre propuesto. 


 
#### **12. Desde la raíz del usuario creamos un folder llamado: *trabajos*.** 



- En ambos casos esto se hace situándonos en nuestra home con *cd*. Luego escribimos: *mkdir trabajos* 



#### **13. Desde la raíz del usuario creamos un archivo de texto plano llamado *parte_3*. Lo salvamos, salimos y verificamos que esté en el lugar adecuado.** 



- Hacemos *cd* para volver a home. Allí escribimos: *nano parte_3*. Lo salvamos con *control + x*, y luego verificamos que está en el lugar adecuado.
- En el caso de Ubuntu lo verificamos con el comando *tree*. 
- En el caso de cygwin lo verificamos con el comando *ls* directamente. 



#### **14. Desde la raíz del usuario abrimos los tres archivos creados, agregamos en cada uno de ellos nuestro nombre al final del texto, lo salvamos y salimos del editor.** 



- En ambos casos esto lo hacemos escribiendo *nano + el nombre del archivo determinado*. Una vez allí se nos abrirá nano, y podremos editarlo. 



#### **15. Nos dirigimos al folder donde está ubicado el archivo *parte_3*. Verificamos la ubicación con el comando adecuado.**



- Vamos a la home con el comando *cd*. Allí está el archivo de texto *parte_3*. Verificamos la ubicación con el comando *pwd*. 



#### **16. Con el comando adecuado copiamos el archivo: *parte_3* en el folder donde están los otros dos archivos y verificamos con el comando *tree*.**



- En este caso creo que en los enunciados falta pedir que copiemos el archivo *parte_2* en la carpeta de *EjercicioImarkdown*. Lo hago, y también copio el documento de texto *parte_3* así:



- Para copiar el archivo de texto *parte_2* en la carpeta de *EjercicioImarkdown* escribo: *cp parte_2  /EjercicioImarkdown*
- Para copiar el archivo de texto *parte_3* en la carpeta de *EjercicioImarkdown* escribo: *cp parte_3  /EjercicioImarkdown*



#### **17. Desde la actual posición en el árbol nos movemos al folder donde están los tres archivos recién creados (ejercicios). Verificamos nuestra posición**



- Primero escribimos *cd*, para volver a la home. Luego escribimos *cd EjercicioImarkdown*, para ir a nuestra carpeta. Para verificar nuestra posición escribimos: *pwd*. Una vez verificada, en cygwin listamos con *ls* para ver nuestros archivos. En Ubunto escribimos *tree*, para ver el árbol. 



#### **18. Con el comando adecuado listamos los archivos del folder donde estamos ubicados.**



- Esto lo hacemos con el comando *ls*. 



#### **19. Utilizamos el comando adecuado para leer los tres archivos simultáneamente. Visualizaremos sus textos en líneas separadas (en el terminal).**



- Esto lo hacemos con el comando *cat*. Escribimos: *cat parte_1 cat parte_2 cat parte_3*, damos al intro y nos salen sus textos. 



#### **20. Concatenamos los tres archivos y al nuevo archivo lo llamamos: textoTotal*.**



- Esto lo hacemos escribiendo lo siguiente: *cat parte_1 cat parte_2 cat parte_3 >> textoTotal*



#### **21. Listamos los archivos del folder y verificamos si está *textoTotal* **



- Esto lo hacemos con el comando *ls*. 



#### **22. Con el editor abrimos *textoTotal* y escribimos: *trabajo finalizado*. Lo salvamos y salimos.**



- Esto lo hacemos escribiendo *nano textoTotal* dentro de nuestra carpeta *EjercicioImarkdown*. Se abrirá nano, escribimos: *trabajo finalizado*. Lo guardamos con *control + x* y salimos. 



#### **23. Ahora borramos o removemos el folder: *trabajos*.**



- Como es una carpeta vacía la eliminamos con el comando: *rmdir*. Escribimos: *rmdir trabajos*. Y se borrará. 



#### **24. Nos movemos desde nuestra posición actual a */home/nuestrousuario/*.**



- Esto lo hacemos con el comando *cd*. 



#### **25. Desde la raíz del usuario creamos un folder llamado: *final*.**



- En este caso no voy a hacerlo en este ejemplo, ya que quiero subirlo a git y si lo dejo en home no se verá en la carpeta que yo suba. 




# *EjercicioImarkdown*
