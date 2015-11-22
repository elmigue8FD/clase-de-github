# clase-de-github - en la rama mejorandola
Esta es un ejemplo de github para la comunidad de @mejorandola


git clone "URL del pryecto"
git config --global user.name "Miguel"
ssh-keygen
	Donde quieres crear el archivo ssh
	Enter file in which to save the key (/c/Users/Paty/.ssh/id_rsa):
	Password para el archivo ssh
	Enter passphrase (empty for no passphrase):
	Muestral la clave ssh
	cat /c/Users/Paty/.ssh/id_rsa
$ git config --list//comprobar la configuracion actual de git
$ git init
$ touch README2
$ git add README2//añadelo a mi repositorio
$ git status//ver el estatus del repositorio
$ git commit -m "este es el primer archivo dede mi computadora"//enviar al repositorio un cambio
$ git remote add origin https://github.com/elmigue8FD/clase-de-github.git//conectarse remotamente a github
$ git pull origin master//nos traemos todos los archivos que tiene el repositorio de github
$ git push origin master//enviar cambios al repositorio