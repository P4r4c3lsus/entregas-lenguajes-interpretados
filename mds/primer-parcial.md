# Examen Primer Parcial 

1. #### ¿Qué es y para qué sirve Visual Studio Code?

Nos sirve para crear código y poder acceder al git.
 
2. #### ¿Qué es y para qué sirve la Terminal de Comandos?

Nos permite interactuar con la computadora sin sus interfaces gráficas.

3. #### ¿Qué es y para qué sirve Markdown?

Nos ayuda a crear interfaces gráficas en visual studio code.

4. #### ¿Qué es y para qué sirve Git?

Nos permite trabajar sobre un mismo código.

5. #### ¿Qué es y para qué sirve GitHub?

Nos ayuda a subir los repositorios creados en git o incluso a descargar repositorios publicos.

6. #### ¿Para qué sirven los siguientes comandos: pwd, whoami, touch, mkdir, cp, mv, ls, clear, cd y rm? 
El comando _**pwd**_ nos ayuda para saber en que directorio estoy trabajando.

El comando _**whoami**_ nos auyda a saber con que usuario estamos trabajando dentro de la terminal.

El comando _**touch**_ nos permite crear archivos ya sean del tipo que quieras.

El comando _**mkdir**_ nos permite crear directorios.

El comando _**cp**_ nos permite copiar ya sea el archivo o el directorio.

El comando _**mv**_ nos permite mover el archivo o directorio de dirección.

El comando _**ls**_ nos permite listar los directorios o archivos que tenemos dentro.

El comando _**clear**_ nos permite limpiar la terminal de git, para que esta no se vea saturada o nos distraiga con tanto comando.

El comando _**cd**_ nos permite cambiar de directorio.

El comando _**rm**_ nos permite eliminar un archivo.

7. #### ¿Qué significan los siguiente caracteres en la terminal de Comandos: ./, ../, /, y ~?

El caracter _**./**_ nos permite regresar un directorio arriba.

El caracter _**../**_ nos permite regresar dos directorios arriba.

El caracter _**/**_ nos permite ver en que directorio estamos.

El caracter _**~**_ nos permite regresar al directorio _home_

8. #### ¿Cómo se inicializa un repositorio en Git?

```markdown
git innit 
git add . (para subir y guardar todos los cambios hechos)
git commit -m "Pones el commit que quieras"
git commit branch -M main (para llamar la rama principal "main" y sepamos donde estamos)
git remote add origin (añades el link de tu repositorio de github)
git push -u origin main (añade lo trabajado en tu repositorio de github)
```

9. #### ¿Cómo creas un repositorio en GitHub?

Para crear un repositorio a _**GitHub**_ te tienes que ir a tu icono de perfil en el mismo github, picarle a donde diga _**Repositorios**_ ahí te aparece la opción de _**New**_ y ahi te va indicar que le pongas un nombre, una descripción en caso de que quieras añadirle una y poner si quires que el repositorio sea publico o privado.

10. #### ¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub?
```markdown
git remote add origin (añades el link de tu repositorio de github)
git push -u origin main (añade lo trabajado en tu repositorio de github)
```

11. #### ¿Cuál es el flujo básico de trabajo en Git y GitHub?, explicalo indicando la secuencia de comandos?

Cuando estemos trabajando y queramos guardar lo que hemos hecho aplicamos el comando _**git add .**_ el cual va a subir los cambios al repositorio y guardalos, después añadimos un commit con el comando _**git commit -m**_, el cual aquí los cambios ya se han aplicado y registrados en el git, después añadimos el comando _**git push**_, el cual sube los cambios hechos en el repositorio a tu GitHub, y en dado caso que estemos trabajando en equipo y queramos descargar los cambios que hicieron añadimos el comando _**git pull**_ el cual nos vas a "actualizar" los cambios hechos por el equipo.

12. #### ¿Para qué sirve el archivo .gitignore?

El comando _**.gitignore**_ nos ayuda a ignorar los archivos que nosotros queramos.

13. #### ¿Cuál es el propósito de una rama?

Nos permite realizar cambios en un mismo proyecto pero que este no llegue afectar a la rama principal y podamos tener varias ramas a la vez trabajando en diferentes cosas.

14. #### ¿Qué es una fusión?

Une las diferentes ramas que creamos y las fusiona en la rama principal

15. #### Explica los diferentes tipos de fusión que existen.

Existen dos tipos de fusion: 
- Fast-forward: Nos permite fusionar las ramas de manera automática.
- Manual Merge: Nos aparece en pantalla los cambios que se haran al momento de hacer las fusiones.

16. #### ¿Cómo puedes ver el historial de tu repositorio?

Con el comando _**git log --oneline**_

17. #### ¿Cuál es el propósito de una etiqueta?

Levar un mejor control las versiones que vamos publicando.

