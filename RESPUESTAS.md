1. Preguntas
¿Para qué sirven user.name y user.email? ¿Dónde aparecerán más adelante?

Sirven para indentificar quien hace los cambios y luego aparecen para publicar en Git.

¿Por qué GitHub no permite usar la contraseña de la cuenta para subir código por HTTPS?

Por que se hace por tokens para mas seguridad.

2. Preguntas
¿Por qué no se debe subir la carpeta .venv al repositorio?

por el .gitignore y que es el entorno virtual.

¿Qué significaba el color rojo antes del commit? ¿Y qué color tendría un archivo modificado después?

Significa que no esta guardado con el commit y si se modifica luego seria azul.

3. Preguntas
¿Qué es origin?

Es de donde parte la rama principal (main)

Explica con tus palabras la diferencia entre commit y push.

Commit: guarda los cambios en el historial de Git en tu ordenador.
Push: envía esos cambios al repositorio remoto, por ejemplo, a GitHub.

4. Preguntas
¿Por qué es mejor hacer dos commits pequeños que uno grande con todo?

Para tener mas margen de maniobra en caso de fallar.

Escribe un ejemplo de mensaje de commit malo y explica por qué lo es.

LLamar al commit "Cambios", ya que no se indaga en que "cambios" son.

5. Preguntas
¿Qué ventaja tiene trabajar en una rama en lugar de directamente en main?

Pues que puedes experimentar y trabajar sin que el condigo principal se vea afectado.

¿Qué es una fusión fast-forward y por qué se ha producido aquí?

Una fusión fast-forward es una fusion que se da cuando las ramas no tienen diferencias entre si.

6. Preguntas
¿Por qué Git no pudo fusionar automáticamente esta vez y sí en la fase 5?

Porque ambas ramas modificaron la misma parte de un archivo y Git no pudo decidir qué versión conservar.

¿Qué habría pasado si hubieras pulsado Accept Theirs?

Se habría conservado la versión del archivo de la otra rama, descartando los cambios conflictivos de la actual.

7. ¿Por qué conviene hacer Update Project antes de empezar cada día?
Para evitar trabajar con una versión desactualizada del proyecto.

8. Preguntas
¿Qué aporta una pull request frente a fusionar directamente en local como en la fase 5?

Permite revisar el código, comentar los cambios y detectar errores antes de integrarlos en la rama principal.

¿Por qué el commit hecho después de crear la PR apareció en ella sin hacer nada más?

Porque se hizo en la misma rama asociada a la pull request y, al subirlo, se añadió automáticamente.

9. Preguntas
¿Qué diferencia hay entre Pop y Apply al recuperar un stash?

Pop: recupera los cambios y elimina el stash si se aplican correctamente.
Apply: recupera los cambios, pero conserva el stash.

10. Preguntas
Completa: 

Rollback sirve para descartar cambios locales; 
Amend para modificar el último commit; 
Undo Commit para sirve para deshacer el último commit guardando los cambios ; 
Revert para sirve para crear un nuevo commit que revierte los cambios de otro commit.

¿Por qué pudiste recuperar borrador.txt si Git nunca lo había guardado?

Porque el archivo seguía existiendo localmente.

11. Preguntas

¿Cuántos commits tiene main en total? 

6

¿Cuántos son commits de merge? 

2

¿Qué commit introdujo la validación del rango? 

Busca ese cambio en el historial y copia los 7 primeros caracteres de su hash.

86f3fa0f