Config Global
    
    git config --global user.name "Jose"
    git config --global user.email "jose@gmail.com"

Copiar el Repositorio a la PC

	git clone git@github.com:gzaldana/myapp.git
	cd myapp

Crear un tocken clasico GH
    
    En GH ir a setting and tokens clasico asignando los permisos necesarios

Loguearse usando los comandos:

	git config --list : checkea los parametros que hay actualmente.
	git config --global credential.helper store
	git push -u origin main: aqui pude el user y el token creado
