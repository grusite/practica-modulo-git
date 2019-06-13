# README practica git

* ¿Qué comando utilizaste en el paso 11? 
	> ```git reset --hard HEAD~1```

	* ¿Por qué?
		> Con el ```HEAD~1``` le digo que vuelvo al comit anterior y con --hard le digo que pierda lo que tenía en el workinfo

* ¿Qué comando o comandos utilizaste en el paso 12?
	> ```git reset --hard HEAD@{1}```

	* ¿Por qué?
		> Porque es el anterior commit del reflog de donde venía antes del anterior reset

* El merge del paso 13, ¿Causó algún conflicto?
	> No

	* ¿Por qué?
		> Porque la rama master está apuntando a un commit anterior por lo que ya pertenece a la historia de styled

* El merge del paso 19, ¿Causó algún conflicto?
	> Sí

	* ¿Por qué?
		> Porque el fichero git.nuestro ha sido modificado en las dos ramas tocando las mismas líneas

* El merge del paso 21, ¿Causó algún conflicto?
	> No

	* ¿Por qué?
		> Porque con un simple fast-forward ha podido mergear debido a que el cambio es una simple adición de código (en este caso los estilos) que no genera conflicto

* ¿Qué comando o comandos utilizaste en el paso 25?
	> ``` git log --oneline --graph ```

* El merge del paso 26, ¿Podría ser fast forward?
	> Sí

	* ¿Por qué?
		> Porque la rama master venía de un commit justo anterior que no ha divergido 

* ¿Qué comando o comandos utilizaste en el paso 27?
	> ``` git reset HEAD~1 ```

* ¿Qué comando o comandos utilizaste en el paso 28?
	> ``` git checkout -- git-nuestro.md ```

* ¿Qué comando o comandos utilizaste en el paso 29?
	> ```git branch -D title ```

* ¿Qué comando o comandos utilizaste en el paso 30?
	> ``` git reset --hard HEAD@{5} ``` [Podía haber hecho un checkout al anterior commit, crear la rama title otra vez, y volver a hacer un merge --no-ff pero me lo ahorraba con solo este paso]

* ¿Qué comando o comandos usaste en el paso 32?
	> ``` git reset --hard 9fc36eb ```

* ¿Qué comando o comandos usaste en el punto 33?
	> ``` git reset --hard HEAD@{3} ```


------------ En algunos pasos he modificado el log entre paso y paso para hacer pruebas y es posible que el número después del HEAD sea superior al que deba ser ---------------