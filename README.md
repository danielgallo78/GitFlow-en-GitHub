# GitFlow-en-GitHub
practicando gitflow 


![image](https://github.com/danielgallo78/GitFlow-en-GitHub/assets/130160711/2b514784-e784-4fd0-aa21-dc1aa93676d6)

• Git checkout -b develop
Git push -u origin develop ( luego reviso el graph)

![image](https://github.com/danielgallo78/GitFlow-en-GitHub/assets/130160711/5361f6e5-b3d6-4c9b-a83e-8b899c07175f)

Luego creamos una rama que se llame login-como-ejemplo con el siguiente comando
• Git checkout -b feature/login-como-ejemplo
Todo lo que apartir de ahora se haga se va a guardar en esta rama 

![image](https://github.com/danielgallo78/GitFlow-en-GitHub/assets/130160711/2982c3f0-821d-4dcc-b749-3775d6eaa58b)

Luego crear un nuevo archivo llamado .txt
Touch login-como-ejemplo.txt

![image](https://github.com/danielgallo78/GitFlow-en-GitHub/assets/130160711/0f21e8fe-5c9e-466c-b583-3584c674bad6)

Luego agregarlo al archivo
• Git add login-como-ejemplo.txt
Luego hacerle el commit 
Git commit -m " se implementa ejemplo en login"

![image](https://github.com/danielgallo78/GitFlow-en-GitHub/assets/130160711/19ce582d-079c-4116-a809-2781580de75b)

Luego enviar la rama para llevarlo a github
Luego hacerle el push a la rama 
Git push -u origin feature/login-como-ejemplo

![image](https://github.com/danielgallo78/GitFlow-en-GitHub/assets/130160711/fb834d8b-d806-4ba9-a646-f6dd7c597168)

Una ves listo  se tendria que encontrar una version aparte fuera de la original para trabajar sin causar problemas.

![image](https://github.com/danielgallo78/GitFlow-en-GitHub/assets/130160711/7a212849-dc82-403c-8d42-37812ecc62c5)

Paso siguiente:

Después ya desde github una ves hecho los pasos anteriores
Hay que hacer un pull request para agregar la rama ya terminada

	• Repositorio > pull Request > New pull request
	• Base: develop
	• Compare: feature/login-como-ejemplo

Repositorio > pull Request > New pull request

![image](https://github.com/danielgallo78/GitFlow-en-GitHub/assets/130160711/0e186dee-5f3b-4597-a8b0-2fd1e8d7b765)

Se hace el new pull request

![image](https://github.com/danielgallo78/GitFlow-en-GitHub/assets/130160711/d806df4d-6ab6-4013-b516-f1a55b9a0265)

Seleccionar donde se va hacer los cambios

![image](https://github.com/danielgallo78/GitFlow-en-GitHub/assets/130160711/ab8cb5cc-d2ba-4f73-96e8-cef9827cadbd)

Se hace un create pull request 
Se puede dejar un comentario y nuevamente un create pull request


![image](https://github.com/danielgallo78/GitFlow-en-GitHub/assets/130160711/be5b36e7-9911-4550-a547-c8e9995fed68)

Paso siguiente seria hacer un merge que en este caso lo haría la persona con permiso la cual primero va a chequear los cambios y probarlos antes de realizar el merge

Una ves comprobado y todo listo se pasa hacer el merge

![image](https://github.com/danielgallo78/GitFlow-en-GitHub/assets/130160711/84a217cf-874a-46f9-a6ed-c454db99dd87)

Una ves echo el merge y si todo sale bien tendria que quedar el icono color violeta, eso quiere decir que salió todo bien y sin problemas 

Ejemplo siguiente imagen:

![image](https://github.com/danielgallo78/GitFlow-en-GitHub/assets/130160711/c49842f0-62e3-4406-a20e-a4bddc5bda6d)

vista de como iria en la terminal de vscode:


![image](https://github.com/danielgallo78/GitFlow-en-GitHub/assets/130160711/ba918e9b-63b9-490b-b686-a26f051a0359)























