
Ejercicio 1
===========
Responde en este fichero a las siguientes preguntas: 

1. ¿Cómo se configura el email de manera global en GIT?
Respuesta: git config --global user.email manufp6@gmail.com

2. ¿Qué es un Pull Request?
Respuesta: Es una peticion del propietario de un repositorio folkeado le hace al propietario del repositorio original para actualizar los cambios hechos

3. ¿Para qué sirve HEAD en GIT?
Respuesta: Indica el ultimo commit en el repositorio en el momento actual

4. ¿En cuántos estados diferentes puede estar un fichero en GIT?
Respuesta: committed, modified y staged.

5. ¿Qué número identifica de manera única a cada commit?
Respuesta: El hash, haciendo git log podemos verlos.

6. ¿Cómo retrocederías en los commits para tener el directorio de trabajo como lo tenías hace 3 commits?
Respuesta: Utilizariamos git log para ver el hash del commit al que queremos volver, una vez localizado usaremos git reset --hard #commit para mover el puntero head al commit deseado.

7. ¿Cómo explicarías un conflicto en GIT?
Respuesta: 

8. ¿Con qué comando dejaríamos de tener el directorio bajo control de versiones?
Respuesta: rm .git

9. ¿Cómo añadirías la URL de un repositorio remoto?
Respuesta: git remote add origin https://github.com/NOMBRE_USUARIO/NOMBRE_PROYECTO.git

10. ¿Cómo explicarías qué ha ocurrido cuando tras la ejecución de un comando de GIT nos responde: "You are in 'detached HEAD' state"?
Respuesta: Cuando le estas haciendo checkout a un commit que no esta en la rama actual
